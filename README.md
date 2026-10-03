# MCU-APP Android Project

This project is set up as a production-style Android shell for a smart MCU control dashboard.

Included features:
- Android app skeleton with modern Gradle config
- WebView-based interface loaded from local assets
- Dark premium dashboard UI
- Live-style metrics and performance chart
- Interactive buttons for cycle start, diagnostics, and power state
- JavaScript-to-Android bridge for app actions

Project structure:
- `settings.gradle`
- `build.gradle`
- `gradle.properties`
- `app/build.gradle`
- `app/src/main/AndroidManifest.xml`
- `app/src/main/java/com/mcu/union/MainActivity.java`
- `app/src/main/assets/index.html`

Run steps:
1. Open the repo in Android Studio.
2. Let Gradle sync complete.
3. Choose a device or emulator.
4. Press Run.

This app loads `file:///android_asset/index.html` and presents a live MCU dashboard interface.
