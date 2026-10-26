SAFE HELMET Android wrapper project

This Android app opens the live Safe Helmet website:
https://safehelmet-public-2026.web.app

Build an APK:
1. Install Android Studio on Windows.
2. Extract this ZIP.
3. In Android Studio choose Open and select the extracted SafeHelmetAndroid folder.
4. Wait for Gradle sync. If prompted, install Android SDK Platform 35 and Build Tools.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When it finishes, click Locate. The APK is usually app/build/outputs/apk/debug/app-debug.apk.
7. Transfer that APK to your Android phone and install it. You may need to allow installing unknown apps for the app used to open the APK.

This is a simple WebView wrapper, not a native sensor-reading app. It displays the hosted dashboard and requires internet access.
Security note: the dashboard currently has public read access to EMP001. Anyone with the link/app may be able to view that worker's data. Secure the Firebase rules before using real worker data.
