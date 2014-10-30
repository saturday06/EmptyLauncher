# EmptyLauncher

Does android launcher crash randomly and break instrumentation test? Let's use EmptyLauncher.
EmptyLauncher is launcher app consisting of only one empty activity. That's extremely stable and
lightweight!

You can install it from [Google Play](http://google.com) or [apk download](http://github.com)

## Setup

```shellscript
adb shell pm list packages # search default launcher
adb shell pm disable com.android.launcher # disable default launcher
adb install EmptyLauncher.apk # install EmptyLauncher as new default launcher
```

Now your launcher becomes extremely stable and lightweight! Let's start instrumentation test.
