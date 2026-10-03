# MCU-APP Android Project

This project now includes real hardware control support for Bluetooth Classic serial MCU modules such as HC-05 and HC-06.

## Features
- Android app shell with the dashboard flow
- Bluetooth Classic connection to MCU hardware
- Device pairing list and manual MAC input
- Command actions: START, STATUS, POWER, STOP
- JavaScript-to-Android bridge for hardware control
- Multi-page dashboard: dashboard, hardware, alerts, settings

## Supported hardware
This implementation targets standard Bluetooth serial modules commonly used with Arduino/MCU boards.

Typical connection flow:
1. Pair the MCU module in Android Bluetooth settings.
2. Enter the paired device MAC address in the app.
3. Tap Connect.
4. Use the command buttons to send commands to the MCU device.

## Notes
The exact command protocol depends on your MCU firmware. The app sends ASCII commands like:
- START
- STATUS
- POWER
- STOP

You can adjust the command strings in the app or change the firmware to match your board.

## Run steps
1. Open the repo in Android Studio.
2. Let Gradle sync complete.
3. Select an emulator/device.
4. Press Run.

The app loads a local HTML dashboard and provides real hardware connection controls.
