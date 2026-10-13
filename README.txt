MINISTERYO TRACKER - Android Studio project

This project wraps the current Ministeryo Tracker HTML prototype in an Android WebView app.

HOW TO BUILD AN APK:
1. Install Android Studio on a computer.
2. Open the folder MinisteryoTrackerAndroid in Android Studio.
3. Allow Gradle sync and install the Android SDK platform 35 if prompted.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will show the APK location (usually app/build/outputs/apk/debug/app-debug.apk).
6. Transfer the APK to your Android phone and install it. You may need to allow installation from that file manager.

NOTES:
- This is a project, not a prebuilt APK.
- The app runs the existing HTML file locally; it does not need internet for the core interface.
- Assignments are saved in WebView browser storage on the device. Back up/export data before uninstalling or clearing app storage.
- Printing depends on Android WebView and the phone's print service.
