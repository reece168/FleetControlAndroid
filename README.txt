FLEET CONTROL ANDROID PROJECT

This is an Android Studio project that packages the Fleet Control HTML app inside a native Android WebView wrapper.

BUILD AN APK
1. Install Android Studio on a PC.
2. Open this FleetControlAndroid folder as a project.
3. Allow Gradle sync and install the Android SDK platform 35 if prompted.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK will normally be at app/build/outputs/apk/debug/app-debug.apk.

NOTES
- This project is source code, not a precompiled APK.
- App data is stored in the WebView/browser local storage on that device. Export a backup before uninstalling or clearing app data.
- CSV import/export depends on browser file picker support in Android WebView and should be tested on the target device.
