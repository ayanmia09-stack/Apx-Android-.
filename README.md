# APX — Android media player prototype

This is a starter Android Studio project for **APX**, a local-media player prototype with:
- Local video file picker
- Playback via Android's built-in video player view
- A downloads screen placeholder (intentionally does not download arbitrary copyrighted content)
- A plugins screen placeholder for future, trusted extensions

## Build and run
1. Install Android Studio on a computer.
2. Open this folder in Android Studio.
3. Let Gradle sync.
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Install the generated APK on your Android phone.

## Notes
- This is a starter project, not a finished production app.
- Gradle/Android SDK versions may need updating depending on your Android Studio installation.
- The local file picker uses Android's Storage Access Framework, so it does not need broad storage access.
- No third-party plugin code is executed. The Plugins screen is a safe placeholder.
