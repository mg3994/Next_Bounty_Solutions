# Next_Bounty_Solutions
# TODO Tap
use 
```
adb shell input text "your_email@example.com"
```

# references

>adb shell dumpsys window | findstr /R /C:"mCurrentFocus" /C:"mFocusedApp"
    mFocusedApp=Token{ebcf014 ActivityRecord{3d8ba67 u0 com.google.android.gms/.auth.uiflows.minutemaid.MinuteMaidActivity t158}}
  mCurrentFocus=Window{c6d67c2 u0 com.google.android.gms/com.google.android.gms.auth.uiflows.minutemaid.MinuteMaidActivity}
  mFocusedApp=AppWindowToken{b1080bd token=Token{ebcf014 ActivityRecord{3d8ba67 u0 com.google.android.gms/.auth.uiflows.minutemaid.MinuteMaidActivity t158}}}
