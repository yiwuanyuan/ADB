adb shell screencap -p /sdcard/2.png

mCurrentFocus=Window{8d1c881 u0 com.netease.XY2Pocket/com.netease.XY2Pocket.Client}

adb shell am start -n com.netease.XY2Pocket/com.netease.XY2Pocket.Client

adb shell am start -a android.intent.action.MAIN -c android.intent.category.LAUNCHER -n com.netease.XY2Pocket/com.netease.XY2Pocket.Client
