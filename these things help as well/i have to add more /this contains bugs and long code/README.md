```dart
import 'dart:io';

import 'package:example/constants/app_strings.dart';
import 'package:flutter_driver/flutter_driver.dart';
import 'package:test/test.dart';

void main() {
  group('Accept Permission Test', () {
    late FlutterDriver driver;

    SerializableFinder _getFinderForKey(String key) {
      return find.byValueKey(key);
    }

    // Connect to the Flutter driver before running any tests.
    setUpAll(() async {
      driver = await FlutterDriver.connect(printCommunication: true);
    });

    // Close the connection to the driver after the tests have completed.
    tearDownAll(() async {
      driver.close();
    });
    test('Get platform information', () async {
      //command to get platform information from which i am running , is it Windows , Mac or Linux ,etc
      final vm = await driver.serviceClient.getVM();

      // Access the platform information
      final platform = vm.operatingSystem;

      String operatingSystem = Platform.operatingSystem;

      switch (operatingSystem) {
        case 'windows':
          print('Tests are being run from a Windows');
          break;
        case 'macos':
          print('Tests are being run from a macOS');
          break;
        case 'linux':
          print('Tests are being run from a Linux');
          break;
        default:
          print('Tests are being run from a : Unknown operating system');
      }

      print('Platform: $platform');

      // Perform assertions or further actions based on the platform
      // For example:
      if (platform!.toLowerCase().contains('android')) {
        // Handle Android
        print('Running on Android');
      } else if (platform.toLowerCase().contains('ios')) {
        // Handle iOS
        print('Running on iOS');
      } else {
        print('Unsupported platform');
      }
    });

    test('Accept permission should navigate to main View', () async {
      final permissionButtonFinder = _getFinderForKey('permission_button');
      // final homeViewFinder = _getFinderForKey('home_view');

      await driver.waitFor(permissionButtonFinder);
      await driver.tap(permissionButtonFinder);
      // Determine platform from environment variable or test parameter
      final vm = await driver.serviceClient.getVM();
      // Access the platform information
      final platform = vm.operatingSystem;

      // final result = await driver.requestData(
      //     ksAcceptPermission); //Not in Use but will be used in Route Screen  Logic

      // Accept permissions using adb (Android)
      if (platform!.toLowerCase().contains('android')) {
        await _grantAndroidPermission();
      }
      //Accept for iOS
      if (platform.toLowerCase().contains('ios')) {
        // Execute simctl command to grant permission (iOS)
        await Process.run('xcrun', [
          'simctl',
          'privacy',
          'location',
          'com.example.example',
          'grant'
        ]); // TODO: Add seprate logic for this bundle name also modify if "booted"
      }
      // TASK: If you need to add code here, you can replace the line above with
      // your permission accept code
      //TODO: YOUR Screen Test Logic Here
      // await driver.waitFor(homeViewFinder,
      //     timeout: Duration(seconds: 3)); //TODO: increase the time
    });

///////////////
    ///
    ///
    ///
    test('input email and press enter', () async {
      // Check if the desired activity is currently focused
      final isActivityonFocus = await isActivityFocused(
          'com.google.android.gms.auth.uiflows.minutemaid.MinuteMaidActivity'); // this is for Google Login Screen in Android , Not that Firebase Login

      if (isActivityonFocus) {
        // Navigate through the native dialog using tab until the keyboard is visible
        while (!(await isKeyboardVisible())) {
          await Process.run(
              'adb', ['shell', 'input', 'keyevent', 'KEYCODE_TAB']);
          await Future.delayed(Duration(seconds: 1)); // Adjust delay as needed
        }

        // Once the keyboard is visible, input email directly
        await Process.run(
            'adb', ['shell', 'input', 'text', 'your_email@example.com']);
        await Process.run(
            'adb', ['shell', 'input', 'keyevent', 'KEYCODE_ENTER']);
      }
      // await driver.enterText("your_email@example.com");
      // await driver.tap(find.text(
      //     "Submit")); // Or whatever element you want to tap after entering email
    });
  });
}

Future<bool> isActivityFocused(String activityName) async {
  final result = await Process.run('adb', ['shell', 'dumpsys', 'window']);
  final output = result.stdout.toString();

  // Check if the desired activity is found in the output
  return output.contains(activityName);
}

Future<bool> isKeyboardVisible() async {
  final result = await Process.run('adb', ['shell', 'dumpsys', 'input_method']);
  return result.stdout.toString().contains('mInputShown=true');
}

Future<void> _grantAndroidPermission() async {
  // Replace <package_name> and <permission> with actual values
  final packageName = "com.example.example"; // TODO: Add seprate locic for this
  final permission1 = "android.permission.ACCESS_FINE_LOCATION";
  final permission2 = "android.permission.ACCESS_COARSE_LOCATION";

  // Execute adb command to grant permission
  await Process.run('adb', ['shell', 'pm', 'grant', packageName, permission1]);
  await Process.run('adb', ['shell', 'pm', 'grant', packageName, permission2]);
}

```
