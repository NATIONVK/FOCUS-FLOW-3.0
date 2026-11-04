# FOCUS FLOW 3.0

A privacy-first, offline-capable study timer and progress tracker.

**Built by NATIONVK · YEASIEN AHMED**

## Features
- Timestamp-based focus timer with pause, resume and save-on-exit.
- Minimal fullscreen timer with animated black-hole particle field.
- Subject management with colours, icons and persistent session history.
- Dashboard, daily/weekly/monthly statistics and subject breakdown.
- Study history with CSV export.
- Tasks, daily study goal and private notes.
- JSON backup and restore.
- Local-first storage; no account or server required.
- Android APK build through GitHub Actions using Capacitor.

## Build APK
1. Open **Actions** in this repository.
2. Select **FOCUS FLOW Android APK**.
3. Select **Run workflow** (or wait for a push to main).
4. Open the successful run and download **FOCUS-FLOW-3.0-APK** from Artifacts.

The generated APK is a debug build for testing and direct installation. A release build requires signing configuration.

## Local development
```bash
npm install
npm run dev
```

## Data & privacy
Study records are stored in this device's browser/app local storage. Export a JSON backup before clearing app data or uninstalling.
