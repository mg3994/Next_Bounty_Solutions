# Next_Bounty_Solutions
# TODO Tap
use 
```
adb shell input tap <x-coordinate> <y-coordinate> # refence of below
adb shell input tap 500 700
or use adb shell input keyevent KEYCODE_TAB three times


adb shell input text "your_email@example.com"
adb shell input keyevent KEYCODE_ENTER

```

# verify robot Screen
Tab 
Enter
Enter

# experimental Stuff
adb shell input keyevent KEYCODE_DPAD_DOWN

Navigation Keys: Depending on the layout of the app, navigation keys such as KEYCODE_MENU, KEYCODE_BACK, or KEYCODE_HOME might trigger changes in focus.

# references

>adb shell dumpsys window | findstr /R /C:"mCurrentFocus" /C:"mFocusedApp"
    mFocusedApp=Token{ebcf014 ActivityRecord{3d8ba67 u0 com.google.android.gms/.auth.uiflows.minutemaid.MinuteMaidActivity t158}}
  mCurrentFocus=Window{c6d67c2 u0 com.google.android.gms/com.google.android.gms.auth.uiflows.minutemaid.MinuteMaidActivity}
  mFocusedApp=AppWindowToken{b1080bd token=Token{ebcf014 ActivityRecord{3d8ba67 u0 com.google.android.gms/.auth.uiflows.minutemaid.MinuteMaidActivity t158}}}
