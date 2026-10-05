# Notification Storage

Saves every notification your phone receives into a local database (Room) and lets you
search and filter them. Nothing leaves the device.

## Build
1. Open this folder in Android Studio (Ladybug or newer) and let Gradle sync.
2. Run on a device or emulator (Android 8.0+).
3. On first launch tap "Grant access" and enable Notification Storage.
   Sideloaded builds on Android 13+: App info > ⋮ > Allow restricted settings first.

## Features
- Captures title, text, app, category, channel and time
- Search + time range (24h / 7d / 30d) + per-app filter
- Delete one, delete per app, or delete everything
- Optional: save ongoing notifications (menu, off by default)
- Nothing-style UI: black/white, red accent, dot-matrix counter, mono type
