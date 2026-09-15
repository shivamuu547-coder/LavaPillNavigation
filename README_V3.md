# Lava Pill Navigation V3

Phone-friendly AndroidIDE project.

## Setup
1. Build/install the debug APK.
2. Open the app.
3. Enable **Accessibility Service** for navigation.
4. Enable **Notification Access** for notification reactions.
5. On Android 13+, allow the app's notification permission if requested.

The navigation pill is provided by an AccessibilityService overlay. Closing/minimizing the Activity does not stop the enabled service. Force-stopping the app from Android Settings will stop its services until Android allows/restarts them.

No INTERNET permission is declared.
