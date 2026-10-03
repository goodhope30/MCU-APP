# MCU-APP Android Project

Production-grade Android MCU control dashboard with multi-page navigation.

## Features

### Dashboard Page
- Live system metrics (CPU, Memory, Temperature, Uptime)
- Performance chart with live data
- System status panels
- Runtime details and activity log
- Quick action buttons (Start Cycle, Diagnostics, Power)

### Devices Page
- Connected MCU devices list
- Network status overview
- Device signal strength and IP address
- Real-time online/offline status

### Alerts Page
- System event log
- Priority-based alert display
- Recent notifications and warnings
- Maintenance schedules

### Settings Page
- Device configuration
- Update intervals
- Theme selection
- Network endpoint configuration
- Connection timeout settings
- Save/reset functionality

## Architecture

- `app/build.gradle` - Gradle configuration
- `app/src/main/AndroidManifest.xml` - App manifest
- `app/src/main/java/com/mcu/union/MainActivity.java` - Java activity with WebView bridge
- `app/src/main/assets/index.html` - Multi-page HTML5 dashboard

## Running the App

1. Open in Android Studio
2. Let Gradle sync
3. Select device/emulator
4. Press Run

The app loads a local HTML dashboard with full page navigation, live metrics, and device controls.
