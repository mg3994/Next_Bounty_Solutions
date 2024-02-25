```
adb shell dumpsys input_method
* daemon not running; starting now at tcp:5037
* daemon started successfully
Current Input Method Manager state:
  Input Methods: mMethodMapUpdateCount=9 mBindInstantServiceAllowed=false
  InputMethod #0:
    mId=com.google.android.apps.inputmethod.zhuyin/.ZhuyinInputMethodService mSettingsActivityName=com.google.android.apps.inputmethod.zhuyin.preference.SettingsActivity mIsVrOnly=false mSupportsSwitchingToNextInputMethod=true
    mIsDefaultResId=0x7f0b0010
    Service:
      priority=0 preferredOrder=0 match=0x108000 specificIndex=-1 isDefault=false
      ServiceInfo:
        name=com.google.android.apps.inputmethod.zhuyin.ZhuyinInputMethodService
        packageName=com.google.android.apps.inputmethod.zhuyin
        labelRes=0x7f1100f0 nonLocalizedLabel=null icon=0x0 banner=0x0
        enabled=true exported=true directBootAware=true
        permission=android.permission.BIND_INPUT_METHOD
        flags=0x0
        ApplicationInfo:
          name=com.google.android.apps.inputmethod.zhuyin.ZhuyinApp
          packageName=com.google.android.apps.inputmethod.zhuyin
          labelRes=0x7f1100f0 nonLocalizedLabel=null icon=0x7f030001 banner=0x7f020053
          className=com.google.android.apps.inputmethod.zhuyin.ZhuyinApp
          processName=com.google.android.apps.inputmethod.zhuyin
          taskAffinity=com.google.android.apps.inputmethod.zhuyin
          uid=10110 flags=0x308abe45 privateFlags=0x1100 theme=0x7f12000e
          requiresSmallestWidthDp=0 compatibleWidthLimitDp=0 largestWidthLimitDp=0
          sourceDir=/system/app/ZhuyinIME/ZhuyinIME.apk
          seinfo=default:targetSdkVersion=26
          seinfoUser=:complete
          dataDir=/data/user/0/com.google.android.apps.inputmethod.zhuyin
          deviceProtectedDataDir=/data/user_de/0/com.google.android.apps.inputmethod.zhuyin
          credentialProtectedDataDir=/data/user/0/com.google.android.apps.inputmethod.zhuyin
          sharedLibraryFiles=[/system/framework/org.apache.http.legacy.boot.jar]
          enabled=true minSdkVersion=17 targetSdkVersion=26 versionCode=2451413 targetSandboxVersion=1
          supportsRtl=false
          fullBackupContent=true
          HiddenApiEnforcementPolicy=3
  InputMethod #1:
    mId=com.google.android.googlequicksearchbox/com.google.android.voicesearch.ime.VoiceInputMethodService mSettingsActivityName=com.google.android.apps.search.transcription.voiceime.standalone.settings.VoiceImeSettingsActivity mIsVrOnly=false mSupportsSwitchingToNextInputMethod=false
    mIsDefaultResId=0x0
    Service:
      priority=0 preferredOrder=0 match=0x108000 specificIndex=-1 isDefault=false
      ServiceInfo:
        name=com.google.android.voicesearch.ime.VoiceInputMethodService
        packageName=com.google.android.googlequicksearchbox
        labelRes=0x7f152ebd nonLocalizedLabel=null icon=0x0 banner=0x0
        processName=com.google.android.googlequicksearchbox:search
        enabled=true exported=true directBootAware=false
        permission=android.permission.BIND_INPUT_METHOD
        flags=0x0
        ApplicationInfo:
          name=com.google.android.apps.gsa.binaries.velvet.app.VelvetRoot_Application
          packageName=com.google.android.googlequicksearchbox
          labelRes=0x7f150106 nonLocalizedLabel=null icon=0x7f110010 banner=0x0
          className=com.google.android.apps.gsa.binaries.velvet.app.VelvetRoot_Application
          processName=com.google.android.googlequicksearchbox
          taskAffinity=null
          uid=10054 flags=0xa8dbbec5 privateFlags=0x518 theme=0x7f160ba6
          requiresSmallestWidthDp=0 compatibleWidthLimitDp=0 largestWidthLimitDp=0
          sourceDir=/data/app/com.google.android.googlequicksearchbox-DswiJA8nI8iWezHzneCVLQ==/base.apk
          splitSourceDirs=[/data/app/com.google.android.googlequicksearchbox-DswiJA8nI8iWezHzneCVLQ==/split_config.xxhdpi.apk]
          seinfo=default:privapp:targetSdkVersion=34
          seinfoUser=:complete
          dataDir=/data/user/0/com.google.android.googlequicksearchbox
          deviceProtectedDataDir=/data/user_de/0/com.google.android.googlequicksearchbox
          credentialProtectedDataDir=/data/user/0/com.google.android.googlequicksearchbox
          sharedLibraryFiles=[/system/framework/org.apache.http.legacy.boot.jar]
          splitClassLoaderNames=[null]
          enabled=true minSdkVersion=28 targetSdkVersion=34 versionCode=301306695 targetSandboxVersion=1
          supportsRtl=true
          fullBackupContent=true
          networkSecurityConfigRes=0x7f1900f8
          category=7
          HiddenApiEnforcementPolicy=2
  InputMethod #2:
    mId=com.google.android.inputmethod.japanese/.MozcService mSettingsActivityName=com.google.android.apps.inputmethod.japanese.preference.SettingsActivity mIsVrOnly=false mSupportsSwitchingToNextInputMethod=true
    mIsDefaultResId=0x7f0b000d
    Service:
      priority=0 preferredOrder=0 match=0x108000 specificIndex=-1 isDefault=false
      ServiceInfo:
        name=com.google.android.inputmethod.japanese.MozcService
        packageName=com.google.android.inputmethod.japanese
        labelRes=0x7f1100e0 nonLocalizedLabel=null icon=0x0 banner=0x0
        enabled=true exported=true directBootAware=true
        permission=android.permission.BIND_INPUT_METHOD
        flags=0x0
        ApplicationInfo:
          name=com.google.android.apps.inputmethod.japanese.JapaneseApp
          packageName=com.google.android.inputmethod.japanese
          labelRes=0x7f1100e0 nonLocalizedLabel=null icon=0x7f030001 banner=0x0
          className=com.google.android.apps.inputmethod.japanese.JapaneseApp
          processName=com.google.android.inputmethod.japanese
          taskAffinity=com.google.android.inputmethod.japanese
          uid=10101 flags=0x308abe45 privateFlags=0x1100 theme=0x7f12000d
          requiresSmallestWidthDp=0 compatibleWidthLimitDp=0 largestWidthLimitDp=0
          sourceDir=/system/app/JapaneseIME/JapaneseIME.apk
          seinfo=default:targetSdkVersion=25
          seinfoUser=:complete
          dataDir=/data/user/0/com.google.android.inputmethod.japanese
          deviceProtectedDataDir=/data/user_de/0/com.google.android.inputmethod.japanese
          credentialProtectedDataDir=/data/user/0/com.google.android.inputmethod.japanese
          sharedLibraryFiles=[/system/framework/org.apache.http.legacy.boot.jar]
          enabled=true minSdkVersion=17 targetSdkVersion=25 versionCode=6287405 targetSandboxVersion=1
          supportsRtl=false
          fullBackupContent=true
          HiddenApiEnforcementPolicy=3
  InputMethod #3:
    mId=com.google.android.inputmethod.korean/.KoreanIme mSettingsActivityName=com.google.android.apps.inputmethod.korean.preference.SettingsActivity mIsVrOnly=false mSupportsSwitchingToNextInputMethod=true
    mIsDefaultResId=0x7f0b0010
    Service:
      priority=0 preferredOrder=0 match=0x108000 specificIndex=-1 isDefault=false
      ServiceInfo:
        name=com.google.android.inputmethod.korean.KoreanIme
        packageName=com.google.android.inputmethod.korean
        labelRes=0x7f1100d7 nonLocalizedLabel=null icon=0x0 banner=0x0
        enabled=true exported=true directBootAware=true
        permission=android.permission.BIND_INPUT_METHOD
        flags=0x0
        ApplicationInfo:
          name=com.google.android.apps.inputmethod.korean.KoreanApp
          packageName=com.google.android.inputmethod.korean
          labelRes=0x7f1100d7 nonLocalizedLabel=null icon=0x7f030001 banner=0x7f020053
          className=com.google.android.apps.inputmethod.korean.KoreanApp
          processName=com.google.android.inputmethod.korean
          taskAffinity=com.google.android.inputmethod.korean
          uid=10102 flags=0x308abe45 privateFlags=0x1100 theme=0x7f12000e
          requiresSmallestWidthDp=0 compatibleWidthLimitDp=0 largestWidthLimitDp=0
          sourceDir=/system/app/KoreanIME/KoreanIME.apk
          seinfo=default:targetSdkVersion=26
          seinfoUser=:complete
          dataDir=/data/user/0/com.google.android.inputmethod.korean
          deviceProtectedDataDir=/data/user_de/0/com.google.android.inputmethod.korean
          credentialProtectedDataDir=/data/user/0/com.google.android.inputmethod.korean
          sharedLibraryFiles=[/system/framework/org.apache.http.legacy.boot.jar]
          enabled=true minSdkVersion=17 targetSdkVersion=26 versionCode=1551409 targetSandboxVersion=1
          supportsRtl=false
          fullBackupContent=true
          HiddenApiEnforcementPolicy=3
  InputMethod #4:
    mId=com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME mSettingsActivityName=com.google.android.apps.inputmethod.latin.preference.SettingsActivity mIsVrOnly=false mSupportsSwitchingToNextInputMethod=true
    mIsDefaultResId=0x7f0c00f6
    Service:
      priority=0 preferredOrder=0 match=0x108000 specificIndex=-1 isDefault=false
      ServiceInfo:
        name=com.android.inputmethod.latin.LatinIME
        packageName=com.google.android.inputmethod.latin
        labelRes=0x7f1302c0 nonLocalizedLabel=null icon=0x0 banner=0x0
        enabled=true exported=true directBootAware=true
        permission=android.permission.BIND_INPUT_METHOD
        flags=0x0
        ApplicationInfo:
          name=com.google.android.apps.inputmethod.latin.LatinApp
          packageName=com.google.android.inputmethod.latin
          labelRes=0x7f1302c0 nonLocalizedLabel=null icon=0x7f030003 banner=0x0
          className=com.google.android.apps.inputmethod.latin.LatinApp
          processName=com.google.android.inputmethod.latin
          taskAffinity=com.google.android.inputmethod.latin
          uid=10109 flags=0x28cabe45 privateFlags=0x1110 theme=0x7f140012
          requiresSmallestWidthDp=0 compatibleWidthLimitDp=0 largestWidthLimitDp=0
          sourceDir=/system/app/LatinImeGoogle/LatinImeGoogle.apk
          seinfo=default:targetSdkVersion=28
          seinfoUser=:complete
          dataDir=/data/user/0/com.google.android.inputmethod.latin
          deviceProtectedDataDir=/data/user_de/0/com.google.android.inputmethod.latin
          credentialProtectedDataDir=/data/user/0/com.google.android.inputmethod.latin
          enabled=true minSdkVersion=21 targetSdkVersion=28 versionCode=26761314 targetSandboxVersion=1
          supportsRtl=true
          fullBackupContent=true
          HiddenApiEnforcementPolicy=2
  InputMethod #5:
    mId=com.google.android.inputmethod.pinyin/.PinyinIME mSettingsActivityName=com.google.android.apps.inputmethod.pinyin.preference.SettingsActivity mIsVrOnly=false mSupportsSwitchingToNextInputMethod=true
    mIsDefaultResId=0x7f0b0010
    Service:
      priority=0 preferredOrder=0 match=0x108000 specificIndex=-1 isDefault=false
      ServiceInfo:
        name=com.google.android.inputmethod.pinyin.PinyinIME
        packageName=com.google.android.inputmethod.pinyin
        labelRes=0x7f110132 nonLocalizedLabel=null icon=0x0 banner=0x0
        enabled=true exported=true directBootAware=true
        permission=android.permission.BIND_INPUT_METHOD
        flags=0x0
        ApplicationInfo:
          name=com.google.android.apps.inputmethod.pinyin.PinyinApp
          packageName=com.google.android.inputmethod.pinyin
          labelRes=0x7f110132 nonLocalizedLabel=null icon=0x7f030001 banner=0x7f020053
          className=com.google.android.apps.inputmethod.pinyin.PinyinApp
          processName=com.google.android.inputmethod.pinyin
          taskAffinity=com.google.android.inputmethod.pinyin
          uid=10114 flags=0x308abe45 privateFlags=0x1100 theme=0x7f12000e
          requiresSmallestWidthDp=0 compatibleWidthLimitDp=0 largestWidthLimitDp=0
          sourceDir=/system/app/GooglePinyinIME/GooglePinyinIME.apk
          seinfo=default:targetSdkVersion=26
          seinfoUser=:complete
          dataDir=/data/user/0/com.google.android.inputmethod.pinyin
          deviceProtectedDataDir=/data/user_de/0/com.google.android.inputmethod.pinyin
          credentialProtectedDataDir=/data/user/0/com.google.android.inputmethod.pinyin
          sharedLibraryFiles=[/system/framework/org.apache.http.legacy.boot.jar]
          enabled=true minSdkVersion=17 targetSdkVersion=26 versionCode=4511409 targetSandboxVersion=1
          supportsRtl=false
          fullBackupContent=true
          HiddenApiEnforcementPolicy=3
  Clients:
  Client ClientState{3bbdb63 uid 10072 pid 2512}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@420e5ed
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@a5e4c22
    sessionRequested=false
    curSession=SessionState{uid 10072 pid 2512 method 9a4f6b3 session fd9c470 channel ClientState{3bbdb63 uid 10072 pid 2512} (server)}
  Client ClientState{fe6427e uid 10046 pid 29858}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@832f3e9
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@339086e
    sessionRequested=false
    curSession=SessionState{uid 10046 pid 29858 method 9a4f6b3 session 2ee4b0f channel ClientState{fe6427e uid 10046 pid 29858} (server)}
  Client ClientState{6eeb79c uid 1000 pid 1898}:
    client=android.view.inputmethod.InputMethodManager$1@e346e71
    inputContext=ControlledInputConnectionWrapper{connection=android.view.inputmethod.BaseInputConnection@e3de5a5 finished=false mParentInputMethodManager.mActive=false}
    sessionRequested=false
    curSession=null
  Client ClientState{26b16f7 uid 10082 pid 2942}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@ef13d7a
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@3ce892b
    sessionRequested=false
    curSession=SessionState{uid 10082 pid 2942 method 9a4f6b3 session efdb188 channel ClientState{26b16f7 uid 10082 pid 2942} (server)}
  Client ClientState{54c3721 uid 10109 pid 2193}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@ec5b746
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@e2a8d07
    sessionRequested=false
    curSession=null
  Client ClientState{1492b uid 1001 pid 2357}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@9805e34
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@894245d
    sessionRequested=false
    curSession=SessionState{uid 1001 pid 2357 method 9a4f6b3 session 71601d2 channel ClientState{1492b uid 1001 pid 2357} (server)}
  Client ClientState{ec36355 uid 10145 pid 10990}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@358f2a3
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@3df29a0
    sessionRequested=false
    curSession=SessionState{uid 10145 pid 10990 method 9a4f6b3 session 673a959 channel ClientState{ec36355 uid 10145 pid 10990} (server)}
  Client ClientState{6ab1ad7 uid 10131 pid 5817}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@ae691e
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@97e15ff
    sessionRequested=false
    curSession=SessionState{uid 10131 pid 5817 method 9a4f6b3 session 79d3fcc channel ClientState{6ab1ad7 uid 10131 pid 5817} (server)}
  Client ClientState{511222c uid 10038 pid 2206}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@b2c8215
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@2d3f92a
    sessionRequested=false
    curSession=SessionState{uid 10038 pid 2206 method 9a4f6b3 session aa8131b channel ClientState{511222c uid 10038 pid 2206} (server)}
  Client ClientState{5790cb2 uid 10064 pid 29683}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@1448cb8
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@b602a91
    sessionRequested=false
    curSession=SessionState{uid 10064 pid 29683 method 9a4f6b3 session 2107df6 channel ClientState{5790cb2 uid 10064 pid 29683} (server)}
  Client ClientState{9b72d63 uid 10171 pid 20136}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@9aac5f7
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@a11bc64
    sessionRequested=false
    curSession=SessionState{uid 10171 pid 20136 method 9a4f6b3 session a4bdecd channel ClientState{9b72d63 uid 10171 pid 20136} (server)}
  Client ClientState{d9791cb uid 10054 pid 1276}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@fbe8382
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@8bbca93
    sessionRequested=false
    curSession=SessionState{uid 10054 pid 1276 method 9a4f6b3 session 603ad0 channel ClientState{d9791cb uid 10054 pid 1276} (server)}
  Client ClientState{a973a8f uid 1000 pid 27626}:
    client=com.android.internal.view.IInputMethodClient$Stub$Proxy@7c49ac9
    inputContext=com.android.internal.view.IInputContext$Stub$Proxy@65555ce
    sessionRequested=false
    curSession=SessionState{uid 1000 pid 27626 method 9a4f6b3 session dce7cef channel ClientState{a973a8f uid 1000 pid 27626} (server)}
  mCurMethodId=com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME
  mCurClient=ClientState{5790cb2 uid 10064 pid 29683} mCurSeq=2555
  mCurFocusedWindow=android.os.BinderProxy@2f93b7b softInputMode=STATE_ALWAYS_HIDDEN|ADJUST_PAN client=ClientState{5790cb2 uid 10064 pid 29683}
  mCurId=com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME mHaveConnect=true mBoundToMethod=true
  mCurToken=android.os.Binder@a53256
  mCurIntent=Intent { act=android.view.InputMethod cmp=com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME (has extras) }
  mCurMethod=com.android.internal.view.IInputMethod$Stub$Proxy@9a4f6b3
  mEnabledSession=SessionState{uid 10064 pid 29683 method 9a4f6b3 session 2107df6 channel ClientState{5790cb2 uid 10064 pid 29683} (server)}
  mImeWindowVis=
  mShowRequested=false mShowExplicitlyRequested=false mShowForced=false mInputShown=false
  mInFullscreenMode=false
  mCurUserActionNotificationSequenceNumber=9
  mSystemReady=true mInteractive=true
  mSettingsObserver=SettingsObserver{mUserId=0 mRegistered=true mLastEnabled=}
  mSwitchingController:
    mSwitchingAwareRotationList:
      rank=0 item=ImeSubtypeListItem{mImeName=Gboard mSubtypeName=null mSubtypeId=0 mIsSystemLocale=false mIsSystemLanguage=false}
    mSwitchingUnawareRotationList:
  mSettings:
    mCurrentUserId=0
    mCurrentProfileIds=[0]
    mCopyOnWrite=false
    mEnabledInputMethodsStrCache=com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME:com.google.android.googlequicksearchbox/com.google.android.voicesearch.ime.VoiceInputMethodService
  mStartInputHistory:
   StartInput #2539:
    time=2024-02-25 12:00:56.079 (timestamp=421998496) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@2a0a573 [com.motorola.launcher3] clientBindSeq=2540
    softInputMode=STATE_UNSPECIFIED|ADJUST_PAN|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2540:
    time=2024-02-25 12:00:59.141 (timestamp=422001559) reason=SESSION_CREATED_BY_IME restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@58271a2 [com.android.settings] clientBindSeq=2541
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0x7f0a01ef fieldName=null actionId=0 actionLabel=null
   StartInput #2541:
    time=2024-02-25 12:01:00.372 (timestamp=422002789) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@40f9d95 [com.android.settings] clientBindSeq=2542
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2542:
    time=2024-02-25 12:01:09.237 (timestamp=422011654) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@58271a2 [com.android.settings] clientBindSeq=2543
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE
    inputType=0x0 imeOptions=0x0 fieldId=0x7f0a01ef fieldName=null actionId=0 actionLabel=null
   StartInput #2543:
    time=2024-02-25 12:01:11.390 (timestamp=422013807) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@7282471 [com.android.settings] clientBindSeq=2544
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2544:
    time=2024-02-25 12:01:16.261 (timestamp=422018678) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@2a0a573 [com.motorola.launcher3] clientBindSeq=2545
    softInputMode=STATE_UNSPECIFIED|ADJUST_PAN|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2545:
    time=2024-02-25 12:01:17.431 (timestamp=422019849) reason=CHECK_FOCUS restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@2a0a573 [com.motorola.launcher3] clientBindSeq=2546
    softInputMode=STATE_UNSPECIFIED|ADJUST_PAN|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0x7f0a001d fieldName=null actionId=0 actionLabel=null
   StartInput #2546:
    time=2024-02-25 12:01:23.312 (timestamp=422025730) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@c70319e [com.motorola.motodisplay] clientBindSeq=2547
    softInputMode=STATE_ALWAYS_HIDDEN|ADJUST_PAN
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2547:
    time=2024-02-25 12:20:15.407 (timestamp=423157824) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@2a0a573 [com.motorola.launcher3] clientBindSeq=2548
    softInputMode=STATE_UNSPECIFIED|ADJUST_PAN
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2548:
    time=2024-02-25 12:20:20.370 (timestamp=423162788) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@f23377e [com.android.settings] clientBindSeq=2549
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0x7f0a01ef fieldName=null actionId=0 actionLabel=null
   StartInput #2549:
    time=2024-02-25 12:20:21.496 (timestamp=423163913) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@31bf760 [com.android.settings] clientBindSeq=2550
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE|IS_FORWARD_NAVIGATION
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2550:
    time=2024-02-25 12:20:30.951 (timestamp=423173369) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@ff7d67c [com.motorola.motodisplay] clientBindSeq=2551
    softInputMode=STATE_ALWAYS_HIDDEN|ADJUST_PAN
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2551:
    time=2024-02-25 12:34:50.541 (timestamp=424032959) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@19b961b [com.motorola.motodisplay] clientBindSeq=2552
    softInputMode=STATE_ALWAYS_HIDDEN|ADJUST_PAN
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2552:
    time=2024-02-25 13:15:17.188 (timestamp=426459605) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@31bf760 [com.android.settings] clientBindSeq=2553
    softInputMode=STATE_UNSPECIFIED|ADJUST_RESIZE
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null
   StartInput #2553:
    time=2024-02-25 13:15:19.499 (timestamp=426461916) reason=SESSION_CREATED_BY_IME restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@16c69c7 [com.android.settings.intelligence] clientBindSeq=2554
    softInputMode=STATE_UNSPECIFIED|ADJUST_PAN|IS_FORWARD_NAVIGATION
    inputType=0x90001 imeOptions=0x10000003 fieldId=0x10203df fieldName=null actionId=0 actionLabel=null
   StartInput #2554:
    time=2024-02-25 13:15:50.201 (timestamp=426492619) reason=WINDOW_FOCUS_GAIN restarting=false
    imeToken=android.os.Binder@a53256 [com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME]
    targetWin=android.os.BinderProxy@2f93b7b [com.motorola.motodisplay] clientBindSeq=2555
    softInputMode=STATE_ALWAYS_HIDDEN|ADJUST_PAN
    inputType=0x0 imeOptions=0x0 fieldId=0xffffffff fieldName=null actionId=0 actionLabel=null

Input method client state for android.view.inputmethod.InputMethodManager@fcc2c03:
  mService=com.android.internal.view.IInputMethodManager$Stub$Proxy@ca9d780
  mMainLooper=Looper (main, tid 2) {f9f1b9}
  mIInputContext=ControlledInputConnectionWrapper{connection=android.view.inputmethod.BaseInputConnection@2879fe finished=false mParentInputMethodManager.mActive=true}
  mActive=true mRestartOnNextWindowFocus=false mBindSequence=2555 mCurId=com.google.android.inputmethod.latin/com.android.inputmethod.latin.LatinIME
  mFullscreenMode=false
  mCurMethod=com.android.internal.view.IInputMethodSession$Stub$Proxy@edb855f
  mCurRootView=android.widget.FrameLayout{b91ee14 V.E...... ......ID 0,0-1080,1920}
  mServedView=null
  mNextServedView=null
  mServedConnecting=false
  mCurrentTextBoxAttribute: null
  mServedInputConnectionWrapper=null
  mCompletions=null
  mCursorRect=Rect(0, 0 - 0, 0)
  mCursorSelStart=0 mCursorSelEnd=0 mCursorCandStart=0 mCursorCandEnd=0
  mNextUserActionNotificationSequenceNumber=9 mLastSentUserActionNotificationSequenceNumber=-1

Input method service state for com.android.inputmethod.latin.LatinIME@1def8f6:
  mWindowCreated=true mWindowAdded=true
  mWindowVisible=false mWindowWasVisible=false mInShowWindow=false
  Configuration={1.0 ?mcc?mnc [en_US,hi_IN] ldltr sw360dp w360dp h616dp 480dpi nrml long port finger -keyb/v/h -nav/h winConfig={ mBounds=Rect(0, 0 - 0, 0) mAppBounds=Rect(0, 0 - 1080, 1920) mWindowingMode=fullscreen mActivityType=undefined} s.23 ?spn ?gid}
  mToken=android.os.BinderProxy@9b6cf2b
  mInputBinding=InputBinding{android.os.BinderProxy@c377f88 / uid 10064 / pid 29683}
  mInputConnection=InputConnectionWrapper{idHash=#7aced21 mMissingMethods=}
  mStartedInputConnection=null
  mInputStarted=true mInputViewStarted=false mCandidatesViewStarted=false
  mStartInputToken=android.os.BinderProxy@d673546
  mInputEditorInfo:
    inputType=0x0 imeOptions=0x0 privateImeOptions=null
    actionLabel=null actionId=0
    initialSelStart=-1 initialSelEnd=-1 initialCapsMode=0x0
    hintText=null label=null
    packageName=com.motorola.motodisplay fieldId=-1 fieldName=null
    extras=null
    hintLocales=null
    contentMimeTypes=null
  mShowInputRequested=false mLastShowInputRequested=false mShowInputFlags=0x0
  mCandidatesVisibility=4 mFullscreenApplied=true mIsFullscreen=false mExtractViewHidden=false
  mExtractedText: null
  mExtractedToken=0
  mIsInputViewShown=true mStatusIcon=0
Last computed insets:
  contentTopInsets=957 visibleTopInsets=957 touchableInsets=3 touchableRegion=SkRegion((0,957,1080,1704))
 mShouldClearInsetOfPreviousIme=false
 mSettingsObserver=SettingsObserver{mShowImeWithHardKeyboard=1}

Version Info :
VersionCode = 26761314
VersionName = 7.6.13.215505041-release-arm64-v8a

[ijm #1513307]


ExecutorUtils

[ddx #b890c34]

appStartCounter = 24
disable_gmscore = false
signature_check_gms_version = 0
signature_check_security_exception_crash =
package_signature_digest = F0FD6C5B410F25CB25C3B53346C8972FAE30F8EE7411DF910480AD6B2D60DB83

[dcj #f4a3a5d]


User Preferences :
enable_one_tap_to_search: "true"
pref_key_latest_unified_ime_activation_time: "1708338777940"
ACTIVE_IME.SOFT.en-US: "ime_english_united_states"
enable_battery_saver_theme: "false"
pref_key_access_points_showing_order_migrated: "true"
enable_one_tap_to_search_changed_by_user: "false"
PREF_LAST_ACTIVE_TAB: "com.google.android.apps.inputmethod.libs.search.IEmojiSearchExtension"
enable_secondary_symbols: "false"
latest_emoji_share_from_emoji_kb_timestamp: "1708331744146"
ACTIVE_IME.SOFT.und-Latn-x-number-password: "number_password"
enable_vibrate_on_keypress: "true"
pref_key_latest_ime_activation_time: "1708847119602"
RECENT_SYMBOL_DIGIT_KEYBOARD_ime_english_united_states: "symbol"
new_first_use_ping_sent: "true"
ACTIVE_IME.SOFT.und-Latn-x-phone-number: "phone_number"
app_last_started_version_name: "26761314"
enable_incognito_mode: "false"
pref_key_last_ping_time: "1708847119602"
previously_enabled_entries: "[hi-XT, en-US]"
enable_number_row: "false"
pref_key_contacts_suggestion_notice_posted: "true"
RECENT_SMILEY_KEYBOARD_ime_english_united_states: "smiley"
show_suggestions: "true"
text_committed_before_daily_ping: "false"
pref_key_show_sticker_badge_on_emoji_switch_key: "false"
show_launcher_icon: "false"
pref_key_num_art_extension_activations: "1"
new_rlz_ping_sent: "true"
pref_key_first_periodic_ping: "1567667522561"
RECENT_SYMBOL_DIGIT_KEYBOARD_password: "symbol"
smiley_keyboard_subcategory_selected: "2952790016"
current_input_method_entry: "en-US:qwerty"
ACTIVE_IME.SOFT.und-Latn-x-password: "password"
import_user_contacts: "false"
pref_key_should_reset_suggestions_pref: "false"
ACTIVE_IME.SOFT.und-Latn-x-number: "number"
latest_activation_time: "1708847119603"

[ilf #1515fd2]


[cvw #943f8a3]

Current Input Method:
(en-US , en-US, qwerty)
Enabled Input Method Entries:
(en-US , en-US, qwerty)
(hi , hi-XT, qwerty)
Use system language = true
Rotation List: [0, 1]

[cnt #7a6c60e]

AccessPointIds = [search, universal_media, sticker, gif_search, translate, theme_setting, textediting, clipboard, one_handed, quality_bug_report, settings, floating_keyboard]
EnabledAccessPointIds = [settings, theme_setting, gif_search, textediting, more_access_points, sticker, clipboard, translate, one_handed, search, floating_keyboard]
EnableOneTapSearch = true
EnableLaunchFeatureOnOneTapToSearch = true
HighlightedAccessPoint = NULL
OpenedAccessPointIds = []
OneTapFeatureProvider = ctk

[dyk #8c4b7a0]

All modules:
com.google.android.apps.inputmethod.libs.search.IUniversalMediaExtension: not instantiated.

JapaneseMozcExtension
  sIsDataPackageDefRegistered: false
  isJapaneseEnabled: false
com.google.android.apps.inputmethod.libs.translate.ITranslateUIExtension: not instantiated.

ConversationToQueryExtension
  isEnabled = true
  mActivated = false
  mNetworkConnected = false
  mLatestLocale = null
  mNoRealEngine = false
  mShouldAddCandidateEngine = true
  Client = not initialized
LSTM personalized training: false
LSTM federated training: false
LSTM prediction: false
LSTM cache client creation failed: false
LSTM current inference model: null
LSTM current personalization training model: null
LSTM latest prediction info:
LSTM last model metadata URL: null
LSTM active model: null
LSTM downloading service last run time: January 1, 1970, 5:30 AM
com.google.android.apps.inputmethod.libs.search.IStickerExtension: not instantiated.
com.google.android.apps.inputmethod.libs.search.IGifKeyboardExtension: not instantiated.

EmoticonExtension
 previousExtension =null
  currentKeyboardType = null
  currentKeyboard = null
FederatedC2Q triggering training: false
FederatedC2Q ranking training: false
FederatedC2Q inference: false
FederatedC2Q cache client creation failed: false
FederatedC2Q current inference model: null
FederatedC2Q training cache logger is null
com.google.android.apps.inputmethod.libs.contextual.ContextualPredictionExtension.dump()
com.google.android.apps.inputmethod.libs.swissarmyknife.IDecoderBugReportExtension: not instantiated.
com.google.android.apps.inputmethod.libs.search.IEmojiOrGifExtension: not instantiated.
com.google.android.apps.inputmethod.libs.search.INativeCardExtension: not instantiated.
Voice IME Extension: Voice Mic status = [{MicIconAvailable,}]

EmojiSearchExtension
  isActivated = false
  isShown = false
  mCurrentLocale = null
  getCurrentQuery = null
  previousExtension = null
  mCurrentKeyboardType = null
  mCurrentKeyboard = null
  mLastKnownEmojiSearchResultCandidates.size = null
 lastKnownQueries.size = null
should useDecoderAgnosticSearch? true
JNI instance exists? true
com.google.android.apps.inputmethod.libs.textediting.ITextEditingExtension: not instantiated.
com.google.android.apps.inputmethod.libs.contextstore.IConversationContextProcessor: not instantiated.
com.google.android.apps.inputmethod.libs.search.IBitmojiExtension: not instantiated.

Feature Card Notice extension
Activated: false
Feature cards enabled: true
Has feature cards to show: true
User tapped on notice: false
Max allowable times for displaying notice: 3
Actual times notice displayed: 5
All modules printed.

[InputContentProvider #bf77085]


[ccp #8819eda]

# Superpacks status report
- manifest keep count: 32
- db version: 15
- db path: /data/user/0/com.google.android.inputmethod.latin/databases/superpacks.db
- all known superpacks: [bundled_delight, emoji, bundled_emoji, conv2query_en, delight]
- network: No active network available
- power save mode: false

## FileManager status report
- root dir: /data/user/0/com.google.android.inputmethod.latin/files/superpacks
- gc behavior: chill
- gc min ttl: 172800000 ms
- last gc: never
- free space on device storage: 37 GB

## Referenced files
|namespace    |file name                       |ref count|
|        emoji|de96d6a43683ddb4f3bc1b59bcd73bb4|        1|
|bundled_emoji|442dd7424a2b73ebe817b5223ec48db9|        1|
|        emoji|75f112f3014bde732dc35bcb56c06bd2|        1|
|      delight|           main_en_us_20180802_1|        1|

## Namespace table
|namespace        |quota      |total reserved|total used|gc prio       |
|  bundled_delight|<unlimited>|          8 MB|      8 MB|{relative:500}|
|            emoji|<unlimited>|        527 kB|    527 kB|{relative:300}|
|        manifests| (detached)|          0 kB|    578 kB|  {absolute:0}|
|    bundled_emoji|<unlimited>|        224 kB|    224 kB|{relative:300}|
|delight_overrides|<unlimited>|          0 kB|      0 kB|{relative:300}|
|          layouts|<unlimited>|          0 kB|      0 kB|{relative:500}|
|          delight|<unlimited>|         17 MB|     17 MB|{relative:500}|

## File metadata table
|name                                    |gcp|state  |last          |source
                                            |superpack    |res   |
|              manifests:delight-20180903|  0|       |1/1/70 5:30 AM|                                         assets:///system/app/LatinImeGoogle/LatinImeGoogle.apk|    manifests|     0|
|      manifests:bundled_delight-20180903|  0|       |1/1/70 5:30 AM|                                         assets:///system/app/LatinImeGoogle/LatinImeGoogle.apk|    manifests|     0|
|   bundled_delight:main_en_us_20180802_2|  0|reserve|2/24/24 4:15 A|                                         assets:///system/app/LatinImeGoogle/LatinImeGoogle.apk|bundled_delig|501268|
|                                        |   |d      |M             |
                                            |ht           |8     |
|               manifests:bundled_emoji-3|  0|       |1/1/70 5:30 AM|assets:///data/user/0/com.google.android.inputmethod.latin/files/emoji_superpacks_manifest_bund|    manifests|     0|
|                                        |   |       |              |led.zip
                                            |             |      |
|bundled_emoji:442dd7424a2b73ebe817b5223e|  0|reserve|2/20/24 11:19 |        assets:///data/user/0/com.google.android.inputmethod.latin/files/emoji_search_en_us.zip|bundled_emoji|228714|
|c48db9                                  |   |d      |PM            |
                                            |             |      |
|           delight:main_en_us_20180802_1|  0|reserve|2/25/24 7:40 A|
                                            |      delight|779296|
|                                        |   |d      |M             |
                                            |             |4     |
|               manifests:bundled_emoji-6|  0|       |1/1/70 5:30 AM|assets:///data/user/0/com.google.android.inputmethod.latin/files/emoji_superpacks_manifest_bund|    manifests|     0|
|                                        |   |       |              |led.zip
                                            |             |      |
|            manifests:delight-2019100102|  0|       |1/1/70 5:30 AM|               https://www.gstatic.com/android/keyboard/dictionarypack/Saz-normal/metadata.json|    manifests|     0|
|                       manifests:emoji-6|  0|       |1/1/70 5:30 AM|https://www.gstatic.com/android/keyboard/modelpack/emoji/20180831175952/superpacks_manifest.zip|    manifests|     0|
|  emoji:de96d6a43683ddb4f3bc1b59bcd73bb4|  0|reserve|2/25/24 7:40 A|                        https://www.gstatic.com/android/keyboard/emoji/20180831175952/en-us.zip|        emoji|219002|
|                                        |   |d      |M             |
                                            |             |      |
|           delight:main_hi_xt_20171012_1|  0|reserve|2/25/24 7:40 A|https://www.gstatic.com/android/keyboard/dictionarypack/Saz-normal/04hl0gsqwzr_lpv-main_hi_xt_d|      delight|930401|
|                                        |   |d      |M             |3_20171012.dict
                                            |             |6     |
|  emoji:75f112f3014bde732dc35bcb56c06bd2|  0|reserve|2/25/24 7:40 A|                        https://www.gstatic.com/android/keyboard/emoji/20180831175952/hi-in.zip|        emoji|320064|
|                                        |   |d      |M             |
                                            |             |      |

## File status report
- root dir: /data/user/0/com.google.android.inputmethod.latin/files/superpacks

### delight
|file                 |last modified  |size   |
|main_en_us_20180802_1| 2/8/24 8:31 AM|7792964|
|main_hi_xt_20171012_1|2/22/24 4:15 PM|9304016|

### manifests
|file                    |last modified  |size  |
|        delight-20180903|9/5/19 12:38 PM|184823|
|                 emoji-6| 2/8/24 8:31 AM| 36048|
|bundled_delight-20180903| 2/8/24 8:29 AM|184823|
|      delight-2019100102| 2/8/24 8:31 AM|184823|
|         bundled_emoji-6| 2/8/24 8:29 AM|   304|
|         bundled_emoji-3| 2/8/24 8:29 AM|   304|

### bundled_emoji
|file                            |last modified |size  |
|442dd7424a2b73ebe817b5223ec48db9|2/8/24 8:29 AM|228714|

### emoji
|file                            |last modified  |size  |
|75f112f3014bde732dc35bcb56c06bd2|2/22/24 8:04 PM|320064|
|de96d6a43683ddb4f3bc1b59bcd73bb4| 2/8/24 8:31 AM|219002|

### bundled_delight
|file                 |last modified |size   |
|main_en_us_20180802_2|2/8/24 8:29 AM|7792964|

## Pending pack fetches
|id|
-There are no pending fetches-

## Namespace download priorities
|namespace        |priority      |
|  bundled_delight|{relative:500}|
|            emoji|{relative:300}|
|    bundled_emoji|{relative:300}|
|delight_overrides|{relative:300}|
|          layouts|{relative:500}|
|          delight|{relative:500}|

## Pipeline components
|type     |name                                         |
|  fetcher|SuperDelightResourceMetadataFetcher:178091136|
|  fetcher|      SuperDelightResourceLmFetcher:160025273|
|  fetcher|      SuperDelightLegacyFileFetcher:260431614|
|  fetcher|        BundledEmojiMetadataFetcher:207980127|
|  fetcher|             BundledEmojiDataFetcher:44390572|
|  fetcher|            ScheduledDownloadFetcher:63988996|
| unpacker|               SuperDelightUnpacker:117972227|
| unpacker|                         ZipUnpacker:41113973|
|validator|                   ChecksumValidator:98364682|

## Pending packs table
|parent id             |pending                     |
|conv2query_en-manifest|[manifests:conv2query_en-15]|

## ScheduledDownloadFetcher status report
- requires charging: false
- requires unmetered: true
- scheduling flags: bg

## Pending download queue:
|id                           |p  |urls                                    |start          |constr.|flags|path
                          |exp            |
|delight:main_en_us_20180802_1|500|[https://www.gstatic.com/android/keyboar| 2/8/24 8:29 AM|    m:b|   fg|delight/main_en_us_20180802_1.fst-decomp| 2/9/24 8:29 AM|
|                             |   |d/dictionarypack/Saz-normal/rm7hiq7n5yf-|               |       |     |ress.fetched                            |               |
|                             |   |-laimain_en_us_d3_20180802.dict]        |               |       |     |
                          |               |
|   manifests:conv2query_en-15|300|[https://www.gstatic.com/android/keyboar|2/16/24 1:41 AM|    W:b|   bg|  manifests/conv2query_en-15.zip.fetched|2/17/24 1:41 AM|
|                             |   |d/conv2query/S/en/2018102604/superpacks_|               |       |     |
                          |               |
|                             |   |manifest_en.zip]                        |               |       |     |
                          |               |

## Fetch progress status report
|id                           |progress                                                                        |cur/total bytes |%       |
|delight:main_en_us_20180802_1|-------------------------------------------------------------------------------o|7792964/7792964 |100.00  |
|   manifests:conv2query_en-15|?                                                                               |?/?             |?       |
## File Manifest store
- manifests namespace: manifests

## Manifest parsers

|namespace        |parser                                      |
|        <default>|                 JsonManifestParser:70467339|
|  bundled_delight|  SuperDelightBundledMetadataParser:76112360|
|delight_overrides|SuperDelightDownloadMetadataParser:197365761|
|          delight|SuperDelightDownloadMetadataParser:166383270|

## Manifest table
|name           |sync version|
|bundled_delight|    20180903|
|  bundled_emoji|           6|
|        delight|  2019100102|
|          emoji|           6|

## Selected packs table
|name                |selected                                                                        |
|     bundled_delight|                                         [bundled_delight:main_en_us_20180802_2]|
|       bundled_emoji|                                [bundled_emoji:442dd7424a2b73ebe817b5223ec48db9]|
|             delight|                  [delight:main_en_us_20180802_1, delight:main_hi_xt_20171012_1]|
|               emoji|[emoji:75f112f3014bde732dc35bcb56c06bd2, emoji:de96d6a43683ddb4f3bc1b59bcd73bb4]|

## Active downloads
|id|params|
-Empty-

## History tracer
- enabled: false

## FG Report:
- Failed : delight:main_hi_xt_20171012_1
- Successful : delight:main_hi_xt_20171012_1
- Failure count: 0
- Interval start: February 22, 4:14 PM

[PhenotypeExperimentConfiguration #e54c0e7]


Experiment Configuration :
flag: avatar_stickers_api_key, value: AIzaSyBeuEkY825uj8CHZSSO0NU6Kl67zjwHeyM
flag: avatar_stickers_metadata_version, value: 0
flag: c2q_asynchronously_triggered, value: false
flag: c2q_pill_popup_max_rate_limit_ms, value: 2592000000
flag: c2q_pill_popup_rate_limit_ms, value: 1000
flag: c2q_pill_ui_enabled, value: true
flag: c2q_superpacks_manifest_url_de, value: https://www.gstatic.com/android/keyboard/conv2query/S/de/2018102522/superpacks_manifest_de.zip
flag: c2q_superpacks_manifest_url_en, value: https://www.gstatic.com/android/keyboard/conv2query/S/en/2018102604/superpacks_manifest_en.zip
flag: c2q_superpacks_manifest_url_es, value: https://www.gstatic.com/android/keyboard/conv2query/S/es/2018102522/superpacks_manifest_es.zip
flag: c2q_superpacks_manifest_url_fr, value: https://www.gstatic.com/android/keyboard/conv2query/S/fr/2018102522/superpacks_manifest_fr.zip
flag: c2q_superpacks_manifest_url_it, value: https://www.gstatic.com/android/keyboard/conv2query/S/it/2018102522/superpacks_manifest_it.zip
flag: c2q_superpacks_manifest_url_ja, value:
flag: c2q_superpacks_manifest_url_ms, value: https://www.gstatic.com/android/keyboard/conv2query/S/ms/2018102522/superpacks_manifest_ms.zip
flag: c2q_superpacks_manifest_url_pt, value: https://www.gstatic.com/android/keyboard/conv2query/S/pt/2018102522/superpacks_manifest_pt.zip
flag: c2q_superpacks_manifest_url_ta, value: https://www.gstatic.com/android/keyboard/conv2query/S/ta/2018102522/superpacks_manifest_ta.zip
flag: c2q_superpacks_manifest_url_zh_cn, value:
flag: c2q_superpacks_manifest_url_zh_tw, value:
flag: c2q_superpacks_manifest_version_de, value: 4
flag: c2q_superpacks_manifest_version_en, value: 15
flag: c2q_superpacks_manifest_version_es, value: 4
flag: c2q_superpacks_manifest_version_fr, value: 4
flag: c2q_superpacks_manifest_version_it, value: 4
flag: c2q_superpacks_manifest_version_ja, value: 0
flag: c2q_superpacks_manifest_version_ms, value: 3
flag: c2q_superpacks_manifest_version_pt, value: 4
flag: c2q_superpacks_manifest_version_ta, value: 3
flag: c2q_superpacks_manifest_version_zh_cn, value: 0
flag: c2q_superpacks_manifest_version_zh_tw, value: 0
flag: clearcut_latency_logging_enabled, value: true
flag: contextual_annotator_superpacks_manifest_url, value: https://www.gstatic.com/android/keyboard/modelpack/contextual/contextualkeyboard-annotators-superpacks-manifest-20180320.json
flag: contextual_annotator_superpacks_version, value: 20180320
flag: contextual_appindexing_context_enabled, value: false
flag: contextual_appindexing_odi_enabled, value: false
flag: contextual_candidate_cache_ttl_sec, value: 14400
flag: contextual_candidate_max_age_for_ui_sec, value: 3600
flag: contextual_rate_us_interval_rate_limit_days, value: 30
flag: contextual_rate_us_max_allowable_attempts, value: 5
flag: contextual_rate_us_max_allowable_times, value: 1
flag: conv2query_extension_enabled, value: true
flag: conv2query_extension_locales, value: de,en,es,fr,it,ms,pt,ta
flag: conv2query_network_status_check_enabled, value: true
flag: conv2query_trending_queries_periodic_download_enabled, value: false
flag: country_cutout_switches, value: AE,ARE,784,AG,ATG,028,AL,ALB,008,AO,AGO,024,AR,ARG,032,AM,ARM,051,AT,AUT,040,AU,AUS,036,AW,ABW,533,AZ,AZE,031,BA,BIH,070,BD,BGD,050,BE,BEL,056,BF,BFA,854,BG,BGR,100,BH,BHR,048,BJ,BEN,204,BG,BGR,100,BO,BOL,068,BR,BRA,076,BS,BHS,044,BW,BWA,072,BY,BLR,112,BZ,BLZ,084,CA,CAN,124,CH,CHE,756,CL,CHL,152,CM,CMR,120,CN,CHN,156,CO,COL,170,CR,CRI,188,CU,CUB,192,CV,CPV,132,CY,CYP,196,CZ,CZE,203,DE,DEU,276,DO,DOM,214,DK,DNK,208,DZ,DZA,012,EC,ECU,218,EG,EGY,818,ES,ESP,724,EE,EST,233,FI,FIN,246,FJ,FJI,242,FR,FRA,250,GA,GAB,266,GB,GBR,826,GH,GHA,288,GR,GRC,300,GT,GTM,320,GW,GNB,624,HK,HKG,344,HN,HND,340,HR,HRV,191,HT,HTI,332,HU,HUN,348,ID,IDN,360,IE,IRL,372,IL,ISR,376,IN,IND,356,IR,IRN,364,IS,ISL,352,IT,ITA,380,JM,JAM,388,JO,JOR,400,JP,JPN,392,KE,KEN,404,KG,KGZ,417,KH,KHM,116,KR,KOR,410,KW,KWT,414,KZ,KAZ,398,LA,LAO,418,LB,LBN,422,LI,LIE,438,LK,LKA,144,LT,LTU,440,LU,LUX,442,LV,LVA,428,NL,NLD,528,MA,MAR,504,MD,MDA,498,MK,MKD,807,ML,MLI,466,MT,MLT,470,MU,MUS,480,MX,MEX,484,MY,MYS,458,MZ,MOZ,508,NA,NAM,516,NE,NER,562,NG,NGA,566,NI,NIC,558,NL,NLD,528,NO,NOR,578,NP,NPL,524,NZ,NZL,554,OM,OMN,512,PA,PAN,591,PE,PER,604,PG,PNG,598,PH,PHL,608,PK,PAK,586,PL,POL,616,PT,PRT,620,PY,PRY,600,QA,QAT,634,RO,ROU,642,RS,SRB,688,RU,RUS,643,RW,RWA,646,SA,SAU,682,SD,SDN,736,SE,SWE,752,SG,SGP,702,SI,SVN,705,SK,SVK,703,SN,SEN,686,SV,SLV,222,TG,TGO,768,TH,THA,764,TJ,TJK,762,TM,TKM,795,TN,TUN,788,TR,TUR,792,TT,TTO,780,TW,TWN,158,TZ,TZA,834,UA,UKR,804,UG,UGA,800,US,USA,840,UY,URY,858,UZ,UZB,860,VE,VEN,862,VN,VNM,704,YE,YEM,887,ZA,ZAF,710,ZM,ZMB,894,ZW,ZWE,716
flag: curated_gif_urls, value: https://media.tenor.com/images/eb707bb9c16cce278309b806437de097/tenor.gif,https://media.tenor.com/images/bb3c1585388c76140a56243ad58516e3/tenor.gif,https://media.tenor.com/images/8cf38543eebff103df6f1ec2730a5bde/tenor.gif,https://media.tenor.com/images/f2dcaaffe29ac111df8e333221ee231b/tenor.gif,https://media.tenor.com/images/a46fb163eedac8b73fd5b37522bb6454/tenor.gif,https://media.tenor.com/images/d7e9839f7816f2e7e00833d3878c8ae6/tenor.gif,https://media.tenor.com/images/890a0f650405054b82510c83b11a4be4/tenor.gif,https://media.tenor.com/images/a625312efec75d0487d2d9cbaa44a316/tenor.gif,https://media.tenor.com/images/323334b2a3d448b296bb813b25c12b96/tenor.gif,https://media.tenor.com/images/b23770782dd10e41d1efb2547ed4b106/tenor.gif,https://media.tenor.com/images/3579c2ea87dab612331fe6642cf72bc5/tenor.gif,https://media.tenor.com/images/053f4becdb91f78b78ef1f420686f971/tenor.gif,https://media.tenor.com/images/f5fafa9023d2ca0242e565cca321575a/tenor.gif,https://media.tenor.com/images/e3067445e4adae8bbf4eebf5c5e70582/tenor.gif,https://media.tenor.com/images/e1568d1a9cd6112b64757319c8130b67/tenor.gif,https://media.tenor.com/images/72d6a1ee3601e07ac0e0f6e446fb1070/tenor.gif,https://media.tenor.com/images/9f325db2402a93c645f802811a17e04d/tenor.gif,https://media.tenor.com/images/bd1569bb2d1a85780cfd2386d5333072/tenor.gif
flag: delete_legacy_delight_lms, value: false
flag: delight_latest_metadata_version, value: 2019100102
flag: delight_latest_overrides_metadata_version, value: -1
flag: delight_metadata_uri, value: https://www.gstatic.com/android/keyboard/dictionarypack/Saz-normal/metadata.json
flag: delight_overrides_metadata_uri, value:
flag: diacritic_cost_single_letter, value: 6.0
flag: downloadable_theme_base_url, value: https://www.gstatic.com/android/keyboard/theme/Regal/prod/
flag: dynamic_rate_limit_candidate_types, value: SEARCHABLE_TEXT,GIF_SEARCHABLE_TEXT,EXPRESSION_SEARCHABLE_TEXT,MAKE_A_GIF
flag: dynamic_rate_limit_interaction_strategy, value: RESET
flag: dynamic_rate_limit_scaling_strategy, value: EXPONENTIAL
flag: dynamic_rate_limit_store_impressions_in_preferences, value: true
flag: emoji_keyboard_prewarm_enabled, value: false
flag: emoji_superpacks_foreground_download_enabled, value: true
flag: emoji_superpacks_manifest_url, value: https://www.gstatic.com/android/keyboard/modelpack/emoji/20180831175952/superpacks_manifest.zip
flag: emoji_superpacks_manifest_version, value: 6
flag: emoji_superpacks_metered_download_enabled, value: true
flag: enable_autocorrection_adaptation_locales, value: ar,en-GB,en-IN
flag: enable_autospace_after_punctuation_setting, value: true
flag: enable_avatar_stickers, value: false
flag: enable_bitmoji_promo_banner, value: true
flag: enable_chevron_ui_v2, value: true
flag: enable_clear_input_and_select_upon_share_text, value: false
flag: enable_conv2expression_candidates, value: true
flag: enable_conv2makeagif_candidates, value: true
flag: enable_conv2query_for_chevron_ui, value: true
flag: enable_decoder_agnostic_emoji_search, value: true
flag: enable_decoder_agnostic_instant_search, value: false
flag: enable_dynamic_candidate_partitioning, value: false
flag: enable_emoji_avatar_stickers_new_features_card, value: true
flag: enable_emoji_search_suggestion_strip, value: true
flag: enable_en_us_morse, value: true
flag: enable_expressive_counters, value: true
flag: enable_fallback_art_corpus_to_universal_media, value: false
flag: enable_fc2q_log_shares_to_training_cache, value: true
flag: enable_feature_cards, value: true
flag: enable_fg_downloads_for_hmm, value: true
flag: enable_filter_image_search_results, value: true
flag: enable_floating_keyboard, value: true
flag: enable_full_backup_content, value: false
flag: enable_gif_access_point, value: true
flag: enable_handwriting, value: true
flag: enable_handwriting_zh_cn, value: true
flag: enable_handwriting_zh_hk, value: true
flag: enable_handwriting_zh_tw, value: true
flag: enable_instant_search, value: false
flag: enable_joystick_delete, value: false
flag: enable_ko, value: true
flag: enable_lang_id, value: false
flag: enable_launch_feature_on_one_tap_to_search, value: true
flag: enable_local_cards_v2, value: true
flag: enable_magic_g, value: true
flag: enable_magic_g_candidate_source_icon, value: true
flag: enable_magic_g_locales, value: de,en,es,fr,it,ms,pt,ta
flag: enable_magic_g_rate_limit, value: true
flag: enable_make_a_gif, value: true
flag: enable_make_a_gif_download_with_content_key, value: true
flag: enable_make_a_gif_loading_spinner, value: true
flag: enable_make_a_gif_megapacks, value: true
flag: enable_make_a_gif_reencode_with_drishti, value: true
flag: enable_make_a_gif_text_annotation, value: true
flag: enable_morse_hint, value: true
flag: enable_morse_switch_access, value: true
flag: enable_native_key_correction, value: true
flag: enable_neural_spatial_model, value: true
flag: enable_open_access_points_at_zero_state, value: false
flag: enable_pill_in_chevron_ui, value: false
flag: enable_rate_us_feature_card, value: true
flag: enable_rate_us_from_image_insert, value: true
flag: enable_rate_us_in_settings, value: true
flag: enable_rate_us_search_card, value: true
flag: enable_share_and_view_more_labels, value: true
flag: enable_share_intent_fallback, value: true
flag: enable_show_disabled_mic, value: true
flag: enable_suggest_recent_clicked_c2q_candidate, value: true
flag: enable_tooltip_for_glow_g_candidate, value: true
flag: enable_unified_search_history, value: true
flag: enable_universal_media, value: true
flag: enable_universal_media_more_emoji_btn, value: false
flag: enable_user_language_profiles_logging, value: true
flag: enable_zero_state_candidates, value: true
flag: enable_zh_cn, value: true
flag: enable_zh_hk, value: true
flag: enable_zh_tw, value: true
flag: enabled_sticker_search_locales, value: ar,de,en,es,fr,hi-Latn,id,it,ja,ko,nl,pl,pt,ru,th,tr,zh-CN,zh-HK,zh-TW
flag: expression_disabled_when_emoji_kb_disallowed, value: true
flag: expressive_stickers_api_key, value: AIzaSyBPSAFlv3zpgK1jCJhlmNwl9NoAuhL-AKc
flag: expressive_stickers_grpc_hostname, value: sticker-pa.googleapis.com
flag: expressive_stickers_market_config, value: [34, 8, 112, 97, 99, 107, 115, 47, 50, 52, 34, 8, 112, 97, 99, 107, 115, 47, 50, 53, 34, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 50, 34, 8, 112, 97, 99, 107, 115, 47, 50, 51, 34, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 52, 50, 57, 54, 57, 57, 50, 8, 112, 97, 99, 107, 115, 47, 50, 52, 50, 8, 112, 97, 99, 107, 115, 47, 50, 53, 50, 8, 112, 97, 99, 107, 115, 47, 50, 57, 50, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 50, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 50, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 54, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 54, 48, 50, 48, 50, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 51, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 51, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 51, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 51, 48, 54, 50, 8, 112, 97, 99, 107, 115, 47, 50, 51, 50, 12, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 52, 50, 8, 112, 97, 99, 107, 115, 47, 50, 55, 50, 8, 112, 97, 99, 107, 115, 47, 51, 48, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 50, 50, 8, 112, 97, 99, 107, 115, 47, 50, 54, 50, 8, 112, 97, 99, 107, 115, 47, 51, 49, 50, 8, 112, 97, 99, 107, 115, 47, 50, 56, 50, 12, 112, 97, 99, 107, 115, 47, 55, 56, 57, 48, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 57, 48, 50, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 55, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 55, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 57, 48, 51, 48, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 50, 48, 48, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 56, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 49, 48, 48, 48, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 49, 48, 48, 48, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 57, 57, 57, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 55, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 54, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 56, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 57, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 56, 48, 55, 50, 12, 112, 97, 99, 107, 115, 47, 55, 56, 57, 48, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 55, 56, 57, 48, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 55, 56, 57, 48, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 55, 56, 57, 48, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 53, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 53, 48, 49, 50, 7, 112, 97, 99, 107, 115, 47, 56, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 52, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 54, 54, 54, 50, 7, 112, 97, 99, 107, 115, 47, 54, 50, 7, 112, 97, 99, 107, 115, 47, 49, 50, 7, 112, 97, 99, 107, 115, 47, 50, 50, 7, 112, 97, 99, 107, 115, 47, 52, 50, 8, 112, 97, 99, 107, 115, 47, 49, 51, 50, 8, 112, 97, 99, 107, 115, 47, 49, 52, 50, 8, 112, 97, 99, 107, 115, 47, 49, 53, 50, 8, 112, 97, 99, 107, 115, 47, 49, 54, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 56, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 54, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 57, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 50, 48, 49, 48, 50, 8, 112, 97, 99, 107, 115, 47, 49, 56, 50, 8, 112, 97, 99, 107, 115, 47, 49, 57, 50, 8, 112, 97, 99, 107, 115, 47, 50, 48, 50, 8, 112, 97, 99, 107, 115, 47, 50, 49, 50, 12, 112, 97, 99, 107, 115, 47, 53, 52, 55, 54, 49, 56, 50, 12, 112, 97, 99, 107, 115, 47, 54, 48, 49, 57, 52, 51, 50, 12, 112, 97, 99, 107, 115, 47, 54, 49, 51, 52, 54, 56, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 57, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 54, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 49, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 50, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 57, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 51, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 53, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 49, 57, 55, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 51, 48, 55, 50, 8, 112, 97, 99, 107, 115, 47, 49, 50, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 52, 48, 49, 50, 8, 112, 97, 99, 107, 115, 47, 49, 55, 50, 12, 112, 97, 99, 107, 115, 47, 56, 56, 48, 50, 48, 50, 50, 7, 112, 97, 99, 107, 115, 47, 53, 50, 7, 112, 97, 99, 107, 115, 47, 51, 50, 7, 112, 97, 99, 107, 115, 47, 57, 50, 12, 112, 97, 99, 107, 115, 47, 56, 48, 54, 50, 53, 56, 50, 8, 112, 97, 99, 107, 115, 47, 50, 50, 50, 8, 112, 97, 99, 107, 115, 47, 49, 48, 50, 7, 112, 97, 99, 107, 115, 47, 55, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 55, 57, 57, 49, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 51, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 51, 48, 50, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 51, 48, 51, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 57, 48, 53, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 57, 48, 54, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 57, 48, 55, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 52, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 52, 48, 50, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 52, 48, 51, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 49, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 49, 48, 50, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 49, 48, 51, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 56, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 56, 50, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 56, 51, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 56, 52, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 56, 53, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 57, 53, 48, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 55, 56, 57, 48, 48, 54, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 55, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 55, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 55, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 55, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 55, 55, 55, 55, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 54, 53, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 55, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 53, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 54, 50, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 53, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 49, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 54, 50, 12, 112, 97, 99, 107, 115, 47, 51, 54, 56, 52, 55, 53, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 52, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 57, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 56, 50, 12, 112, 97, 99, 107, 115, 47, 51, 54, 56, 52, 55, 51, 50, 12, 112, 97, 99, 107, 115, 47, 51, 54, 56, 52, 55, 52, 50, 12, 112, 97, 99, 107, 115, 47, 51, 54, 56, 52, 55, 49, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 53, 51, 50, 12, 112, 97, 99, 107, 115, 47, 55, 51, 48, 50, 54, 49, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 54, 57, 57, 51, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 54, 57, 57, 53, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 55, 57, 57, 48, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 53, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 54, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 49, 48, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 56, 48, 48, 52, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 56, 48, 48, 50, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 54, 57, 57, 50, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 57, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 56, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 56, 48, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 55, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 54, 57, 57, 48, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 56, 48, 48, 51, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 48, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 54, 57, 57, 49, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 54, 57, 57, 52, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 49, 48, 49, 50, 12, 112, 97, 99, 107, 115, 47, 57, 52, 57, 48, 48, 50, 58, 19, 112, 97, 99, 107, 115, 47, 50, 55, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 51, 58, 24, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 51, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 49, 48, 58, 23, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 49, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 49, 58, 20, 112, 97, 99, 107, 115, 47, 51, 48, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 50, 49, 58, 20, 112, 97, 99, 107, 115, 47, 50, 56, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 49, 55, 58, 20, 112, 97, 99, 107, 115, 47, 50, 54, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 49, 55, 58, 24, 112, 97, 99, 107, 115, 47, 50, 48, 48, 48, 48, 52, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 50, 48, 58, 19, 112, 97, 99, 107, 115, 47, 50, 51, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 57, 58, 19, 112, 97, 99, 107, 115, 47, 50, 55, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 49, 58, 23, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 50, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 54, 58, 24, 112, 97, 99, 107, 115, 47, 54, 48, 48, 49, 48, 51, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 49, 54, 58, 20, 112, 97, 99, 107, 115, 47, 50, 51, 47, 115, 116, 105, 99, 107, 101, 114, 115, 47, 50, 51]
flag: expressive_stickers_metadata_version, value: 1000027
flag: federatedc2q_conv2gif_candidates_enabled, value: true
flag: federatedc2q_conv2query_candidates_enabled, value: true
flag: federatedc2q_corpus_tag, value: glowg/saz
flag: federatedc2q_enable_custom_thresholds_trending_queries, value: false
flag: federatedc2q_extra_candidates_enabled, value: false
flag: federatedc2q_inference_enabled, value: false
flag: federatedc2q_inference_triggering_threshold, value: -10.0
flag: federatedc2q_inference_triggering_threshold_trending_queries, value: 0.0
flag: federatedc2q_models_metadata_uri, value: https://www.gstatic.com/android/keyboard/modelpack/federatedc2q/superpacks_manifest.json
flag: federatedc2q_models_metadata_version, value: 1
flag: federatedc2q_prediction_model_variant, value:
flag: federatedc2q_ranking_training_enabled, value: false
flag: federatedc2q_ranking_training_population, value:
flag: federatedc2q_training_enabled, value: false
flag: federatedc2q_training_population, value: conv2query/production
flag: fst_model_params_overrides, value: []
flag: google_keyboard_hotwater_faucet_interval, value: 0
flag: grpc_server_host, value: gboard-pa.googleapis.com
flag: handwriting_superpacks_manifest_url, value: https://dl.google.com/handwriting/models/handwriting.superpack_manifest.20180709.json
flag: handwriting_superpacks_manifest_version, value: 3
flag: hmm_superpacks_manifest_url, value: https://www.gstatic.com/android/keyboard/hmmpack/2019010403/metadata_2019010403.json
flag: hmm_superpacks_manifest_version, value: 2019010403
flag: ignore_word_separators_for_prediction_context, value: true
flag: key_correction_ignore_fraction, value: 0.8
flag: key_correction_language_weight, value: 1.0
flag: key_correction_max_speed_weight, value: 2.0
flag: key_correction_speed_limit_millis, value: 100
flag: key_gaussian_variance_multiplier, value: 1.0
flag: literal_start_penalty_any_autocor_relative_step, value: 0.001
flag: literal_start_penalty_relative_max, value: 1.02
flag: literal_start_penalty_relative_min, value: 0.5
flag: literal_start_penalty_revert_relative_step, value: 0.01
flag: log_next_word_prediction_match, value: true
flag: lstm_federated_training_period_seconds, value: 3600
flag: lstm_hide_non_contextual_predictions, value: false
flag: lstm_hide_predictions, value: true
flag: lstm_models_metadata_version, value: 9
flag: lstm_superpacks_enabled, value: true
flag: lstm_training_period_seconds, value: 3600
flag: lstm_training_requires_idle, value: true
flag: make_a_gif_framerate, value: 15
flag: make_a_gif_max_dimension, value: 480
flag: make_a_gif_superpacks_manifest_url, value: https://www.gstatic.com/android/keyboard/modelpack/makeagif/201809272121/superpacks_manifest.json
flag: make_a_gif_superpacks_manifest_version, value: 13
flag: multiword_candidate_language_tags, value: en-US
flag: multiword_gesture_cost, value: 5.0
flag: multiword_prediction_cost, value: 1.4
flag: multiword_threshold_score, value: 3.0
flag: prediction_branching_limit, value: 1
flag: primes_dir_stats_logging_enabled, value: false
flag: primes_latency_logging_enabled, value: false
flag: primes_memory_logging_enabled, value: false
flag: prune_user_history_by_timestamp, value: true
flag: require_https_urls_in_search_response, value: false
flag: save_non_prime_keyboard_type, value: true
flag: stickers_new_release_badges_show_after_nth_open, value: 0
flag: superpacks_enable_history_trace, value: false
flag: supports_battery_saver_theme, value: true
flag: tenor_safe_search_level, value: mild
flag: translate_source_language_list, value: af,am,ar,az,be,bg,bn,bs,ca,ceb,co,cs,cy,da,de,el,en,eo,es,et,eu,fa,fi,fil,fr,fy,ga,gd,gl,gu,ha,haw,hi,hmn,hr,ht,hu,hy,id,ig,is,it,iw,ja,jw,ka,kk,km,kn,ko,ku,ky,la,lb,lo,lt,lv,mg,mi,mk,ml,mn,mr,ms,mt,my,ne,nl,no,ny,pa,pl,ps,pt,ro,ru,sd,si,sk,sl,sm,sn,so,sq,sr,st,su,sv,sw,ta,te,tg,th,tr,uk,ur,uz,vi,xh,yi,yo,zh,zu
flag: translate_target_language_list, value: af,am,ar,az,be,bg,bn,bs,ca,ceb,co,cs,cy,da,de,el,en,eo,es,et,eu,fa,fi,fil,fr,fy,ga,gd,gl,gu,ha,haw,hi,hmn,hr,ht,hu,hy,id,ig,is,it,iw,ja,jw,ka,kk,km,kn,ko,ku,ky,la,lb,lo,lt,lv,mg,mi,mk,ml,mn,mr,ms,mt,my,ne,nl,no,ny,pa,pl,ps,pt,ro,ru,sd,si,sk,sl,sm,sn,so,sq,sr,st,su,sv,sw,ta,te,tg,th,tr,uk,ur,uz,vi,xh,yi,yo,zh-CN,zh-TW,zu
flag: unified_ime_timeout, value: 10000
flag: unsupported_apps_for_share_intent, value: com.google.android.gm,com.google.android.gm.lite,com.android.systemui,com.facebook.katana,com.facebook.lite,com.instagram.android
flag: urgent_signals, value: [8, -44, -16, -83, -123, 1, 18, 2, 8, 1, 18, -19, 41, 8, 1, 18, 41, 8, 5, 18, 5, 97, 114, 95, 65, 69, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 66, 72, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 68, 74, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 68, 90, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 69, 71, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 76, 89, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 77, 65, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 79, 77, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 83, 65, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 83, 68, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 41, 8, 5, 18, 5, 97, 114, 95, 84, 78, 26, 30, 10, 13, -40, -77, -39, -125, -40, -77, 32, -39, -127, -39, -124, -39, -123, 10, 13, -39, -127, -39, -124, -39, -123, 32, -40, -77, -39, -125, -40, -77, 18, 60, 8, 5, 18, 5, 98, 110, 95, 66, 68, 26, 49, 10, 21, -32, -90, -90, -32, -89, -127, -32, -90, -89, -32, -90, -105, -32, -89, -127, -32, -90, -78, -32, -89, -117, 10, 24, -32, -90, -72, -32, -89, -115, -32, -90, -92, -32, -90, -88, -32, -90, -90, -32, -89, -127, -32, -90, -97, -32, -89, -117, 18, 60, 8, 5, 18, 5, 98, 110, 95, 73, 78, 26, 49, 10, 21, -32, -90, -90, -32, -89, -127, -32, -90, -89, -32, -90, -105, -32, -89, -127, -32, -90, -78, -32, -89, -117, 10, 24, -32, -90, -72, -32, -89, -115, -32, -90, -92, -32, -90, -88, -32, -90, -90, -32, -89, -127, -32, -90, -97, -32, -89, -117, 18, 67, 8, 5, 18, 2, 99, 115, 26, 59, 10, 17, 112, 111, 108, 121, 107, -61, -95, 110, -61, -83, 32, 115, 101, 109, 101, 110, 101, 10, 17, 112, 111, 108, 121, 107, -61, -95, 110, -61, -83, 32, 115, 112, 101, 114, 109, 97, 10, 19, 112, 111, 108, 121, 107, -61, -95, 110, -61, -83, 32, 115, 112, 101, 114, 109, 97, 116, 117, 18, 37, 8, 5, 18, 2, 100, 97, 26, 29, 10, 7, 107, 110, 101, 112, 112, 101, 116, 10, 13, 109, -61, -90, 114, 107, 101, 108, 105, 103, 32, 115, 101, 120, 10, 3, 112, 105, 107, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 65, 85, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 67, 65, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 71, 66, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -83, 3, 8, 5, 18, 5, 101, 110, 95, 73, 78, 26, -95, 3, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 5, 99, 104, 111, 111, 116, 10, 4, 99, 104, 117, 116, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 5, 103, 97, 97, 110, 100, 10, 4, 103, 97, 110, 100, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 10, 16, 115, 117, 112, 112, 111, 114, 116, 32, 110, 97, 114, 101, 110, 100, 114, 97, 10, 19, 115, 117, 112, 112, 111, 114, 116, 32, 115, 117, 98, 114, 97, 109, 97, 110, 105, 97, 110, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 75, 69, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 78, 71, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 80, 72, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -106, 3, 8, 5, 18, 5, 101, 110, 95, 85, 83, 26, -118, 3, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 24, 103, 108, 111, 98, 97, 108, 32, 119, 97, 114, 109, 105, 110, 103, 32, 105, 115, 32, 97, 32, 104, 111, 97, 120, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 104, 101, 39, 115, 32, 97, 32, 118, 105, 114, 103, 105, 110, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, -20, 2, 8, 5, 18, 5, 101, 110, 95, 90, 65, 26, -32, 2, 10, 12, 98, 105, 115, 101, 120, 117, 97, 108, 32, 109, 101, 110, 10, 18, 98, 105, 115, 101, 120, 117, 97, 108, 32, 116, 104, 114, 101, 101, 115, 111, 109, 101, 10, 10, 98, 108, 97, 99, 107, 32, 100, 105, 99, 107, 10, 4, 99, 111, 99, 107, 10, 11, 99, 117, 110, 110, 105, 108, 105, 110, 103, 117, 115, 10, 7, 102, 101, 108, 108, 97, 116, 101, 10, 8, 102, 101, 108, 108, 97, 116, 101, 100, 10, 8, 102, 101, 108, 108, 97, 116, 105, 111, 10, 13, 103, 111, 108, 100, 101, 110, 32, 115, 104, 111, 119, 101, 114, 10, 15, 105, 110, 116, 111, 32, 98, 108, 97, 99, 107, 32, 103, 117, 121, 115, 10, 9, 108, 97, 112, 32, 100, 97, 110, 99, 101, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 98, 97, 98, 101, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 103, 105, 114, 108, 115, 10, 13, 108, 101, 115, 98, 105, 97, 110, 32, 116, 101, 101, 110, 115, 10, 5, 110, 105, 103, 103, 97, 10, 6, 110, 105, 103, 103, 101, 114, 10, 4, 111, 114, 97, 108, 10, 13, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 10, 15, 114, 97, 100, 105, 99, 97, 108, 32, 105, 115, 108, 97, 109, 105, 99, 10, 6, 114, 101, 116, 97, 114, 100, 10, 8, 114, 101, 116, 97, 114, 100, 101, 100, 10, 7, 114, 101, 116, 97, 114, 100, 115, 10, 14, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 102, 97, 99, 101, 10, 13, 115, 105, 116, 32, 111, 110, 32, 109, 121, 32, 108, 97, 112, 10, 16, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 102, 97, 99, 101, 10, 15, 115, 105, 116, 32, 111, 110, 32, 121, 111, 117, 114, 32, 108, 97, 112, 10, 10, 115, 116, 105, 102, 102, 32, 99, 111, 99, 107, 10, 10, 115, 116, 105, 102, 102, 32, 100, 105, 99, 107, 18, 66, 8, 5, 18, 6, 101, 115, 95, 52, 49, 57, 26, 54, 10, 16, 99, 117, 114, 97, 115, 32, 97, 98, 117, 115, 97, 100, 111, 114, 101, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, 101, 114, 97, 115, 116, 97, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, -61, -77, 102, 105, 108, 111, 115, 18, 65, 8, 5, 18, 5, 101, 115, 95, 65, 82, 26, 54, 10, 16, 99, 117, 114, 97, 115, 32, 97, 98, 117, 115, 97, 100, 111, 114, 101, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, 101, 114, 97, 115, 116, 97, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, -61, -77, 102, 105, 108, 111, 115, 18, 65, 8, 5, 18, 5, 101, 115, 95, 69, 83, 26, 54, 10, 16, 99, 117, 114, 97, 115, 32, 97, 98, 117, 115, 97, 100, 111, 114, 101, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, 101, 114, 97, 115, 116, 97, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, -61, -77, 102, 105, 108, 111, 115, 18, 65, 8, 5, 18, 5, 101, 115, 95, 77, 88, 26, 54, 10, 16, 99, 117, 114, 97, 115, 32, 97, 98, 117, 115, 97, 100, 111, 114, 101, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, 101, 114, 97, 115, 116, 97, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, -61, -77, 102, 105, 108, 111, 115, 18, 65, 8, 5, 18, 5, 101, 115, 95, 85, 83, 26, 54, 10, 16, 99, 117, 114, 97, 115, 32, 97, 98, 117, 115, 97, 100, 111, 114, 101, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, 101, 114, 97, 115, 116, 97, 115, 10, 16, 99, 117, 114, 97, 115, 32, 112, 101, 100, -61, -77, 102, 105, 108, 111, 115, 18, 28, 8, 5, 18, 5, 102, 114, 95, 66, 69, 26, 17, 10, 15, 97, 118, 97, 108, 101, 32, 100, 117, 32, 115, 112, 101, 114, 109, 101, 18, 28, 8, 5, 18, 5, 102, 114, 95, 67, 65, 26, 17, 10, 15, 97, 118, 97, 108, 101, 32, 100, 117, 32, 115, 112, 101, 114, 109, 101, 18, 28, 8, 5, 18, 5, 102, 114, 95, 67, 72, 26, 17, 10, 15, 97, 118, 97, 108, 101, 32, 100, 117, 32, 115, 112, 101, 114, 109, 101, 18, 28, 8, 5, 18, 5, 102, 114, 95, 70, 82, 26, 17, 10, 15, 97, 118, 97, 108, 101, 32, 100, 117, 32, 115, 112, 101, 114, 109, 101, 18, 21, 8, 5, 18, 2, 104, 114, 26, 13, 10, 11, 117, 98, 105, 106, 32, 112, 101, 100, 101, 114, 97, 18, 30, 8, 5, 18, 2, 105, 110, 26, 22, 10, 10, 102, 111, 116, 111, 32, 98, 117, 103, 105, 108, 10, 8, 102, 111, 116, 111, 32, 104, 111, 116, 18, 29, 8, 5, 18, 5, 105, 116, 95, 67, 72, 26, 18, 10, 16, 105, 110, 103, 111, 105, 111, 32, 100, 105, 32, 115, 112, 101, 114, 109, 97, 18, 29, 8, 5, 18, 5, 105, 116, 95, 73, 84, 26, 18, 10, 16, 105, 110, 103, 111, 105, 111, 32, 100, 105, 32, 115, 112, 101, 114, 109, 97, 18, 29, 8, 5, 18, 2, 105, 119, 26, 21, 10, 19, -41, -92, -41, -96, -41, -107, -41, -103, -41, -108, 32, -41, -100, -41, -95, -41, -89, -41, -95, 18, 52, 8, 5, 18, 2, 112, 108, 26, 44, 10, 5, 107, 117, 114, 119, 121, 10, 6, 109, 117, 114, 122, 121, 110, 10, 9, 109, 117, 114, 122, 121, 110, -61, -77, 119, 10, 4, 110, 97, 103, 111, 10, 5, 112, 111, 114, 110, 111, 10, 3, 115, 101, 120, 18, 79, 8, 5, 18, 5, 112, 116, 95, 66, 82, 26, 68, 10, 9, 97, 115, 115, 97, 110, 104, 97, 100, 97, 10, 5, 100, 97, 110, 100, 111, 10, 18, 110, 101, 103, 114, 105, 110, 104, 97, 32, 100, 101, 108, 105, 99, 105, 111, 115, 97, 10, 11, 110, 101, 103, 117, 105, 110, 104, 97, 32, 100, 97, 10, 7, 110, 111, 118, 105, 110, 104, 97, 10, 6, 115, 97, 102, 97, 100, 97, 18, 19, 8, 5, 18, 5, 114, 111, 95, 82, 79, 26, 8, 10, 6, 102, 117, 116, 117, 116, 101, 18, 89, 8, 5, 18, 5, 114, 117, 95, 66, 89, 26, 78, 10, 47, -48, -93, -48, -70, -47, -128, -48, -80, -48, -72, -48, -67, -47, -127, -48, -70, -48, -72, -47, -123, 32, -48, -67, -48, -80, -47, -122, -48, -72, -48, -66, -48, -67, -48, -80, -48, -69, -48, -72, -47, -127, -47, -126, -48, -66, -48, -78, 10, 27, -48, -77, -48, -69, -48, -66, -47, -126, -48, -80, -47, -126, -47, -116, 32, -47, -127, -48, -65, -48, -75, -47, -128, -48, -68, -47, -125, 18, 89, 8, 5, 18, 5, 114, 117, 95, 75, 71, 26, 78, 10, 47, -48, -93, -48, -70, -47, -128, -48, -80, -48, -72, -48, -67, -47, -127, -48, -70, -48, -72, -47, -123, 32, -48, -67, -48, -80, -47, -122, -48, -72, -48, -66, -48, -67, -48, -80, -48, -69, -48, -72, -47, -127, -47, -126, -48, -66, -48, -78, 10, 27, -48, -77, -48, -69, -48, -66, -47, -126, -48, -80, -47, -126, -47, -116, 32, -47, -127, -48, -65, -48, -75, -47, -128, -48, -68, -47, -125, 18, 89, 8, 5, 18, 5, 114, 117, 95, 82, 85, 26, 78, 10, 47, -48, -93, -48, -70, -47, -128, -48, -80, -48, -72, -48, -67, -47, -127, -48, -70, -48, -72, -47, -123, 32, -48, -67, -48, -80, -47, -122, -48, -72, -48, -66, -48, -67, -48, -80, -48, -69, -48, -72, -47, -127, -47, -126, -48, -66, -48, -78, 10, 27, -48, -77, -48, -69, -48, -66, -47, -126, -48, -80, -47, -126, -47, -116, 32, -47, -127, -48, -65, -48, -75, -47, -128, -48, -68, -47, -125, 18, 54, 8, 5, 18, 5, 116, 97, 95, 73, 78, 26, 43, 10, 18, -32, -82, -102, -32, -81, -127, -32, -82, -93, -32, -81, -115, -32, -82, -93, -32, -81, -128, 10, 21, -32, -82, -102, -32, -81, -127, -32, -82, -87, -32, -81, -115, -32, -82, -87, -32, -82, -65, -32, -82, -81, 18, 54, 8, 5, 18, 5, 116, 97, 95, 76, 75, 26, 43, 10, 18, -32, -82, -102, -32, -81, -127, -32, -82, -93, -32, -81, -115, -32, -82, -93, -32, -81, -128, 10, 21, -32, -82, -102, -32, -81, -127, -32, -82, -87, -32, -81, -115, -32, -82, -87, -32, -82, -65, -32, -82, -81, 18, 54, 8, 5, 18, 5, 116, 97, 95, 83, 71, 26, 43, 10, 18, -32, -82, -102, -32, -81, -127, -32, -82, -93, -32, -81, -115, -32, -82, -93, -32, -81, -128, 10, 21, -32, -82, -102, -32, -81, -127, -32, -82, -87, -32, -81, -115, -32, -82, -87, -32, -82, -65, -32, -82, -81, 18, 37, 8, 5, 18, 2, 117, 107, 26, 29, 10, 27, -48, -70, -48, -66, -48, -78, -47, -126, -48, -80, -47, -126, -48, -72, 32, -47, -127, -48, -65, -48, -75, -47, -128, -48, -68, -47, -125, 18, 6, 8, 0, 18, 2, 8, 2]
flag: use_emoji_for_expression_candidate_source_icon, value: false
flag: user_history_retention_days, value: 63
Last experiment update: February 25, 7:40 AM
Update available: false
Share this experiment configuration: https://com.google.android.apps.inputmethod.latin?configMap=rO0ABXNyABFqYXZhLnV0aWwuSGFzaE1hcAUH2sHDFmDRAwACRgAKbG9hZEZhY3RvckkACXRocmVz
aG9sZHhwP0AAAAAAAYB3CAAAAgAAAADHdAAZZW5hYmxlX3BpbGxfaW5fY2hldnJvbl91aXQAJmVu
YWJsZV9waWxsX2luX2NoZXZyb25fdWksIGZhbHNlLCAyLCAwdAAaZnN0X21vZGVsX3BhcmFtc19v
dmVycmlkZXN0ACRmc3RfbW9kZWxfcGFyYW1zX292ZXJyaWRlcywgJycsIDUsIDB0AB1lbmFibGVf
dW5pZmllZF9zZWFyY2hfaGlzdG9yeXQAKWVuYWJsZV91bmlmaWVkX3NlYXJjaF9oaXN0b3J5LCB0
cnVlLCAyLCAwdAAsZXhwcmVzc2lvbl9kaXNhYmxlZF93aGVuX2Vtb2ppX2tiX2Rpc2FsbG93ZWR0
ADhleHByZXNzaW9uX2Rpc2FibGVkX3doZW5fZW1vamlfa2JfZGlzYWxsb3dlZCwgdHJ1ZSwgMiwg
MHQAFmVuYWJsZV9hdmF0YXJfc3RpY2tlcnN0ACNlbmFibGVfYXZhdGFyX3N0aWNrZXJzLCBmYWxz
ZSwgMiwgMHQAIWVtb2ppX3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbnQAKmVtb2ppX3N1cGVy
cGFja3NfbWFuaWZlc3RfdmVyc2lvbiwgNiwgMSwgMHQANWNvbnYycXVlcnlfdHJlbmRpbmdfcXVl
cmllc19wZXJpb2RpY19kb3dubG9hZF9lbmFibGVkdABCY29udjJxdWVyeV90cmVuZGluZ19xdWVy
aWVzX3BlcmlvZGljX2Rvd25sb2FkX2VuYWJsZWQsIGZhbHNlLCAyLCAwdAAgY2xlYXJjdXRfbGF0
ZW5jeV9sb2dnaW5nX2VuYWJsZWR0ACxjbGVhcmN1dF9sYXRlbmN5X2xvZ2dpbmdfZW5hYmxlZCwg
dHJ1ZSwgMiwgMHQAImMycV9zdXBlcnBhY2tzX21hbmlmZXN0X3ZlcnNpb25fbXN0ACtjMnFfc3Vw
ZXJwYWNrc19tYW5pZmVzdF92ZXJzaW9uX21zLCAzLCAxLCAwdAAeZmVkZXJhdGVkYzJxX2luZmVy
ZW5jZV9lbmFibGVkdAArZmVkZXJhdGVkYzJxX2luZmVyZW5jZV9lbmFibGVkLCBmYWxzZSwgMiwg
MHQAJmNvbnRleHR1YWxfcmF0ZV91c19tYXhfYWxsb3dhYmxlX3RpbWVzdAAvY29udGV4dHVhbF9y
YXRlX3VzX21heF9hbGxvd2FibGVfdGltZXMsIDEsIDEsIDB0AB5jMnFfc3VwZXJwYWNrc19tYW5p
ZmVzdF91cmxfamF0AChjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF91cmxfamEsICcnLCA0LCAwdAAc
ZW5hYmxlX3NoYXJlX2ludGVudF9mYWxsYmFja3QAKGVuYWJsZV9zaGFyZV9pbnRlbnRfZmFsbGJh
Y2ssIHRydWUsIDIsIDB0ADZmZWRlcmF0ZWRjMnFfZW5hYmxlX2N1c3RvbV90aHJlc2hvbGRzX3Ry
ZW5kaW5nX3F1ZXJpZXN0AENmZWRlcmF0ZWRjMnFfZW5hYmxlX2N1c3RvbV90aHJlc2hvbGRzX3Ry
ZW5kaW5nX3F1ZXJpZXMsIGZhbHNlLCAyLCAwdAA8ZmVkZXJhdGVkYzJxX2luZmVyZW5jZV90cmln
Z2VyaW5nX3RocmVzaG9sZF90cmVuZGluZ19xdWVyaWVzdABHZmVkZXJhdGVkYzJxX2luZmVyZW5j
ZV90cmlnZ2VyaW5nX3RocmVzaG9sZF90cmVuZGluZ19xdWVyaWVzLCAwLjAsIDMsIDB0AChnb29n
bGVfa2V5Ym9hcmRfaG90d2F0ZXJfZmF1Y2V0X2ludGVydmFsdAAxZ29vZ2xlX2tleWJvYXJkX2hv
dHdhdGVyX2ZhdWNldF9pbnRlcnZhbCwgMCwgMSwgMHQAGmVuYWJsZV9yYXRlX3VzX2luX3NldHRp
bmdzdAAmZW5hYmxlX3JhdGVfdXNfaW5fc2V0dGluZ3MsIHRydWUsIDIsIDB0AB5jMnFfc3VwZXJw
YWNrc19tYW5pZmVzdF91cmxfaXR0AIZjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF91cmxfaXQsICdo
dHRwczovL3d3dy5nc3RhdGljLmNvbS9hbmRyb2lkL2tleWJvYXJkL2NvbnYycXVlcnkvUy9pdC8y
MDE4MTAyNTIyL3N1cGVycGFja3NfbWFuaWZlc3RfaXQuemlwJywgNCwgMHQAL2xpdGVyYWxfc3Rh
cnRfcGVuYWx0eV9hbnlfYXV0b2Nvcl9yZWxhdGl2ZV9zdGVwdAA8bGl0ZXJhbF9zdGFydF9wZW5h
bHR5X2FueV9hdXRvY29yX3JlbGF0aXZlX3N0ZXAsIDAuMDAxLCAzLCAwdAAaZW5hYmxlX2Z1bGxf
YmFja3VwX2NvbnRlbnR0ACdlbmFibGVfZnVsbF9iYWNrdXBfY29udGVudCwgZmFsc2UsIDIsIDB0
AB5kZWxpZ2h0X292ZXJyaWRlc19tZXRhZGF0YV91cml0AChkZWxpZ2h0X292ZXJyaWRlc19tZXRh
ZGF0YV91cmksICcnLCA0LCAwdAAOZW5hYmxlX2xhbmdfaWR0ABtlbmFibGVfbGFuZ19pZCwgZmFs
c2UsIDIsIDB0ABBncnBjX3NlcnZlcl9ob3N0dAAyZ3JwY19zZXJ2ZXJfaG9zdCwgJ2dib2FyZC1w
YS5nb29nbGVhcGlzLmNvbScsIDQsIDB0ACRleHByZXNzaXZlX3N0aWNrZXJzX21ldGFkYXRhX3Zl
cnNpb250ADVleHByZXNzaXZlX3N0aWNrZXJzX21ldGFkYXRhX3ZlcnNpb24sICcxMDAwMDI3Jywg
NCwgMHQAHGNvbnYycXVlcnlfZXh0ZW5zaW9uX2VuYWJsZWR0AChjb252MnF1ZXJ5X2V4dGVuc2lv
bl9lbmFibGVkLCB0cnVlLCAyLCAwdAAhZW5hYmxlX3NoYXJlX2FuZF92aWV3X21vcmVfbGFiZWxz
dAAtZW5hYmxlX3NoYXJlX2FuZF92aWV3X21vcmVfbGFiZWxzLCB0cnVlLCAyLCAwdAAedHJhbnNs
YXRlX3NvdXJjZV9sYW5ndWFnZV9saXN0dAFgdHJhbnNsYXRlX3NvdXJjZV9sYW5ndWFnZV9saXN0
LCAnYWYsYW0sYXIsYXosYmUsYmcsYm4sYnMsY2EsY2ViLGNvLGNzLGN5LGRhLGRlLGVsLGVuLGVv
LGVzLGV0LGV1LGZhLGZpLGZpbCxmcixmeSxnYSxnZCxnbCxndSxoYSxoYXcsaGksaG1uLGhyLGh0
LGh1LGh5LGlkLGlnLGlzLGl0LGl3LGphLGp3LGthLGtrLGttLGtuLGtvLGt1LGt5LGxhLGxiLGxv
LGx0LGx2LG1nLG1pLG1rLG1sLG1uLG1yLG1zLG10LG15LG5lLG5sLG5vLG55LHBhLHBsLHBzLHB0
LHJvLHJ1LHNkLHNpLHNrLHNsLHNtLHNuLHNvLHNxLHNyLHN0LHN1LHN2LHN3LHRhLHRlLHRnLHRo
LHRyLHVrLHVyLHV6LHZpLHhoLHlpLHlvLHpoLHp1JywgNCwgMHQALGVtb2ppX3N1cGVycGFja3Nf
Zm9yZWdyb3VuZF9kb3dubG9hZF9lbmFibGVkdAA4ZW1vamlfc3VwZXJwYWNrc19mb3JlZ3JvdW5k
X2Rvd25sb2FkX2VuYWJsZWQsIHRydWUsIDIsIDB0ACRsc3RtX2hpZGVfbm9uX2NvbnRleHR1YWxf
cHJlZGljdGlvbnN0ADFsc3RtX2hpZGVfbm9uX2NvbnRleHR1YWxfcHJlZGljdGlvbnMsIGZhbHNl
LCAyLCAwdAAeYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsX2ZydACGYzJxX3N1cGVycGFja3Nf
bWFuaWZlc3RfdXJsX2ZyLCAnaHR0cHM6Ly93d3cuZ3N0YXRpYy5jb20vYW5kcm9pZC9rZXlib2Fy
ZC9jb252MnF1ZXJ5L1MvZnIvMjAxODEwMjUyMi9zdXBlcnBhY2tzX21hbmlmZXN0X2ZyLnppcCcs
IDQsIDB0ACZjb250ZXh0dWFsX2FwcGluZGV4aW5nX2NvbnRleHRfZW5hYmxlZHQAM2NvbnRleHR1
YWxfYXBwaW5kZXhpbmdfY29udGV4dF9lbmFibGVkLCBmYWxzZSwgMiwgMHQAHGNvbnYycXVlcnlf
ZXh0ZW5zaW9uX2xvY2FsZXN0AD1jb252MnF1ZXJ5X2V4dGVuc2lvbl9sb2NhbGVzLCAnZGUsZW4s
ZXMsZnIsaXQsbXMscHQsdGEnLCA0LCAwdAAaZW5hYmxlX3JhdGVfdXNfc2VhcmNoX2NhcmR0ACZl
bmFibGVfcmF0ZV91c19zZWFyY2hfY2FyZCwgdHJ1ZSwgMiwgMHQAImR5bmFtaWNfcmF0ZV9saW1p
dF9jYW5kaWRhdGVfdHlwZXN0AHVkeW5hbWljX3JhdGVfbGltaXRfY2FuZGlkYXRlX3R5cGVzLCAn
U0VBUkNIQUJMRV9URVhULEdJRl9TRUFSQ0hBQkxFX1RFWFQsRVhQUkVTU0lPTl9TRUFSQ0hBQkxF
X1RFWFQsTUFLRV9BX0dJRicsIDQsIDB0ABlkZWxldGVfbGVnYWN5X2RlbGlnaHRfbG1zdAAmZGVs
ZXRlX2xlZ2FjeV9kZWxpZ2h0X2xtcywgZmFsc2UsIDIsIDB0ACFlbmFibGVfY29udjJleHByZXNz
aW9uX2NhbmRpZGF0ZXN0AC1lbmFibGVfY29udjJleHByZXNzaW9uX2NhbmRpZGF0ZXMsIHRydWUs
IDIsIDB0ACRlbmFibGVfZGVjb2Rlcl9hZ25vc3RpY19lbW9qaV9zZWFyY2h0ADBlbmFibGVfZGVj
b2Rlcl9hZ25vc3RpY19lbW9qaV9zZWFyY2gsIHRydWUsIDIsIDB0ACRlbmFibGVfbWFnaWNfZ19j
YW5kaWRhdGVfc291cmNlX2ljb250ADBlbmFibGVfbWFnaWNfZ19jYW5kaWRhdGVfc291cmNlX2lj
b24sIHRydWUsIDIsIDB0ABRkZWxpZ2h0X21ldGFkYXRhX3VyaXQAbmRlbGlnaHRfbWV0YWRhdGFf
dXJpLCAnaHR0cHM6Ly93d3cuZ3N0YXRpYy5jb20vYW5kcm9pZC9rZXlib2FyZC9kaWN0aW9uYXJ5
cGFjay9TYXotbm9ybWFsL21ldGFkYXRhLmpzb24nLCA0LCAwdAAkZW5hYmxlX2Vtb2ppX3NlYXJj
aF9zdWdnZXN0aW9uX3N0cmlwdAAwZW5hYmxlX2Vtb2ppX3NlYXJjaF9zdWdnZXN0aW9uX3N0cmlw
LCB0cnVlLCAyLCAwdAASZW5hYmxlX2hhbmR3cml0aW5ndAAeZW5hYmxlX2hhbmR3cml0aW5nLCB0
cnVlLCAyLCAwdAAqZmVkZXJhdGVkYzJxX2NvbnYycXVlcnlfY2FuZGlkYXRlc19lbmFibGVkdAA2
ZmVkZXJhdGVkYzJxX2NvbnYycXVlcnlfY2FuZGlkYXRlc19lbmFibGVkLCB0cnVlLCAyLCAwdAAh
bXVsdGl3b3JkX2NhbmRpZGF0ZV9sYW5ndWFnZV90YWdzdAAwbXVsdGl3b3JkX2NhbmRpZGF0ZV9s
YW5ndWFnZV90YWdzLCAnZW4tVVMnLCA0LCAwdAAgZW5hYmxlX2NvbnYycXVlcnlfZm9yX2NoZXZy
b25fdWl0ACxlbmFibGVfY29udjJxdWVyeV9mb3JfY2hldnJvbl91aSwgdHJ1ZSwgMiwgMHQAImxp
dGVyYWxfc3RhcnRfcGVuYWx0eV9yZWxhdGl2ZV9taW50AC1saXRlcmFsX3N0YXJ0X3BlbmFsdHlf
cmVsYXRpdmVfbWluLCAwLjUsIDMsIDB0ACljb250ZXh0dWFsX3JhdGVfdXNfbWF4X2FsbG93YWJs
ZV9hdHRlbXB0c3QAMmNvbnRleHR1YWxfcmF0ZV91c19tYXhfYWxsb3dhYmxlX2F0dGVtcHRzLCA1
LCAxLCAwdAAnZHluYW1pY19yYXRlX2xpbWl0X2ludGVyYWN0aW9uX3N0cmF0ZWd5dAA2ZHluYW1p
Y19yYXRlX2xpbWl0X2ludGVyYWN0aW9uX3N0cmF0ZWd5LCAnUkVTRVQnLCA0LCAwdAAfZGVsaWdo
dF9sYXRlc3RfbWV0YWRhdGFfdmVyc2lvbnQAMWRlbGlnaHRfbGF0ZXN0X21ldGFkYXRhX3ZlcnNp
b24sIDIwMTkxMDAxMDIsIDEsIDB0ACJjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF92ZXJzaW9uX2l0
dAArYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbl9pdCwgNCwgMSwgMHQAJGZlZGVyYXRl
ZGMycV9tb2RlbHNfbWV0YWRhdGFfdmVyc2lvbnQALWZlZGVyYXRlZGMycV9tb2RlbHNfbWV0YWRh
dGFfdmVyc2lvbiwgMSwgMSwgMHQAH3N1cGVycGFja3NfZW5hYmxlX2hpc3RvcnlfdHJhY2V0ACxz
dXBlcnBhY2tzX2VuYWJsZV9oaXN0b3J5X3RyYWNlLCBmYWxzZSwgMiwgMHQAGW11bHRpd29yZF90
aHJlc2hvbGRfc2NvcmV0ACRtdWx0aXdvcmRfdGhyZXNob2xkX3Njb3JlLCAzLjAsIDMsIDB0AB5l
bW9qaV9rZXlib2FyZF9wcmV3YXJtX2VuYWJsZWR0ACtlbW9qaV9rZXlib2FyZF9wcmV3YXJtX2Vu
YWJsZWQsIGZhbHNlLCAyLCAwdAAtZW5hYmxlX2NsZWFyX2lucHV0X2FuZF9zZWxlY3RfdXBvbl9z
aGFyZV90ZXh0dAA6ZW5hYmxlX2NsZWFyX2lucHV0X2FuZF9zZWxlY3RfdXBvbl9zaGFyZV90ZXh0
LCBmYWxzZSwgMiwgMHQAF2NvdW50cnlfY3V0b3V0X3N3aXRjaGVzdAYkY291bnRyeV9jdXRvdXRf
c3dpdGNoZXMsICdBRSxBUkUsNzg0LEFHLEFURywwMjgsQUwsQUxCLDAwOCxBTyxBR08sMDI0LEFS
LEFSRywwMzIsQU0sQVJNLDA1MSxBVCxBVVQsMDQwLEFVLEFVUywwMzYsQVcsQUJXLDUzMyxBWixB
WkUsMDMxLEJBLEJJSCwwNzAsQkQsQkdELDA1MCxCRSxCRUwsMDU2LEJGLEJGQSw4NTQsQkcsQkdS
LDEwMCxCSCxCSFIsMDQ4LEJKLEJFTiwyMDQsQkcsQkdSLDEwMCxCTyxCT0wsMDY4LEJSLEJSQSww
NzYsQlMsQkhTLDA0NCxCVyxCV0EsMDcyLEJZLEJMUiwxMTIsQlosQkxaLDA4NCxDQSxDQU4sMTI0
LENILENIRSw3NTYsQ0wsQ0hMLDE1MixDTSxDTVIsMTIwLENOLENITiwxNTYsQ08sQ09MLDE3MCxD
UixDUkksMTg4LENVLENVQiwxOTIsQ1YsQ1BWLDEzMixDWSxDWVAsMTk2LENaLENaRSwyMDMsREUs
REVVLDI3NixETyxET00sMjE0LERLLEROSywyMDgsRFosRFpBLDAxMixFQyxFQ1UsMjE4LEVHLEVH
WSw4MTgsRVMsRVNQLDcyNCxFRSxFU1QsMjMzLEZJLEZJTiwyNDYsRkosRkpJLDI0MixGUixGUkEs
MjUwLEdBLEdBQiwyNjYsR0IsR0JSLDgyNixHSCxHSEEsMjg4LEdSLEdSQywzMDAsR1QsR1RNLDMy
MCxHVyxHTkIsNjI0LEhLLEhLRywzNDQsSE4sSE5ELDM0MCxIUixIUlYsMTkxLEhULEhUSSwzMzIs
SFUsSFVOLDM0OCxJRCxJRE4sMzYwLElFLElSTCwzNzIsSUwsSVNSLDM3NixJTixJTkQsMzU2LElS
LElSTiwzNjQsSVMsSVNMLDM1MixJVCxJVEEsMzgwLEpNLEpBTSwzODgsSk8sSk9SLDQwMCxKUCxK
UE4sMzkyLEtFLEtFTiw0MDQsS0csS0daLDQxNyxLSCxLSE0sMTE2LEtSLEtPUiw0MTAsS1csS1dU
LDQxNCxLWixLQVosMzk4LExBLExBTyw0MTgsTEIsTEJOLDQyMixMSSxMSUUsNDM4LExLLExLQSwx
NDQsTFQsTFRVLDQ0MCxMVSxMVVgsNDQyLExWLExWQSw0MjgsTkwsTkxELDUyOCxNQSxNQVIsNTA0
LE1ELE1EQSw0OTgsTUssTUtELDgwNyxNTCxNTEksNDY2LE1ULE1MVCw0NzAsTVUsTVVTLDQ4MCxN
WCxNRVgsNDg0LE1ZLE1ZUyw0NTgsTVosTU9aLDUwOCxOQSxOQU0sNTE2LE5FLE5FUiw1NjIsTkcs
TkdBLDU2NixOSSxOSUMsNTU4LE5MLE5MRCw1MjgsTk8sTk9SLDU3OCxOUCxOUEwsNTI0LE5aLE5a
TCw1NTQsT00sT01OLDUxMixQQSxQQU4sNTkxLFBFLFBFUiw2MDQsUEcsUE5HLDU5OCxQSCxQSEws
NjA4LFBLLFBBSyw1ODYsUEwsUE9MLDYxNixQVCxQUlQsNjIwLFBZLFBSWSw2MDAsUUEsUUFULDYz
NCxSTyxST1UsNjQyLFJTLFNSQiw2ODgsUlUsUlVTLDY0MyxSVyxSV0EsNjQ2LFNBLFNBVSw2ODIs
U0QsU0ROLDczNixTRSxTV0UsNzUyLFNHLFNHUCw3MDIsU0ksU1ZOLDcwNSxTSyxTVkssNzAzLFNO
LFNFTiw2ODYsU1YsU0xWLDIyMixURyxUR08sNzY4LFRILFRIQSw3NjQsVEosVEpLLDc2MixUTSxU
S00sNzk1LFROLFRVTiw3ODgsVFIsVFVSLDc5MixUVCxUVE8sNzgwLFRXLFRXTiwxNTgsVFosVFpB
LDgzNCxVQSxVS1IsODA0LFVHLFVHQSw4MDAsVVMsVVNBLDg0MCxVWSxVUlksODU4LFVaLFVaQiw4
NjAsVkUsVkVOLDg2MixWTixWTk0sNzA0LFlFLFlFTSw4ODcsWkEsWkFGLDcxMCxaTSxaTUIsODk0
LFpXLFpXRSw3MTYnLCA0LCAwdAAnY29udGV4dHVhbF9hbm5vdGF0b3Jfc3VwZXJwYWNrc192ZXJz
aW9udAA3Y29udGV4dHVhbF9hbm5vdGF0b3Jfc3VwZXJwYWNrc192ZXJzaW9uLCAyMDE4MDMyMCwg
MSwgMHQAKmxpdGVyYWxfc3RhcnRfcGVuYWx0eV9yZXZlcnRfcmVsYXRpdmVfc3RlcHQANmxpdGVy
YWxfc3RhcnRfcGVuYWx0eV9yZXZlcnRfcmVsYXRpdmVfc3RlcCwgMC4wMSwgMywgMHQAImMycV9z
dXBlcnBhY2tzX21hbmlmZXN0X3ZlcnNpb25famF0ACtjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF92
ZXJzaW9uX2phLCAwLCAxLCAwdAAQY3VyYXRlZF9naWZfdXJsc3QFTWN1cmF0ZWRfZ2lmX3VybHMs
ICdodHRwczovL21lZGlhLnRlbm9yLmNvbS9pbWFnZXMvZWI3MDdiYjljMTZjY2UyNzgzMDliODA2
NDM3ZGUwOTcvdGVub3IuZ2lmLGh0dHBzOi8vbWVkaWEudGVub3IuY29tL2ltYWdlcy9iYjNjMTU4
NTM4OGM3NjE0MGE1NjI0M2FkNTg1MTZlMy90ZW5vci5naWYsaHR0cHM6Ly9tZWRpYS50ZW5vci5j
b20vaW1hZ2VzLzhjZjM4NTQzZWViZmYxMDNkZjZmMWVjMjczMGE1YmRlL3Rlbm9yLmdpZixodHRw
czovL21lZGlhLnRlbm9yLmNvbS9pbWFnZXMvZjJkY2FhZmZlMjlhYzExMWRmOGUzMzMyMjFlZTIz
MWIvdGVub3IuZ2lmLGh0dHBzOi8vbWVkaWEudGVub3IuY29tL2ltYWdlcy9hNDZmYjE2M2VlZGFj
OGI3M2ZkNWIzNzUyMmJiNjQ1NC90ZW5vci5naWYsaHR0cHM6Ly9tZWRpYS50ZW5vci5jb20vaW1h
Z2VzL2Q3ZTk4MzlmNzgxNmYyZTdlMDA4MzNkMzg3OGM4YWU2L3Rlbm9yLmdpZixodHRwczovL21l
ZGlhLnRlbm9yLmNvbS9pbWFnZXMvODkwYTBmNjUwNDA1MDU0YjgyNTEwYzgzYjExYTRiZTQvdGVu
b3IuZ2lmLGh0dHBzOi8vbWVkaWEudGVub3IuY29tL2ltYWdlcy9hNjI1MzEyZWZlYzc1ZDA0ODdk
MmQ5Y2JhYTQ0YTMxNi90ZW5vci5naWYsaHR0cHM6Ly9tZWRpYS50ZW5vci5jb20vaW1hZ2VzLzMy
MzMzNGIyYTNkNDQ4YjI5NmJiODEzYjI1YzEyYjk2L3Rlbm9yLmdpZixodHRwczovL21lZGlhLnRl
bm9yLmNvbS9pbWFnZXMvYjIzNzcwNzgyZGQxMGU0MWQxZWZiMjU0N2VkNGIxMDYvdGVub3IuZ2lm
LGh0dHBzOi8vbWVkaWEudGVub3IuY29tL2ltYWdlcy8zNTc5YzJlYTg3ZGFiNjEyMzMxZmU2NjQy
Y2Y3MmJjNS90ZW5vci5naWYsaHR0cHM6Ly9tZWRpYS50ZW5vci5jb20vaW1hZ2VzLzA1M2Y0YmVj
ZGI5MWY3OGI3OGVmMWY0MjA2ODZmOTcxL3Rlbm9yLmdpZixodHRwczovL21lZGlhLnRlbm9yLmNv
bS9pbWFnZXMvZjVmYWZhOTAyM2QyY2EwMjQyZTU2NWNjYTMyMTU3NWEvdGVub3IuZ2lmLGh0dHBz
Oi8vbWVkaWEudGVub3IuY29tL2ltYWdlcy9lMzA2NzQ0NWU0YWRhZThiYmY0ZWViZjVjNWU3MDU4
Mi90ZW5vci5naWYsaHR0cHM6Ly9tZWRpYS50ZW5vci5jb20vaW1hZ2VzL2UxNTY4ZDFhOWNkNjEx
MmI2NDc1NzMxOWM4MTMwYjY3L3Rlbm9yLmdpZixodHRwczovL21lZGlhLnRlbm9yLmNvbS9pbWFn
ZXMvNzJkNmExZWUzNjAxZTA3YWMwZTBmNmU0NDZmYjEwNzAvdGVub3IuZ2lmLGh0dHBzOi8vbWVk
aWEudGVub3IuY29tL2ltYWdlcy85ZjMyNWRiMjQwMmE5M2M2NDVmODAyODExYTE3ZTA0ZC90ZW5v
ci5naWYsaHR0cHM6Ly9tZWRpYS50ZW5vci5jb20vaW1hZ2VzL2JkMTU2OWJiMmQxYTg1NzgwY2Zk
MjM4NmQ1MzMzMDcyL3Rlbm9yLmdpZicsIDQsIDB0ABtkb3dubG9hZGFibGVfdGhlbWVfYmFzZV91
cmx0AF9kb3dubG9hZGFibGVfdGhlbWVfYmFzZV91cmwsICdodHRwczovL3d3dy5nc3RhdGljLmNv
bS9hbmRyb2lkL2tleWJvYXJkL3RoZW1lL1JlZ2FsL3Byb2QvJywgNCwgMHQAM2R5bmFtaWNfcmF0
ZV9saW1pdF9zdG9yZV9pbXByZXNzaW9uc19pbl9wcmVmZXJlbmNlc3QAP2R5bmFtaWNfcmF0ZV9s
aW1pdF9zdG9yZV9pbXByZXNzaW9uc19pbl9wcmVmZXJlbmNlcywgdHJ1ZSwgMiwgMHQAG2VuYWJs
ZV9uZXVyYWxfc3BhdGlhbF9tb2RlbHQAJ2VuYWJsZV9uZXVyYWxfc3BhdGlhbF9tb2RlbCwgdHJ1
ZSwgMiwgMHQAI2hhbmR3cml0aW5nX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsdACCaGFuZHdyaXRp
bmdfc3VwZXJwYWNrc19tYW5pZmVzdF91cmwsICdodHRwczovL2RsLmdvb2dsZS5jb20vaGFuZHdy
aXRpbmcvbW9kZWxzL2hhbmR3cml0aW5nLnN1cGVycGFja19tYW5pZmVzdC4yMDE4MDcwOS5qc29u
JywgNCwgMHQAIXVuc3VwcG9ydGVkX2FwcHNfZm9yX3NoYXJlX2ludGVudHQArHVuc3VwcG9ydGVk
X2FwcHNfZm9yX3NoYXJlX2ludGVudCwgJ2NvbS5nb29nbGUuYW5kcm9pZC5nbSxjb20uZ29vZ2xl
LmFuZHJvaWQuZ20ubGl0ZSxjb20uYW5kcm9pZC5zeXN0ZW11aSxjb20uZmFjZWJvb2sua2F0YW5h
LGNvbS5mYWNlYm9vay5saXRlLGNvbS5pbnN0YWdyYW0uYW5kcm9pZCcsIDQsIDB0AB5jMnFfc3Vw
ZXJwYWNrc19tYW5pZmVzdF91cmxfZW50AIZjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF91cmxfZW4s
ICdodHRwczovL3d3dy5nc3RhdGljLmNvbS9hbmRyb2lkL2tleWJvYXJkL2NvbnYycXVlcnkvUy9l
bi8yMDE4MTAyNjA0L3N1cGVycGFja3NfbWFuaWZlc3RfZW4uemlwJywgNCwgMHQAF2ZlZGVyYXRl
ZGMycV9jb3JwdXNfdGFndAAqZmVkZXJhdGVkYzJxX2NvcnB1c190YWcsICdnbG93Zy9zYXonLCA0
LCAwdAAbZW5hYmxlX3JhdGVfdXNfZmVhdHVyZV9jYXJkdAAnZW5hYmxlX3JhdGVfdXNfZmVhdHVy
ZV9jYXJkLCB0cnVlLCAyLCAwdAAeYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsX2VzdACGYzJx
X3N1cGVycGFja3NfbWFuaWZlc3RfdXJsX2VzLCAnaHR0cHM6Ly93d3cuZ3N0YXRpYy5jb20vYW5k
cm9pZC9rZXlib2FyZC9jb252MnF1ZXJ5L1MvZXMvMjAxODEwMjUyMi9zdXBlcnBhY2tzX21hbmlm
ZXN0X2VzLnppcCcsIDQsIDB0AChlbmFibGVfZmMycV9sb2dfc2hhcmVzX3RvX3RyYWluaW5nX2Nh
Y2hldAA0ZW5hYmxlX2ZjMnFfbG9nX3NoYXJlc190b190cmFpbmluZ19jYWNoZSwgdHJ1ZSwgMiwg
MHQAFm11bHRpd29yZF9nZXN0dXJlX2Nvc3R0ACFtdWx0aXdvcmRfZ2VzdHVyZV9jb3N0LCA1LjAs
IDMsIDB0ACVmZWRlcmF0ZWRjMnFfcHJlZGljdGlvbl9tb2RlbF92YXJpYW50dAAvZmVkZXJhdGVk
YzJxX3ByZWRpY3Rpb25fbW9kZWxfdmFyaWFudCwgJycsIDQsIDB0AB5rZXlfY29ycmVjdGlvbl9p
Z25vcmVfZnJhY3Rpb250AClrZXlfY29ycmVjdGlvbl9pZ25vcmVfZnJhY3Rpb24sIDAuOCwgMywg
MHQAImMycV9zdXBlcnBhY2tzX21hbmlmZXN0X3ZlcnNpb25fZnJ0ACtjMnFfc3VwZXJwYWNrc19t
YW5pZmVzdF92ZXJzaW9uX2ZyLCA0LCAxLCAwdAAbdXNlcl9oaXN0b3J5X3JldGVudGlvbl9kYXlz
dAAldXNlcl9oaXN0b3J5X3JldGVudGlvbl9kYXlzLCA2MywgMSwgMHQAHHNhdmVfbm9uX3ByaW1l
X2tleWJvYXJkX3R5cGV0AChzYXZlX25vbl9wcmltZV9rZXlib2FyZF90eXBlLCB0cnVlLCAyLCAw
dAAoZmVkZXJhdGVkYzJxX3JhbmtpbmdfdHJhaW5pbmdfcG9wdWxhdGlvbnQAMmZlZGVyYXRlZGMy
cV9yYW5raW5nX3RyYWluaW5nX3BvcHVsYXRpb24sICcnLCA0LCAwdAAOdXJnZW50X3NpZ25hbHN0
HBt1cmdlbnRfc2lnbmFscywgJ0NOVHdyWVVCRWdJSUFSTHRLUWdCRWlrSUJSSUZZWEpmUVVVYUhn
b04yTFBaZzlpeklObUIyWVRaaFFvTjJZSFpoTm1GSU5pejJZUFlzeElwQ0FVU0JXRnlYMEpJR2g0
S0RkaXoyWVBZc3lEWmdkbUUyWVVLRGRtQjJZVFpoU0RZczltRDJMTVNLUWdGRWdWaGNsOUVTaG9l
Q2czWXM5bUQyTE1nMllIWmhObUZDZzNaZ2RtRTJZVWcyTFBaZzlpekVpa0lCUklGWVhKZlJGb2FI
Z29OMkxQWmc5aXpJTm1CMllUWmhRb04yWUhaaE5tRklOaXoyWVBZc3hJcENBVVNCV0Z5WDBWSEdo
NEtEZGl6MllQWXN5RFpnZG1FMllVS0RkbUIyWVRaaFNEWXM5bUQyTE1TS1FnRkVnVmhjbDlNV1Jv
ZUNnM1lzOW1EMkxNZzJZSFpoTm1GQ2czWmdkbUUyWVVnMkxQWmc5aXpFaWtJQlJJRllYSmZUVUVh
SGdvTjJMUFpnOWl6SU5tQjJZVFpoUW9OMllIWmhObUZJTml6MllQWXN4SXBDQVVTQldGeVgwOU5H
aDRLRGRpejJZUFlzeURaZ2RtRTJZVUtEZG1CMllUWmhTRFlzOW1EMkxNU0tRZ0ZFZ1ZoY2w5VFFS
b2VDZzNZczltRDJMTWcyWUhaaE5tRkNnM1pnZG1FMllVZzJMUFpnOWl6RWlrSUJSSUZZWEpmVTBR
YUhnb04yTFBaZzlpeklObUIyWVRaaFFvTjJZSFpoTm1GSU5pejJZUFlzeElwQ0FVU0JXRnlYMVJP
R2g0S0RkaXoyWVBZc3lEWmdkbUUyWVVLRGRtQjJZVFpoU0RZczltRDJMTVNQQWdGRWdWaWJsOUNS
Qm94Q2hYZ3BxYmdwNEhncHFmZ3BwZmdwNEhncHJMZ3A0c0tHT0NtdU9DbmplQ21wT0NtcU9DbXB1
Q25nZUNtbitDbml4SThDQVVTQldKdVgwbE9HakVLRmVDbXB1Q25nZUNtcCtDbWwrQ25nZUNtc3VD
bml3b1k0S2E0NEtlTjRLYWs0S2FvNEthbTRLZUI0S2FmNEtlTEVrTUlCUklDWTNNYU93b1JjRzlz
ZVd2RG9XN0RyU0J6WlcxbGJtVUtFWEJ2Ykhscnc2RnV3NjBnYzNCbGNtMWhDaE53YjJ4NWE4T2hi
c090SUhOd1pYSnRZWFIxRWlVSUJSSUNaR0VhSFFvSGEyNWxjSEJsZEFvTmJjT21jbXRsYkdsbklI
TmxlQW9EY0dsckV1d0NDQVVTQldWdVgwRlZHdUFDQ2d4aWFYTmxlSFZoYkNCdFpXNEtFbUpwYzJW
NGRXRnNJSFJvY21WbGMyOXRaUW9LWW14aFkyc2daR2xqYXdvRVkyOWphd29MWTNWdWJtbHNhVzVu
ZFhNS0IyWmxiR3hoZEdVS0NHWmxiR3hoZEdWa0NnaG1aV3hzWVhScGJ3b05aMjlzWkdWdUlITm9i
M2RsY2dvUGFXNTBieUJpYkdGamF5Qm5kWGx6Q2dsc1lYQWdaR0Z1WTJVS0RXeGxjMkpwWVc0Z1lt
RmlaWE1LRFd4bGMySnBZVzRnWjJseWJITUtEV3hsYzJKcFlXNGdkR1ZsYm5NS0JXNXBaMmRoQ2da
dWFXZG5aWElLQkc5eVlXd0tEWEpoWkdsallXd2dhWE5zWVcwS0QzSmhaR2xqWVd3Z2FYTnNZVzFw
WXdvR2NtVjBZWEprQ2doeVpYUmhjbVJsWkFvSGNtVjBZWEprY3dvT2MybDBJRzl1SUcxNUlHWmhZ
MlVLRFhOcGRDQnZiaUJ0ZVNCc1lYQUtFSE5wZENCdmJpQjViM1Z5SUdaaFkyVUtEM05wZENCdmJp
QjViM1Z5SUd4aGNBb0tjM1JwWm1ZZ1kyOWphd29LYzNScFptWWdaR2xqYXhMc0FnZ0ZFZ1ZsYmw5
RFFScmdBZ29NWW1selpYaDFZV3dnYldWdUNoSmlhWE5sZUhWaGJDQjBhSEpsWlhOdmJXVUtDbUpz
WVdOcklHUnBZMnNLQkdOdlkyc0tDMk4xYm01cGJHbHVaM1Z6Q2dkbVpXeHNZWFJsQ2dobVpXeHNZ
WFJsWkFvSVptVnNiR0YwYVc4S0RXZHZiR1JsYmlCemFHOTNaWElLRDJsdWRHOGdZbXhoWTJzZ1oz
VjVjd29KYkdGd0lHUmhibU5sQ2cxc1pYTmlhV0Z1SUdKaFltVnpDZzFzWlhOaWFXRnVJR2RwY214
ekNnMXNaWE5pYVdGdUlIUmxaVzV6Q2dWdWFXZG5ZUW9HYm1sbloyVnlDZ1J2Y21Gc0NnMXlZV1Jw
WTJGc0lHbHpiR0Z0Q2c5eVlXUnBZMkZzSUdsemJHRnRhV01LQm5KbGRHRnlaQW9JY21WMFlYSmta
V1FLQjNKbGRHRnlaSE1LRG5OcGRDQnZiaUJ0ZVNCbVlXTmxDZzF6YVhRZ2IyNGdiWGtnYkdGd0No
QnphWFFnYjI0Z2VXOTFjaUJtWVdObENnOXphWFFnYjI0Z2VXOTFjaUJzWVhBS0NuTjBhV1ptSUdO
dlkyc0tDbk4wYVdabUlHUnBZMnNTN0FJSUJSSUZaVzVmUjBJYTRBSUtER0pwYzJWNGRXRnNJRzFs
YmdvU1ltbHpaWGgxWVd3Z2RHaHlaV1Z6YjIxbENncGliR0ZqYXlCa2FXTnJDZ1JqYjJOckNndGpk
VzV1YVd4cGJtZDFjd29IWm1Wc2JHRjBaUW9JWm1Wc2JHRjBaV1FLQ0dabGJHeGhkR2x2Q2cxbmIy
eGtaVzRnYzJodmQyVnlDZzlwYm5SdklHSnNZV05ySUdkMWVYTUtDV3hoY0NCa1lXNWpaUW9OYkdW
elltbGhiaUJpWVdKbGN3b05iR1Z6WW1saGJpQm5hWEpzY3dvTmJHVnpZbWxoYmlCMFpXVnVjd29G
Ym1sbloyRUtCbTVwWjJkbGNnb0ViM0poYkFvTmNtRmthV05oYkNCcGMyeGhiUW9QY21Ga2FXTmhi
Q0JwYzJ4aGJXbGpDZ1p5WlhSaGNtUUtDSEpsZEdGeVpHVmtDZ2R5WlhSaGNtUnpDZzV6YVhRZ2Iy
NGdiWGtnWm1GalpRb05jMmwwSUc5dUlHMTVJR3hoY0FvUWMybDBJRzl1SUhsdmRYSWdabUZqWlFv
UGMybDBJRzl1SUhsdmRYSWdiR0Z3Q2dwemRHbG1aaUJqYjJOckNncHpkR2xtWmlCa2FXTnJFcTBE
Q0FVU0JXVnVYMGxPR3FFRENneGlhWE5sZUhWaGJDQnRaVzRLRW1KcGMyVjRkV0ZzSUhSb2NtVmxj
Mjl0WlFvS1lteGhZMnNnWkdsamF3b0ZZMmh2YjNRS0JHTm9kWFFLQkdOdlkyc0tDMk4xYm01cGJH
bHVaM1Z6Q2dkbVpXeHNZWFJsQ2dobVpXeHNZWFJsWkFvSVptVnNiR0YwYVc4S0JXZGhZVzVrQ2dS
bllXNWtDZzFuYjJ4a1pXNGdjMmh2ZDJWeUNnOXBiblJ2SUdKc1lXTnJJR2QxZVhNS0NXeGhjQ0Jr
WVc1alpRb05iR1Z6WW1saGJpQmlZV0psY3dvTmJHVnpZbWxoYmlCbmFYSnNjd29OYkdWelltbGhi
aUIwWldWdWN3b0ZibWxuWjJFS0JtNXBaMmRsY2dvRWIzSmhiQW9OY21Ga2FXTmhiQ0JwYzJ4aGJR
b1BjbUZrYVdOaGJDQnBjMnhoYldsakNnWnlaWFJoY21RS0NISmxkR0Z5WkdWa0NnZHlaWFJoY21S
ekNnNXphWFFnYjI0Z2JYa2dabUZqWlFvTmMybDBJRzl1SUcxNUlHeGhjQW9RYzJsMElHOXVJSGx2
ZFhJZ1ptRmpaUW9QYzJsMElHOXVJSGx2ZFhJZ2JHRndDZ3B6ZEdsbVppQmpiMk5yQ2dwemRHbG1a
aUJrYVdOckNoQnpkWEJ3YjNKMElHNWhjbVZ1WkhKaENoTnpkWEJ3YjNKMElITjFZbkpoYldGdWFX
RnVFdXdDQ0FVU0JXVnVYMHRGR3VBQ0NneGlhWE5sZUhWaGJDQnRaVzRLRW1KcGMyVjRkV0ZzSUhS
b2NtVmxjMjl0WlFvS1lteGhZMnNnWkdsamF3b0VZMjlqYXdvTFkzVnVibWxzYVc1bmRYTUtCMlps
Ykd4aGRHVUtDR1psYkd4aGRHVmtDZ2htWld4c1lYUnBid29OWjI5c1pHVnVJSE5vYjNkbGNnb1Bh
VzUwYnlCaWJHRmpheUJuZFhsekNnbHNZWEFnWkdGdVkyVUtEV3hsYzJKcFlXNGdZbUZpWlhNS0RX
eGxjMkpwWVc0Z1oybHliSE1LRFd4bGMySnBZVzRnZEdWbGJuTUtCVzVwWjJkaENnWnVhV2RuWlhJ
S0JHOXlZV3dLRFhKaFpHbGpZV3dnYVhOc1lXMEtEM0poWkdsallXd2dhWE5zWVcxcFl3b0djbVYw
WVhKa0NnaHlaWFJoY21SbFpBb0hjbVYwWVhKa2N3b09jMmwwSUc5dUlHMTVJR1poWTJVS0RYTnBk
Q0J2YmlCdGVTQnNZWEFLRUhOcGRDQnZiaUI1YjNWeUlHWmhZMlVLRDNOcGRDQnZiaUI1YjNWeUlH
eGhjQW9LYzNScFptWWdZMjlqYXdvS2MzUnBabVlnWkdsamF4THNBZ2dGRWdWbGJsOU9SeHJnQWdv
TVltbHpaWGgxWVd3Z2JXVnVDaEppYVhObGVIVmhiQ0IwYUhKbFpYTnZiV1VLQ21Kc1lXTnJJR1Jw
WTJzS0JHTnZZMnNLQzJOMWJtNXBiR2x1WjNWekNnZG1aV3hzWVhSbENnaG1aV3hzWVhSbFpBb0la
bVZzYkdGMGFXOEtEV2R2YkdSbGJpQnphRzkzWlhJS0QybHVkRzhnWW14aFkyc2daM1Y1Y3dvSmJH
RndJR1JoYm1ObENnMXNaWE5pYVdGdUlHSmhZbVZ6Q2cxc1pYTmlhV0Z1SUdkcGNteHpDZzFzWlhO
aWFXRnVJSFJsWlc1ekNnVnVhV2RuWVFvR2JtbG5aMlZ5Q2dSdmNtRnNDZzF5WVdScFkyRnNJR2x6
YkdGdENnOXlZV1JwWTJGc0lHbHpiR0Z0YVdNS0JuSmxkR0Z5WkFvSWNtVjBZWEprWldRS0IzSmxk
R0Z5WkhNS0RuTnBkQ0J2YmlCdGVTQm1ZV05sQ2cxemFYUWdiMjRnYlhrZ2JHRndDaEJ6YVhRZ2Iy
NGdlVzkxY2lCbVlXTmxDZzl6YVhRZ2IyNGdlVzkxY2lCc1lYQUtDbk4wYVdabUlHTnZZMnNLQ25O
MGFXWm1JR1JwWTJzUzdBSUlCUklGWlc1ZlVFZ2E0QUlLREdKcGMyVjRkV0ZzSUcxbGJnb1NZbWx6
WlhoMVlXd2dkR2h5WldWemIyMWxDZ3BpYkdGamF5QmthV05yQ2dSamIyTnJDZ3RqZFc1dWFXeHBi
bWQxY3dvSFptVnNiR0YwWlFvSVptVnNiR0YwWldRS0NHWmxiR3hoZEdsdkNnMW5iMnhrWlc0Z2My
aHZkMlZ5Q2c5cGJuUnZJR0pzWVdOcklHZDFlWE1LQ1d4aGNDQmtZVzVqWlFvTmJHVnpZbWxoYmlC
aVlXSmxjd29OYkdWelltbGhiaUJuYVhKc2N3b05iR1Z6WW1saGJpQjBaV1Z1Y3dvRmJtbG5aMkVL
Qm01cFoyZGxjZ29FYjNKaGJBb05jbUZrYVdOaGJDQnBjMnhoYlFvUGNtRmthV05oYkNCcGMyeGhi
V2xqQ2daeVpYUmhjbVFLQ0hKbGRHRnlaR1ZrQ2dkeVpYUmhjbVJ6Q2c1emFYUWdiMjRnYlhrZ1pt
RmpaUW9OYzJsMElHOXVJRzE1SUd4aGNBb1FjMmwwSUc5dUlIbHZkWElnWm1GalpRb1BjMmwwSUc5
dUlIbHZkWElnYkdGd0NncHpkR2xtWmlCamIyTnJDZ3B6ZEdsbVppQmthV05yRXBZRENBVVNCV1Z1
WDFWVEdvb0RDZ3hpYVhObGVIVmhiQ0J0Wlc0S0VtSnBjMlY0ZFdGc0lIUm9jbVZsYzI5dFpRb0tZ
bXhoWTJzZ1pHbGphd29FWTI5amF3b0xZM1Z1Ym1sc2FXNW5kWE1LQjJabGJHeGhkR1VLQ0dabGJH
eGhkR1ZrQ2dobVpXeHNZWFJwYndvWVoyeHZZbUZzSUhkaGNtMXBibWNnYVhNZ1lTQm9iMkY0Q2cx
bmIyeGtaVzRnYzJodmQyVnlDZzlwYm5SdklHSnNZV05ySUdkMWVYTUtDV3hoY0NCa1lXNWpaUW9O
YkdWelltbGhiaUJpWVdKbGN3b05iR1Z6WW1saGJpQm5hWEpzY3dvTmJHVnpZbWxoYmlCMFpXVnVj
d29GYm1sbloyRUtCbTVwWjJkbGNnb0ViM0poYkFvTmNtRmthV05oYkNCcGMyeGhiUW9QY21Ga2FX
TmhiQ0JwYzJ4aGJXbGpDZ1p5WlhSaGNtUUtDSEpsZEdGeVpHVmtDZ2R5WlhSaGNtUnpDZzV6YUdV
bmN5QmhJSFpwY21kcGJnb09jMmwwSUc5dUlHMTVJR1poWTJVS0RYTnBkQ0J2YmlCdGVTQnNZWEFL
RUhOcGRDQnZiaUI1YjNWeUlHWmhZMlVLRDNOcGRDQnZiaUI1YjNWeUlHeGhjQW9LYzNScFptWWdZ
MjlqYXdvS2MzUnBabVlnWkdsamF4THNBZ2dGRWdWbGJsOWFRUnJnQWdvTVltbHpaWGgxWVd3Z2JX
VnVDaEppYVhObGVIVmhiQ0IwYUhKbFpYTnZiV1VLQ21Kc1lXTnJJR1JwWTJzS0JHTnZZMnNLQzJO
MWJtNXBiR2x1WjNWekNnZG1aV3hzWVhSbENnaG1aV3hzWVhSbFpBb0labVZzYkdGMGFXOEtEV2R2
YkdSbGJpQnphRzkzWlhJS0QybHVkRzhnWW14aFkyc2daM1Y1Y3dvSmJHRndJR1JoYm1ObENnMXNa
WE5pYVdGdUlHSmhZbVZ6Q2cxc1pYTmlhV0Z1SUdkcGNteHpDZzFzWlhOaWFXRnVJSFJsWlc1ekNn
VnVhV2RuWVFvR2JtbG5aMlZ5Q2dSdmNtRnNDZzF5WVdScFkyRnNJR2x6YkdGdENnOXlZV1JwWTJG
c0lHbHpiR0Z0YVdNS0JuSmxkR0Z5WkFvSWNtVjBZWEprWldRS0IzSmxkR0Z5WkhNS0RuTnBkQ0J2
YmlCdGVTQm1ZV05sQ2cxemFYUWdiMjRnYlhrZ2JHRndDaEJ6YVhRZ2IyNGdlVzkxY2lCbVlXTmxD
Zzl6YVhRZ2IyNGdlVzkxY2lCc1lYQUtDbk4wYVdabUlHTnZZMnNLQ25OMGFXWm1JR1JwWTJzU1Fn
Z0ZFZ1psYzE4ME1Ua2FOZ29RWTNWeVlYTWdZV0oxYzJGa2IzSmxjd29RWTNWeVlYTWdjR1ZrWlhK
aGMzUmhjd29RWTNWeVlYTWdjR1ZrdzdObWFXeHZjeEpCQ0FVU0JXVnpYMEZTR2pZS0VHTjFjbUZ6
SUdGaWRYTmhaRzl5WlhNS0VHTjFjbUZ6SUhCbFpHVnlZWE4wWVhNS0VHTjFjbUZ6SUhCbFpNT3pa
bWxzYjNNU1FRZ0ZFZ1ZsYzE5RlV4bzJDaEJqZFhKaGN5QmhZblZ6WVdSdmNtVnpDaEJqZFhKaGN5
QndaV1JsY21GemRHRnpDaEJqZFhKaGN5QndaV1REczJacGJHOXpFa0VJQlJJRlpYTmZUVmdhTmdv
UVkzVnlZWE1nWVdKMWMyRmtiM0psY3dvUVkzVnlZWE1nY0dWa1pYSmhjM1JoY3dvUVkzVnlZWE1n
Y0dWa3c3Tm1hV3h2Y3hKQkNBVVNCV1Z6WDFWVEdqWUtFR04xY21GeklHRmlkWE5oWkc5eVpYTUtF
R04xY21GeklIQmxaR1Z5WVhOMFlYTUtFR04xY21GeklIQmxaTU96Wm1sc2IzTVNIQWdGRWdWbWNs
OUNSUm9SQ2c5aGRtRnNaU0JrZFNCemNHVnliV1VTSEFnRkVnVm1jbDlEUVJvUkNnOWhkbUZzWlNC
a2RTQnpjR1Z5YldVU0hBZ0ZFZ1ZtY2w5RFNCb1JDZzloZG1Gc1pTQmtkU0J6Y0dWeWJXVVNIQWdG
RWdWbWNsOUdVaG9SQ2c5aGRtRnNaU0JrZFNCemNHVnliV1VTRlFnRkVnSm9jaG9OQ2d0MVltbHFJ
SEJsWkdWeVlSSWVDQVVTQW1sdUdoWUtDbVp2ZEc4Z1luVm5hV3dLQ0dadmRHOGdhRzkwRWgwSUJS
SUZhWFJmUTBnYUVnb1FhVzVuYjJsdklHUnBJSE53WlhKdFlSSWRDQVVTQldsMFgwbFVHaElLRUds
dVoyOXBieUJrYVNCemNHVnliV0VTSFFnRkVnSnBkeG9WQ2hQWHBOZWcxNVhYbWRlVUlOZWMxNkhY
cDllaEVqUUlCUklDY0d3YUxBb0ZhM1Z5ZDNrS0JtMTFjbnA1YmdvSmJYVnllbmx1dzdOM0NnUnVZ
V2R2Q2dWd2IzSnVid29EYzJWNEVrOElCUklGY0hSZlFsSWFSQW9KWVhOellXNW9ZV1JoQ2dWa1lX
NWtid29TYm1WbmNtbHVhR0VnWkdWc2FXTnBiM05oQ2d0dVpXZDFhVzVvWVNCa1lRb0hibTkyYVc1
b1lRb0djMkZtWVdSaEVoTUlCUklGY205ZlVrOGFDQW9HWm5WMGRYUmxFbGtJQlJJRmNuVmZRbGth
VGdvdjBLUFF1dEdBMExEUXVOQzkwWUhRdXRDNDBZVWcwTDNRc05HRzBMalF2dEM5MExEUXU5QzQw
WUhSZ3RDKzBMSUtHOUN6MEx2UXZ0R0MwTERSZ3RHTUlOR0IwTC9RdGRHQTBMelJneEpaQ0FVU0JY
SjFYMHRIR2s0S0w5Q2owTHJSZ05DdzBMalF2ZEdCMExyUXVOR0ZJTkM5MExEUmh0QzQwTDdRdmRD
dzBMdlF1TkdCMFlMUXZ0Q3lDaHZRczlDNzBMN1JndEN3MFlMUmpDRFJnZEMvMExYUmdOQzgwWU1T
V1FnRkVnVnlkVjlTVlJwT0NpL1FvOUM2MFlEUXNOQzQwTDNSZ2RDNjBMalJoU0RRdmRDdzBZYlF1
TkMrMEwzUXNOQzcwTGpSZ2RHQzBMN1FzZ29iMExQUXU5QyswWUxRc05HQzBZd2cwWUhRdjlDMTBZ
RFF2TkdERWpZSUJSSUZkR0ZmU1U0YUt3b1M0SzZhNEsrQjRLNmo0SytONEs2ajRLK0FDaFhncnBy
Z3I0SGdycW5ncjQzZ3Jxbmdyci9ncnE4U05nZ0ZFZ1YwWVY5TVN4b3JDaExncnByZ3I0SGdycVBn
cjQzZ3JxUGdyNEFLRmVDdW11Q3ZnZUN1cWVDdmplQ3VxZUN1ditDdXJ4STJDQVVTQlhSaFgxTkhH
aXNLRXVDdW11Q3ZnZUN1bytDdmplQ3VvK0N2Z0FvVjRLNmE0SytCNEs2cDRLK040SzZwNEs2LzRL
NnZFaVVJQlJJQ2RXc2FIUW9iMExyUXZ0Q3kwWUxRc05HQzBMZ2cwWUhRdjlDMTBZRFF2TkdERWdZ
SUFCSUNDQUknLCA1LCAwdAAnZW5hYmxlX29wZW5fYWNjZXNzX3BvaW50c19hdF96ZXJvX3N0YXRl
dAA0ZW5hYmxlX29wZW5fYWNjZXNzX3BvaW50c19hdF96ZXJvX3N0YXRlLCBmYWxzZSwgMiwgMHQA
J2VuYWJsZV9tYWtlX2FfZ2lmX3JlZW5jb2RlX3dpdGhfZHJpc2h0aXQAM2VuYWJsZV9tYWtlX2Ff
Z2lmX3JlZW5jb2RlX3dpdGhfZHJpc2h0aSwgdHJ1ZSwgMiwgMHQAJWVuYWJsZV91bml2ZXJzYWxf
bWVkaWFfbW9yZV9lbW9qaV9idG50ADJlbmFibGVfdW5pdmVyc2FsX21lZGlhX21vcmVfZW1vamlf
YnRuLCBmYWxzZSwgMiwgMHQAIGMycV9waWxsX3BvcHVwX21heF9yYXRlX2xpbWl0X21zdAAyYzJx
X3BpbGxfcG9wdXBfbWF4X3JhdGVfbGltaXRfbXMsIDI1OTIwMDAwMDAsIDEsIDB0ACllbW9qaV9z
dXBlcnBhY2tzX21ldGVyZWRfZG93bmxvYWRfZW5hYmxlZHQANWVtb2ppX3N1cGVycGFja3NfbWV0
ZXJlZF9kb3dubG9hZF9lbmFibGVkLCB0cnVlLCAyLCAwdAAYZW5hYmxlX2Zsb2F0aW5nX2tleWJv
YXJkdAAkZW5hYmxlX2Zsb2F0aW5nX2tleWJvYXJkLCB0cnVlLCAyLCAwdAAqZW5hYmxlX2xhdW5j
aF9mZWF0dXJlX29uX29uZV90YXBfdG9fc2VhcmNodAA2ZW5hYmxlX2xhdW5jaF9mZWF0dXJlX29u
X29uZV90YXBfdG9fc2VhcmNoLCB0cnVlLCAyLCAwdAAUbWFrZV9hX2dpZl9mcmFtZXJhdGV0AB5t
YWtlX2FfZ2lmX2ZyYW1lcmF0ZSwgMTUsIDEsIDB0ACZsc3RtX2ZlZGVyYXRlZF90cmFpbmluZ19w
ZXJpb2Rfc2Vjb25kc3QAMmxzdG1fZmVkZXJhdGVkX3RyYWluaW5nX3BlcmlvZF9zZWNvbmRzLCAz
NjAwLCAxLCAwdAAeYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsX2RldACGYzJxX3N1cGVycGFj
a3NfbWFuaWZlc3RfdXJsX2RlLCAnaHR0cHM6Ly93d3cuZ3N0YXRpYy5jb20vYW5kcm9pZC9rZXli
b2FyZC9jb252MnF1ZXJ5L1MvZGUvMjAxODEwMjUyMi9zdXBlcnBhY2tzX21hbmlmZXN0X2RlLnpp
cCcsIDQsIDB0ABpwcmVkaWN0aW9uX2JyYW5jaGluZ19saW1pdHQAI3ByZWRpY3Rpb25fYnJhbmNo
aW5nX2xpbWl0LCAxLCAxLCAwdAAjZW5hYmxlX3Rvb2x0aXBfZm9yX2dsb3dfZ19jYW5kaWRhdGV0
AC9lbmFibGVfdG9vbHRpcF9mb3JfZ2xvd19nX2NhbmRpZGF0ZSwgdHJ1ZSwgMiwgMHQAGWVuYWJs
ZV9tYWdpY19nX3JhdGVfbGltaXR0ACVlbmFibGVfbWFnaWNfZ19yYXRlX2xpbWl0LCB0cnVlLCAy
LCAwdAATdW5pZmllZF9pbWVfdGltZW91dHQAIHVuaWZpZWRfaW1lX3RpbWVvdXQsIDEwMDAwLCAx
LCAwdAAWZW5hYmxlX2pveXN0aWNrX2RlbGV0ZXQAI2VuYWJsZV9qb3lzdGlja19kZWxldGUsIGZh
bHNlLCAyLCAwdAAiY29udGV4dHVhbF9jYW5kaWRhdGVfY2FjaGVfdHRsX3NlY3QAL2NvbnRleHR1
YWxfY2FuZGlkYXRlX2NhY2hlX3R0bF9zZWMsIDE0NDAwLCAxLCAwdAAeYzJxX3N1cGVycGFja3Nf
bWFuaWZlc3RfdXJsX3RhdACGYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsX3RhLCAnaHR0cHM6
Ly93d3cuZ3N0YXRpYy5jb20vYW5kcm9pZC9rZXlib2FyZC9jb252MnF1ZXJ5L1MvdGEvMjAxODEw
MjUyMi9zdXBlcnBhY2tzX21hbmlmZXN0X3RhLnppcCcsIDQsIDB0ABRlbmFibGVfZmVhdHVyZV9j
YXJkc3QAIGVuYWJsZV9mZWF0dXJlX2NhcmRzLCB0cnVlLCAyLCAwdAAmbWFrZV9hX2dpZl9zdXBl
cnBhY2tzX21hbmlmZXN0X3ZlcnNpb250ADBtYWtlX2FfZ2lmX3N1cGVycGFja3NfbWFuaWZlc3Rf
dmVyc2lvbiwgMTMsIDEsIDB0ABxzdXBwb3J0c19iYXR0ZXJ5X3NhdmVyX3RoZW1ldAAoc3VwcG9y
dHNfYmF0dGVyeV9zYXZlcl90aGVtZSwgdHJ1ZSwgMiwgMHQADmVuYWJsZV9tYWdpY19ndAAaZW5h
YmxlX21hZ2ljX2csIHRydWUsIDIsIDB0ABxsc3RtX21vZGVsc19tZXRhZGF0YV92ZXJzaW9udAAl
bHN0bV9tb2RlbHNfbWV0YWRhdGFfdmVyc2lvbiwgOSwgMSwgMHQAJWVuYWJsZV9keW5hbWljX2Nh
bmRpZGF0ZV9wYXJ0aXRpb25pbmd0ADJlbmFibGVfZHluYW1pY19jYW5kaWRhdGVfcGFydGl0aW9u
aW5nLCBmYWxzZSwgMiwgMHQAFmVuYWJsZV9tYWdpY19nX2xvY2FsZXN0ADdlbmFibGVfbWFnaWNf
Z19sb2NhbGVzLCAnZGUsZW4sZXMsZnIsaXQsbXMscHQsdGEnLCA0LCAwdAAlZmVkZXJhdGVkYzJx
X2V4dHJhX2NhbmRpZGF0ZXNfZW5hYmxlZHQAMmZlZGVyYXRlZGMycV9leHRyYV9jYW5kaWRhdGVz
X2VuYWJsZWQsIGZhbHNlLCAyLCAwdAAea2V5X2NvcnJlY3Rpb25fbGFuZ3VhZ2Vfd2VpZ2h0dAAp
a2V5X2NvcnJlY3Rpb25fbGFuZ3VhZ2Vfd2VpZ2h0LCAxLjAsIDMsIDB0ACVjMnFfc3VwZXJwYWNr
c19tYW5pZmVzdF92ZXJzaW9uX3poX2NudAAuYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lv
bl96aF9jbiwgMCwgMSwgMHQAH3BydW5lX3VzZXJfaGlzdG9yeV9ieV90aW1lc3RhbXB0ACtwcnVu
ZV91c2VyX2hpc3RvcnlfYnlfdGltZXN0YW1wLCB0cnVlLCAyLCAwdAAoZmVkZXJhdGVkYzJxX2Nv
bnYyZ2lmX2NhbmRpZGF0ZXNfZW5hYmxlZHQANGZlZGVyYXRlZGMycV9jb252MmdpZl9jYW5kaWRh
dGVzX2VuYWJsZWQsIHRydWUsIDIsIDB0AChlbmFibGVfYXV0b2NvcnJlY3Rpb25fYWRhcHRhdGlv
bl9sb2NhbGVzdABAZW5hYmxlX2F1dG9jb3JyZWN0aW9uX2FkYXB0YXRpb25fbG9jYWxlcywgJ2Fy
LGVuLUdCLGVuLUlOJywgNCwgMHQAHmMycV9zdXBlcnBhY2tzX21hbmlmZXN0X3VybF9wdHQAhmMy
cV9zdXBlcnBhY2tzX21hbmlmZXN0X3VybF9wdCwgJ2h0dHBzOi8vd3d3LmdzdGF0aWMuY29tL2Fu
ZHJvaWQva2V5Ym9hcmQvY29udjJxdWVyeS9TL3B0LzIwMTgxMDI1MjIvc3VwZXJwYWNrc19tYW5p
ZmVzdF9wdC56aXAnLCA0LCAwdAAiYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbl9lbnQA
LGMycV9zdXBlcnBhY2tzX21hbmlmZXN0X3ZlcnNpb25fZW4sIDE1LCAxLCAwdAAlZmVkZXJhdGVk
YzJxX3JhbmtpbmdfdHJhaW5pbmdfZW5hYmxlZHQAMmZlZGVyYXRlZGMycV9yYW5raW5nX3RyYWlu
aW5nX2VuYWJsZWQsIGZhbHNlLCAyLCAwdAAgcHJpbWVzX2Rpcl9zdGF0c19sb2dnaW5nX2VuYWJs
ZWR0AC1wcmltZXNfZGlyX3N0YXRzX2xvZ2dpbmdfZW5hYmxlZCwgZmFsc2UsIDIsIDB0AB5wcmlt
ZXNfbGF0ZW5jeV9sb2dnaW5nX2VuYWJsZWR0ACtwcmltZXNfbGF0ZW5jeV9sb2dnaW5nX2VuYWJs
ZWQsIGZhbHNlLCAyLCAwdAAtZW5hYmxlX2ZhbGxiYWNrX2FydF9jb3JwdXNfdG9fdW5pdmVyc2Fs
X21lZGlhdAA6ZW5hYmxlX2ZhbGxiYWNrX2FydF9jb3JwdXNfdG9fdW5pdmVyc2FsX21lZGlhLCBm
YWxzZSwgMiwgMHQAHnRyYW5zbGF0ZV90YXJnZXRfbGFuZ3VhZ2VfbGlzdHQBaXRyYW5zbGF0ZV90
YXJnZXRfbGFuZ3VhZ2VfbGlzdCwgJ2FmLGFtLGFyLGF6LGJlLGJnLGJuLGJzLGNhLGNlYixjbyxj
cyxjeSxkYSxkZSxlbCxlbixlbyxlcyxldCxldSxmYSxmaSxmaWwsZnIsZnksZ2EsZ2QsZ2wsZ3Us
aGEsaGF3LGhpLGhtbixocixodCxodSxoeSxpZCxpZyxpcyxpdCxpdyxqYSxqdyxrYSxrayxrbSxr
bixrbyxrdSxreSxsYSxsYixsbyxsdCxsdixtZyxtaSxtayxtbCxtbixtcixtcyxtdCxteSxuZSxu
bCxubyxueSxwYSxwbCxwcyxwdCxybyxydSxzZCxzaSxzayxzbCxzbSxzbixzbyxzcSxzcixzdCxz
dSxzdixzdyx0YSx0ZSx0Zyx0aCx0cix1ayx1cix1eix2aSx4aCx5aSx5byx6aC1DTix6aC1UVyx6
dScsIDQsIDB0ACFjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF91cmxfemhfdHd0ACtjMnFfc3VwZXJw
YWNrc19tYW5pZmVzdF91cmxfemhfdHcsICcnLCA0LCAwdAAeZW5hYmxlZF9zdGlja2VyX3NlYXJj
aF9sb2NhbGVzdABuZW5hYmxlZF9zdGlja2VyX3NlYXJjaF9sb2NhbGVzLCAnYXIsZGUsZW4sZXMs
ZnIsaGktTGF0bixpZCxpdCxqYSxrbyxubCxwbCxwdCxydSx0aCx0cix6aC1DTix6aC1ISyx6aC1U
VycsIDQsIDB0ACJjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF92ZXJzaW9uX2VzdAArYzJxX3N1cGVy
cGFja3NfbWFuaWZlc3RfdmVyc2lvbl9lcywgNCwgMSwgMHQAHWVtb2ppX3N1cGVycGFja3NfbWFu
aWZlc3RfdXJsdACGZW1vamlfc3VwZXJwYWNrc19tYW5pZmVzdF91cmwsICdodHRwczovL3d3dy5n
c3RhdGljLmNvbS9hbmRyb2lkL2tleWJvYXJkL21vZGVscGFjay9lbW9qaS8yMDE4MDgzMTE3NTk1
Mi9zdXBlcnBhY2tzX21hbmlmZXN0LnppcCcsIDQsIDB0AC5lbmFibGVfZW1vamlfYXZhdGFyX3N0
aWNrZXJzX25ld19mZWF0dXJlc19jYXJkdAA6ZW5hYmxlX2Vtb2ppX2F2YXRhcl9zdGlja2Vyc19u
ZXdfZmVhdHVyZXNfY2FyZCwgdHJ1ZSwgMiwgMHQAG2VuYWJsZV9mZ19kb3dubG9hZHNfZm9yX2ht
bXQAJ2VuYWJsZV9mZ19kb3dubG9hZHNfZm9yX2htbSwgdHJ1ZSwgMiwgMHQAJ2hhbmR3cml0aW5n
X3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbnQAMGhhbmR3cml0aW5nX3N1cGVycGFja3NfbWFu
aWZlc3RfdmVyc2lvbiwgMywgMSwgMHQAEWVuYWJsZV9tYWtlX2FfZ2lmdAAdZW5hYmxlX21ha2Vf
YV9naWYsIHRydWUsIDIsIDB0ABtlbmFibGVfbWFrZV9hX2dpZl9tZWdhcGFja3N0ACdlbmFibGVf
bWFrZV9hX2dpZl9tZWdhcGFja3MsIHRydWUsIDIsIDB0AB1wcmltZXNfbWVtb3J5X2xvZ2dpbmdf
ZW5hYmxlZHQAKnByaW1lc19tZW1vcnlfbG9nZ2luZ19lbmFibGVkLCBmYWxzZSwgMiwgMHQAGmVu
YWJsZV9tb3JzZV9zd2l0Y2hfYWNjZXNzdAAmZW5hYmxlX21vcnNlX3N3aXRjaF9hY2Nlc3MsIHRy
dWUsIDIsIDB0ABRlbmFibGVfY2hldnJvbl91aV92MnQAIGVuYWJsZV9jaGV2cm9uX3VpX3YyLCB0
cnVlLCAyLCAwdAAhZXhwcmVzc2l2ZV9zdGlja2Vyc19tYXJrZXRfY29uZmlndA02ZXhwcmVzc2l2
ZV9zdGlja2Vyc19tYXJrZXRfY29uZmlnLCAnSWdod1lXTnJjeTh5TkNJSWNHRmphM012TWpVaURI
QmhZMnR6THpJd01EQXdNaUlJY0dGamEzTXZNak1pREhCaFkydHpMekl3TURBd05USU1jR0ZqYTNN
dk5ESTVOams1TWdod1lXTnJjeTh5TkRJSWNHRmphM012TWpVeUNIQmhZMnR6THpJNU1neHdZV05y
Y3k4eU1EQXdNREl5REhCaFkydHpMekl3TURBd016SU1jR0ZqYTNNdk5qQXdNakF4TWd4d1lXTnJj
eTgyTURBeU1ESXlESEJoWTJ0ekx6YzVOakF4TURJTWNHRmphM012TnprMk1ESXdNZ3h3WVdOcmN5
OHlNREF3TURFeURIQmhZMnR6THpJd01EQXdOVElNY0dGamEzTXZOakF3TXpBek1neHdZV05yY3k4
Mk1EQXpNREl5REhCaFkydHpMell3TURNd01USU1jR0ZqYTNNdk5qQXdNekEyTWdod1lXTnJjeTh5
TXpJTWNHRmphM012TWpBd01EQTBNZ2h3WVdOcmN5OHlOeklJY0dGamEzTXZNekF5REhCaFkydHpM
ell3TURFd01USU1jR0ZqYTNNdk5qQXdNVEF6TWd4d1lXTnJjeTgyTURBeE1ESXlDSEJoWTJ0ekx6
STJNZ2h3WVdOcmN5OHpNVElJY0dGamEzTXZNamd5REhCaFkydHpMemM0T1RBd01USU1jR0ZqYTNN
dk9EZ3dPREF6TWd4d1lXTnJjeTgzT1Rrd01qQXlESEJoWTJ0ekx6Y3pNRGN3TWpJTWNHRmphM012
TnpNd056QTBNZ3h3WVdOcmN5ODNPVGt3TXpBeURIQmhZMnR6THpnNE1ESXdNRElNY0dGamEzTXZP
RGd3TVRrNE1neHdZV05yY3k4NE9EQTRNVEF5REhCaFkydHpMemc0TURnd05ESU1jR0ZqYTNNdk1U
QXdNREF5TWd4d1lXTnJjeTh4TURBd01ERXlESEJoWTJ0ekx6ZzRNRGd3TVRJTWNHRmphM012T0Rn
d09EQXlNZ3h3WVdOcmN5ODVPVGt3TVRBeURIQmhZMnR6THpjek1EY3dNeklNY0dGamEzTXZPRGd3
T0RBMU1neHdZV05yY3k4NE9EQTRNRFl5REhCaFkydHpMemc0TURnd09ESU1jR0ZqYTNNdk9EZ3dP
REE1TWd4d1lXTnJjeTg0T0RBNE1EY3lESEJoWTJ0ekx6YzRPVEF3TlRJTWNHRmphM012TnpnNU1E
QTBNZ3h3WVdOcmN5ODNPRGt3TURJeURIQmhZMnR6THpjNE9UQXdNeklNY0dGamEzTXZPRGd3TlRB
eU1neHdZV05yY3k4NE9EQTFNREV5QjNCaFkydHpMemd5REhCaFkydHpMemc0TURFNU5ESU1jR0Zq
YTNNdk56YzNOalkyTWdkd1lXTnJjeTgyTWdkd1lXTnJjeTh4TWdkd1lXTnJjeTh5TWdkd1lXTnJj
eTgwTWdod1lXTnJjeTh4TXpJSWNHRmphM012TVRReUNIQmhZMnR6THpFMU1naHdZV05yY3k4eE5q
SU1jR0ZqYTNNdk9EZ3dNekE0TWd4d1lXTnJjeTg0T0RBeE9UWXlESEJoWTJ0ekx6ZzRNRE13T1RJ
TWNHRmphM012TnpreU1ERXdNZ2h3WVdOcmN5OHhPRElJY0dGamEzTXZNVGt5Q0hCaFkydHpMekl3
TWdod1lXTnJjeTh5TVRJTWNHRmphM012TlRRM05qRTRNZ3h3WVdOcmN5ODJNREU1TkRNeURIQmhZ
MnR6THpZeE16UTJPRElNY0dGamEzTXZOems1TURFd01neHdZV05yY3k4NE9EQTJNREV5REhCaFky
dHpMemc0TURFNU1USU1jR0ZqYTNNdk9EZ3dNVGt5TWd4d1lXTnJjeTg0T0RBeE9Ua3lESEJoWTJ0
ekx6ZzRNREU1TXpJTWNHRmphM012T0Rnd01UazFNZ3h3WVdOcmN5ODRPREF4T1RjeURIQmhZMnR6
THpnNE1ETXdNVElNY0dGamEzTXZPRGd3TXpBeU1neHdZV05yY3k4NE9EQXpNRE15REhCaFkydHpM
emc0TURNd05ESU1jR0ZqYTNNdk9EZ3dNekExTWd4d1lXTnJjeTg0T0RBek1EY3lDSEJoWTJ0ekx6
RXlNZ3h3WVdOcmN5ODRPREEwTURFeUNIQmhZMnR6THpFM01neHdZV05yY3k4NE9EQXlNREl5QjNC
aFkydHpMelV5QjNCaFkydHpMek15QjNCaFkydHpMemt5REhCaFkydHpMemd3TmpJMU9ESUljR0Zq
YTNNdk1qSXlDSEJoWTJ0ekx6RXdNZ2R3WVdOcmN5ODNNZ3h3WVdOcmN5ODVORGM1T1RFeURIQmhZ
MnR6THpjNU16QXhNRElNY0dGamEzTXZOemt6TURJd01neHdZV05yY3k4M09UTXdNekF5REhCaFky
dHpMemM1T1RBMU1ESU1jR0ZqYTNNdk56azVNRFl3TWd4d1lXTnJjeTgzT1Rrd056QXlESEJoWTJ0
ekx6YzVOREF4TURJTWNHRmphM012TnprME1ESXdNZ3h3WVdOcmN5ODNPVFF3TXpBeURIQmhZMnR6
THpjNU1UQXhNRElNY0dGamEzTXZOemt4TURJd01neHdZV05yY3k4M09URXdNekF5REhCaFkydHpM
emMzTnpneE1ESU1jR0ZqYTNNdk56YzNPREl3TWd4d1lXTnJjeTgzTnpjNE16QXlESEJoWTJ0ekx6
YzNOemcwTURJTWNHRmphM012TnpjM09EVXdNZ3h3WVdOcmN5ODNPVFV3TVRBeURIQmhZMnR6THpj
NE9UQXdOaklNY0dGamEzTXZOemMzTnpBeE1neHdZV05yY3k4M056YzNNREl5REhCaFkydHpMemMz
Tnpjd016SU1jR0ZqYTNNdk56YzNOekEwTWd4d1lXTnJjeTgzTnpjM01EVXlESEJoWTJ0ekx6Y3pN
REkyTlRJTWNHRmphM012TnpNd056QXhNZ3h3WVdOcmN5ODNNekExTURFeURIQmhZMnR6THpjek1E
STJNaklNY0dGamEzTXZOek13TWpVMU1neHdZV05yY3k4M016QXlOVEV5REhCaFkydHpMemN6TURJ
MU5qSU1jR0ZqYTNNdk16WTRORGMxTWd4d1lXTnJjeTgzTXpBeU5UUXlESEJoWTJ0ekx6Y3pNREkx
T1RJTWNHRmphM012TnpNd01qVTRNZ3h3WVdOcmN5OHpOamcwTnpNeURIQmhZMnR6THpNMk9EUTNO
RElNY0dGamEzTXZNelk0TkRjeE1neHdZV05yY3k4M016QXlOVE15REhCaFkydHpMemN6TURJMk1U
SU1jR0ZqYTNNdk9UUTJPVGt6TWd4d1lXTnJjeTg1TkRZNU9UVXlESEJoWTJ0ekx6azBOems1TURJ
TWNHRmphM012T1RRNU1UQXpNZ3h3WVdOcmN5ODVORGt4TURReURIQmhZMnR6THprME9URXdOVElN
Y0dGamEzTXZPVFE1TVRBMk1neHdZV05yY3k4NU5Ea3hNVEF5REhCaFkydHpMemswT1RFd01qSU1j
R0ZqYTNNdk9UUTRNREEwTWd4d1lXTnJjeTg1TkRnd01ESXlESEJoWTJ0ekx6azBOams1TWpJTWNH
RmphM012T1RRNU1UQTVNZ3h3WVdOcmN5ODVORGt4TURneURIQmhZMnR6THprME9EQXdNVElNY0dG
amEzTXZPVFE1TVRBM01neHdZV05yY3k4NU5EWTVPVEF5REhCaFkydHpMemswT0RBd016SU1jR0Zq
YTNNdk9UUTVNREF4TWd4d1lXTnJjeTg1TkRZNU9URXlESEJoWTJ0ekx6azBOams1TkRJTWNHRmph
M012T1RRNU1UQXhNZ3h3WVdOcmN5ODVORGt3TURJNkUzQmhZMnR6THpJM0wzTjBhV05yWlhKekx6
TTZHSEJoWTJ0ekx6WXdNREV3TXk5emRHbGphMlZ5Y3k4eE1Eb1hjR0ZqYTNNdk5qQXdNVEF4TDNO
MGFXTnJaWEp6THpFNkZIQmhZMnR6THpNd0wzTjBhV05yWlhKekx6SXhPaFJ3WVdOcmN5OHlPQzl6
ZEdsamEyVnljeTh4TnpvVWNHRmphM012TWpZdmMzUnBZMnRsY25Ndk1UYzZHSEJoWTJ0ekx6SXdN
REF3TkM5emRHbGphMlZ5Y3k4eU1Eb1RjR0ZqYTNNdk1qTXZjM1JwWTJ0bGNuTXZPVG9UY0dGamEz
TXZNamN2YzNScFkydGxjbk12TVRvWGNHRmphM012TmpBd01UQXlMM04wYVdOclpYSnpMelk2R0hC
aFkydHpMell3TURFd015OXpkR2xqYTJWeWN5OHhOam9VY0dGamEzTXZNak12YzNScFkydGxjbk12
TWpNJywgNSwgMHQAKmVuYWJsZV9hdXRvc3BhY2VfYWZ0ZXJfcHVuY3R1YXRpb25fc2V0dGluZ3QA
NmVuYWJsZV9hdXRvc3BhY2VfYWZ0ZXJfcHVuY3R1YXRpb25fc2V0dGluZywgdHJ1ZSwgMiwgMHQA
DGVuYWJsZV96aF90d3QAGGVuYWJsZV96aF90dywgdHJ1ZSwgMiwgMHQAGG1ha2VfYV9naWZfbWF4
X2RpbWVuc2lvbnQAI21ha2VfYV9naWZfbWF4X2RpbWVuc2lvbiwgNDgwLCAxLCAwdAAvc3RpY2tl
cnNfbmV3X3JlbGVhc2VfYmFkZ2VzX3Nob3dfYWZ0ZXJfbnRoX29wZW50ADhzdGlja2Vyc19uZXdf
cmVsZWFzZV9iYWRnZXNfc2hvd19hZnRlcl9udGhfb3BlbiwgMCwgMSwgMHQAG2VuYWJsZV9iaXRt
b2ppX3Byb21vX2Jhbm5lcnQAJ2VuYWJsZV9iaXRtb2ppX3Byb21vX2Jhbm5lciwgdHJ1ZSwgMiwg
MHQAEmVuYWJsZV9lbl91c19tb3JzZXQAHmVuYWJsZV9lbl91c19tb3JzZSwgdHJ1ZSwgMiwgMHQA
IWMycV9zdXBlcnBhY2tzX21hbmlmZXN0X3VybF96aF9jbnQAK2MycV9zdXBlcnBhY2tzX21hbmlm
ZXN0X3VybF96aF9jbiwgJycsIDQsIDB0ABVlbmFibGVfaW5zdGFudF9zZWFyY2h0ACJlbmFibGVf
aW5zdGFudF9zZWFyY2gsIGZhbHNlLCAyLCAwdAAiZW5hYmxlX2ZpbHRlcl9pbWFnZV9zZWFyY2hf
cmVzdWx0c3QALmVuYWJsZV9maWx0ZXJfaW1hZ2Vfc2VhcmNoX3Jlc3VsdHMsIHRydWUsIDIsIDB0
ABhlbmFibGVfaGFuZHdyaXRpbmdfemhfaGt0ACRlbmFibGVfaGFuZHdyaXRpbmdfemhfaGssIHRy
dWUsIDIsIDB0AAxlbmFibGVfemhfY250ABhlbmFibGVfemhfY24sIHRydWUsIDIsIDB0ACtjb250
ZXh0dWFsX3JhdGVfdXNfaW50ZXJ2YWxfcmF0ZV9saW1pdF9kYXlzdAA1Y29udGV4dHVhbF9yYXRl
X3VzX2ludGVydmFsX3JhdGVfbGltaXRfZGF5cywgMzAsIDEsIDB0ACFlbmFibGVfbWFrZV9hX2dp
Zl9sb2FkaW5nX3NwaW5uZXJ0AC1lbmFibGVfbWFrZV9hX2dpZl9sb2FkaW5nX3NwaW5uZXIsIHRy
dWUsIDIsIDB0ACFrZXlfY29ycmVjdGlvbl9zcGVlZF9saW1pdF9taWxsaXN0ACxrZXlfY29ycmVj
dGlvbl9zcGVlZF9saW1pdF9taWxsaXMsIDEwMCwgMSwgMHQAImxpdGVyYWxfc3RhcnRfcGVuYWx0
eV9yZWxhdGl2ZV9tYXh0AC5saXRlcmFsX3N0YXJ0X3BlbmFsdHlfcmVsYXRpdmVfbWF4LCAxLjAy
LCAzLCAwdAAiYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbl90YXQAK2MycV9zdXBlcnBh
Y2tzX21hbmlmZXN0X3ZlcnNpb25fdGEsIDMsIDEsIDB0ABZlbmFibGVfdW5pdmVyc2FsX21lZGlh
dAAiZW5hYmxlX3VuaXZlcnNhbF9tZWRpYSwgdHJ1ZSwgMiwgMHQAIm1ha2VfYV9naWZfc3VwZXJw
YWNrc19tYW5pZmVzdF91cmx0AI1tYWtlX2FfZ2lmX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsLCAn
aHR0cHM6Ly93d3cuZ3N0YXRpYy5jb20vYW5kcm9pZC9rZXlib2FyZC9tb2RlbHBhY2svbWFrZWFn
aWYvMjAxODA5MjcyMTIxL3N1cGVycGFja3NfbWFuaWZlc3QuanNvbicsIDQsIDB0ABltdWx0aXdv
cmRfcHJlZGljdGlvbl9jb3N0dAAkbXVsdGl3b3JkX3ByZWRpY3Rpb25fY29zdCwgMS40LCAzLCAw
dAAiYzJxX3N1cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbl9kZXQAK2MycV9zdXBlcnBhY2tzX21h
bmlmZXN0X3ZlcnNpb25fZGUsIDQsIDEsIDB0AB9lbmFibGVfY29udjJtYWtlYWdpZl9jYW5kaWRh
dGVzdAArZW5hYmxlX2NvbnYybWFrZWFnaWZfY2FuZGlkYXRlcywgdHJ1ZSwgMiwgMHQAGmVuYWJs
ZV9leHByZXNzaXZlX2NvdW50ZXJzdAAmZW5hYmxlX2V4cHJlc3NpdmVfY291bnRlcnMsIHRydWUs
IDIsIDB0ABxjMnFfYXN5bmNocm9ub3VzbHlfdHJpZ2dlcmVkdAApYzJxX2FzeW5jaHJvbm91c2x5
X3RyaWdnZXJlZCwgZmFsc2UsIDIsIDB0ACFlbmFibGVfbWFrZV9hX2dpZl90ZXh0X2Fubm90YXRp
b250AC1lbmFibGVfbWFrZV9hX2dpZl90ZXh0X2Fubm90YXRpb24sIHRydWUsIDIsIDB0AClkZWxp
Z2h0X2xhdGVzdF9vdmVycmlkZXNfbWV0YWRhdGFfdmVyc2lvbnQAM2RlbGlnaHRfbGF0ZXN0X292
ZXJyaWRlc19tZXRhZGF0YV92ZXJzaW9uLCAtMSwgMSwgMHQALWlnbm9yZV93b3JkX3NlcGFyYXRv
cnNfZm9yX3ByZWRpY3Rpb25fY29udGV4dHQAOWlnbm9yZV93b3JkX3NlcGFyYXRvcnNfZm9yX3By
ZWRpY3Rpb25fY29udGV4dCwgdHJ1ZSwgMiwgMHQAK2VuYWJsZV9tYWtlX2FfZ2lmX2Rvd25sb2Fk
X3dpdGhfY29udGVudF9rZXl0ADdlbmFibGVfbWFrZV9hX2dpZl9kb3dubG9hZF93aXRoX2NvbnRl
bnRfa2V5LCB0cnVlLCAyLCAwdAAXZW5hYmxlX2dpZl9hY2Nlc3NfcG9pbnR0ACNlbmFibGVfZ2lm
X2FjY2Vzc19wb2ludCwgdHJ1ZSwgMiwgMHQAF3Rlbm9yX3NhZmVfc2VhcmNoX2xldmVsdAAldGVu
b3Jfc2FmZV9zZWFyY2hfbGV2ZWwsICdtaWxkJywgNCwgMHQAHGRpYWNyaXRpY19jb3N0X3Npbmds
ZV9sZXR0ZXJ0ACdkaWFjcml0aWNfY29zdF9zaW5nbGVfbGV0dGVyLCA2LjAsIDMsIDB0AB9obW1f
c3VwZXJwYWNrc19tYW5pZmVzdF92ZXJzaW9udAAxaG1tX3N1cGVycGFja3NfbWFuaWZlc3RfdmVy
c2lvbiwgMjAxOTAxMDQwMywgMSwgMHQAK2VuYWJsZV9zdWdnZXN0X3JlY2VudF9jbGlja2VkX2My
cV9jYW5kaWRhdGV0ADdlbmFibGVfc3VnZ2VzdF9yZWNlbnRfY2xpY2tlZF9jMnFfY2FuZGlkYXRl
LCB0cnVlLCAyLCAwdAArZmVkZXJhdGVkYzJxX2luZmVyZW5jZV90cmlnZ2VyaW5nX3RocmVzaG9s
ZHQAOGZlZGVyYXRlZGMycV9pbmZlcmVuY2VfdHJpZ2dlcmluZ190aHJlc2hvbGQsIC0xMC4wLCAz
LCAwdAAbZXhwcmVzc2l2ZV9zdGlja2Vyc19hcGlfa2V5dABMZXhwcmVzc2l2ZV9zdGlja2Vyc19h
cGlfa2V5LCAnQUl6YVN5QlBTQUZsdjN6cGdLMWpDSmhsbU53bDlOb0F1aEwtQUtjJywgNCwgMHQA
GGVuYWJsZV9oYW5kd3JpdGluZ196aF9jbnQAJGVuYWJsZV9oYW5kd3JpdGluZ196aF9jbiwgdHJ1
ZSwgMiwgMHQAF2xzdG1fc3VwZXJwYWNrc19lbmFibGVkdAAjbHN0bV9zdXBlcnBhY2tzX2VuYWJs
ZWQsIHRydWUsIDIsIDB0ACVlbmFibGVfdXNlcl9sYW5ndWFnZV9wcm9maWxlc19sb2dnaW5ndAAx
ZW5hYmxlX3VzZXJfbGFuZ3VhZ2VfcHJvZmlsZXNfbG9nZ2luZywgdHJ1ZSwgMiwgMHQAFWxzdG1f
aGlkZV9wcmVkaWN0aW9uc3QAIWxzdG1faGlkZV9wcmVkaWN0aW9ucywgdHJ1ZSwgMiwgMHQAImNv
bnRleHR1YWxfYXBwaW5kZXhpbmdfb2RpX2VuYWJsZWR0AC9jb250ZXh0dWFsX2FwcGluZGV4aW5n
X29kaV9lbmFibGVkLCBmYWxzZSwgMiwgMHQAHGVuYWJsZV96ZXJvX3N0YXRlX2NhbmRpZGF0ZXN0
AChlbmFibGVfemVyb19zdGF0ZV9jYW5kaWRhdGVzLCB0cnVlLCAyLCAwdAAgZW5hYmxlX3JhdGVf
dXNfZnJvbV9pbWFnZV9pbnNlcnR0ACxlbmFibGVfcmF0ZV91c19mcm9tX2ltYWdlX2luc2VydCwg
dHJ1ZSwgMiwgMHQAIGtleV9nYXVzc2lhbl92YXJpYW5jZV9tdWx0aXBsaWVydAAra2V5X2dhdXNz
aWFuX3ZhcmlhbmNlX211bHRpcGxpZXIsIDEuMCwgMywgMHQAH2tleV9jb3JyZWN0aW9uX21heF9z
cGVlZF93ZWlnaHR0ACprZXlfY29ycmVjdGlvbl9tYXhfc3BlZWRfd2VpZ2h0LCAyLjAsIDMsIDB0
AB5jMnFfc3VwZXJwYWNrc19tYW5pZmVzdF91cmxfbXN0AIZjMnFfc3VwZXJwYWNrc19tYW5pZmVz
dF91cmxfbXMsICdodHRwczovL3d3dy5nc3RhdGljLmNvbS9hbmRyb2lkL2tleWJvYXJkL2NvbnYy
cXVlcnkvUy9tcy8yMDE4MTAyNTIyL3N1cGVycGFja3NfbWFuaWZlc3RfbXMuemlwJywgNCwgMHQA
JXJlcXVpcmVfaHR0cHNfdXJsc19pbl9zZWFyY2hfcmVzcG9uc2V0ADJyZXF1aXJlX2h0dHBzX3Vy
bHNfaW5fc2VhcmNoX3Jlc3BvbnNlLCBmYWxzZSwgMiwgMHQAJ2NvbnRleHR1YWxfY2FuZGlkYXRl
X21heF9hZ2VfZm9yX3VpX3NlY3QAM2NvbnRleHR1YWxfY2FuZGlkYXRlX21heF9hZ2VfZm9yX3Vp
X3NlYywgMzYwMCwgMSwgMHQAI2R5bmFtaWNfcmF0ZV9saW1pdF9zY2FsaW5nX3N0cmF0ZWd5dAA4
ZHluYW1pY19yYXRlX2xpbWl0X3NjYWxpbmdfc3RyYXRlZ3ksICdFWFBPTkVOVElBTCcsIDQsIDB0
ACFleHByZXNzaXZlX3N0aWNrZXJzX2dycGNfaG9zdG5hbWV0AERleHByZXNzaXZlX3N0aWNrZXJz
X2dycGNfaG9zdG5hbWUsICdzdGlja2VyLXBhLmdvb2dsZWFwaXMuY29tJywgNCwgMHQADGVuYWJs
ZV96aF9oa3QAGGVuYWJsZV96aF9oaywgdHJ1ZSwgMiwgMHQAIGF2YXRhcl9zdGlja2Vyc19tZXRh
ZGF0YV92ZXJzaW9udAArYXZhdGFyX3N0aWNrZXJzX21ldGFkYXRhX3ZlcnNpb24sICcwJywgNCwg
MHQAIGZlZGVyYXRlZGMycV90cmFpbmluZ19wb3B1bGF0aW9udAA/ZmVkZXJhdGVkYzJxX3RyYWlu
aW5nX3BvcHVsYXRpb24sICdjb252MnF1ZXJ5L3Byb2R1Y3Rpb24nLCA0LCAwdAAsY29udGV4dHVh
bF9hbm5vdGF0b3Jfc3VwZXJwYWNrc19tYW5pZmVzdF91cmx0ALNjb250ZXh0dWFsX2Fubm90YXRv
cl9zdXBlcnBhY2tzX21hbmlmZXN0X3VybCwgJ2h0dHBzOi8vd3d3LmdzdGF0aWMuY29tL2FuZHJv
aWQva2V5Ym9hcmQvbW9kZWxwYWNrL2NvbnRleHR1YWwvY29udGV4dHVhbGtleWJvYXJkLWFubm90
YXRvcnMtc3VwZXJwYWNrcy1tYW5pZmVzdC0yMDE4MDMyMC5qc29uJywgNCwgMHQAGGVuYWJsZV9o
YW5kd3JpdGluZ196aF90d3QAJGVuYWJsZV9oYW5kd3JpdGluZ196aF90dywgdHJ1ZSwgMiwgMHQA
F2F2YXRhcl9zdGlja2Vyc19hcGlfa2V5dABIYXZhdGFyX3N0aWNrZXJzX2FwaV9rZXksICdBSXph
U3lCZXVFa1k4MjV1ajhDSFpTU08wTlU2S2w2N3pqd0hleU0nLCA0LCAwdAAcZW5hYmxlX25hdGl2
ZV9rZXlfY29ycmVjdGlvbnQAKGVuYWJsZV9uYXRpdmVfa2V5X2NvcnJlY3Rpb24sIHRydWUsIDIs
IDB0AB1mZWRlcmF0ZWRjMnFfdHJhaW5pbmdfZW5hYmxlZHQAKmZlZGVyYXRlZGMycV90cmFpbmlu
Z19lbmFibGVkLCBmYWxzZSwgMiwgMHQAEWVuYWJsZV9tb3JzZV9oaW50dAAdZW5hYmxlX21vcnNl
X2hpbnQsIHRydWUsIDIsIDB0ACdjb252MnF1ZXJ5X25ldHdvcmtfc3RhdHVzX2NoZWNrX2VuYWJs
ZWR0ADNjb252MnF1ZXJ5X25ldHdvcmtfc3RhdHVzX2NoZWNrX2VuYWJsZWQsIHRydWUsIDIsIDB0
ABhlbmFibGVfc2hvd19kaXNhYmxlZF9taWN0ACRlbmFibGVfc2hvd19kaXNhYmxlZF9taWMsIHRy
dWUsIDIsIDB0ACVjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF92ZXJzaW9uX3poX3R3dAAuYzJxX3N1
cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbl96aF90dywgMCwgMSwgMHQAG2xzdG1fdHJhaW5pbmdf
cmVxdWlyZXNfaWRsZXQAJ2xzdG1fdHJhaW5pbmdfcmVxdWlyZXNfaWRsZSwgdHJ1ZSwgMiwgMHQA
IGZlZGVyYXRlZGMycV9tb2RlbHNfbWV0YWRhdGFfdXJpdACCZmVkZXJhdGVkYzJxX21vZGVsc19t
ZXRhZGF0YV91cmksICdodHRwczovL3d3dy5nc3RhdGljLmNvbS9hbmRyb2lkL2tleWJvYXJkL21v
ZGVscGFjay9mZWRlcmF0ZWRjMnEvc3VwZXJwYWNrc19tYW5pZmVzdC5qc29uJywgNCwgMHQAHGxz
dG1fdHJhaW5pbmdfcGVyaW9kX3NlY29uZHN0AChsc3RtX3RyYWluaW5nX3BlcmlvZF9zZWNvbmRz
LCAzNjAwLCAxLCAwdAAudXNlX2Vtb2ppX2Zvcl9leHByZXNzaW9uX2NhbmRpZGF0ZV9zb3VyY2Vf
aWNvbnQAO3VzZV9lbW9qaV9mb3JfZXhwcmVzc2lvbl9jYW5kaWRhdGVfc291cmNlX2ljb24sIGZh
bHNlLCAyLCAwdAAmZW5hYmxlX2RlY29kZXJfYWdub3N0aWNfaW5zdGFudF9zZWFyY2h0ADNlbmFi
bGVfZGVjb2Rlcl9hZ25vc3RpY19pbnN0YW50X3NlYXJjaCwgZmFsc2UsIDIsIDB0AB5sb2dfbmV4
dF93b3JkX3ByZWRpY3Rpb25fbWF0Y2h0ACpsb2dfbmV4dF93b3JkX3ByZWRpY3Rpb25fbWF0Y2gs
IHRydWUsIDIsIDB0ACJjMnFfc3VwZXJwYWNrc19tYW5pZmVzdF92ZXJzaW9uX3B0dAArYzJxX3N1
cGVycGFja3NfbWFuaWZlc3RfdmVyc2lvbl9wdCwgNCwgMSwgMHQAFWVuYWJsZV9sb2NhbF9jYXJk
c192MnQAIWVuYWJsZV9sb2NhbF9jYXJkc192MiwgdHJ1ZSwgMiwgMHQAE2MycV9waWxsX3VpX2Vu
YWJsZWR0AB9jMnFfcGlsbF91aV9lbmFibGVkLCB0cnVlLCAyLCAwdAAbaG1tX3N1cGVycGFja3Nf
bWFuaWZlc3RfdXJsdAB5aG1tX3N1cGVycGFja3NfbWFuaWZlc3RfdXJsLCAnaHR0cHM6Ly93d3cu
Z3N0YXRpYy5jb20vYW5kcm9pZC9rZXlib2FyZC9obW1wYWNrLzIwMTkwMTA0MDMvbWV0YWRhdGFf
MjAxOTAxMDQwMy5qc29uJywgNCwgMHQACWVuYWJsZV9rb3QAFWVuYWJsZV9rbywgdHJ1ZSwgMiwg
MHQAHGMycV9waWxsX3BvcHVwX3JhdGVfbGltaXRfbXN0AChjMnFfcGlsbF9wb3B1cF9yYXRlX2xp
bWl0X21zLCAxMDAwLCAxLCAweA==


[Decoder #bf14162]

[CrankDispatcher]
[Ranker]
[RuntimeEngineGraph]

[ced #db83b92]

Active Main LMs
  /data/user/0/com.google.android.inputmethod.latin/files/superpacks/delight/main_en_us_20180802_1
Dynamic LMs
  UNUSED /data/user/0/com.google.android.inputmethod.latin/files/personal/Contacts.dict
  DECODING /data/user/0/com.google.android.inputmethod.latin/files/personal/userhistory/UserHistory.en_US.dict
  DECODING /data/user/0/com.google.android.inputmethod.latin/files/personal/Personal.en_US.dict
  UNUSED /data/user/0/com.google.android.inputmethod.latin/files/personal/Email.dict

[dxj #b70e2f3]

currentExtension = NULL
pendingExtension = NULL
previousExtension = NULL

[erp #f28dbb0]


DevFeatureConfig
  R.bool.c2q_pill_ui_enabled = true
  R.bool.enable_conv2query_for_chevron_ui = true
  R.bool.enable_instant_search = false
  R.bool.enable_magic_g = true
  R.bool.enable_magic_g_candidate_source_icon = true
  R.bool.enable_magic_g_no_query_repetition = true
  R.bool.enable_magic_g_rate_limit = true
  R.bool.enable_sticker_platform = true
  R.bool.sticker_badging_enabled = true
  R.bool.use_emoji_for_expression_candidate_source_icon = false
  R.string.pref_key_enable_one_tap_to_search = true
  isBitmojiInstalled = false
  isNotConfigLite = true
  isRunningInTestHarness = false
  isStickerEnabledByOem = true
  isUserSetupComplete = true
  isUserUnlocked = true

Dumped objects: 14, failures: 0, dead references: 0

Content in directory /data/user/0/com.google.android.inputmethod.latin/files
personal        <dir>
emoji_superpacks_manifest_bundled.zip   386
superpacks      <dir>
crash_detection_local_prefs     <dir>
emoji_search_en_us.zip  94,091
dlam    <dir>
nativecrash     <dir>

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/personal
en_us.20180802.lm.acc   194,720
Personal.en_US.dict     294
blacklist.en_us.list    5
userhistory     <dir>

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/personal/userhistory
UserHistory.en_US.dict  13,696

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks
delight <dir>
manifests       <dir>
bundled_emoji   <dir>
emoji   <dir>
bundled_delight <dir>

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/delight
main_en_us_20180802_1   7,792,964
main_hi_xt_20171012_1   9,304,016

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/manifests
delight-20180903        184,823
emoji-6 <dir>
bundled_delight-20180903        184,823
delight-2019100102      184,823
bundled_emoji-6 <dir>
bundled_emoji-3 <dir>

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/manifests/emoji-6
superpacks_manifest.json        36,048

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/manifests/bundled_emoji-6
superpacks_manifest_bundled.json        304

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/manifests/bundled_emoji-3
superpacks_manifest_bundled.json        304

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/bundled_emoji
442dd7424a2b73ebe817b5223ec48db9        <dir>

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/bundled_emoji/442dd7424a2b73ebe817b5223ec48db9
en      101,504
en.shortcuts    127,210

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/emoji
75f112f3014bde732dc35bcb56c06bd2        <dir>
de96d6a43683ddb4f3bc1b59bcd73bb4        <dir>

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/emoji/75f112f3014bde732dc35bcb56c06bd2
hi-in.shortcuts 212,832
hi-in   107,232

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/emoji/de96d6a43683ddb4f3bc1b59bcd73bb4
en-us.shortcuts 127,210
en-us   91,792

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/superpacks/bundled_delight
main_en_us_20180802_2   7,792,964

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/crash_detection_local_prefs
app_version_name        34
app_version_code        8

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/dlam
dlam_properties.data    6

Content in directory /data/user/0/com.google.android.inputmethod.latin/files/nativecrash
No files found.

Content in directory /data/user/0/com.google.android.inputmethod.latin/cache
No files found.
```
