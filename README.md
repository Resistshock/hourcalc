# ResistCalc Android

Offline Android application wrapping the bundled HTML calculator in Android WebView.

## Features
- Time intervals across multiple days, displayed correctly as days + hours + minutes.
- Persistent history using WebView DOM storage (`localStorage`).
- Reopen and delete individual measurements; clear all history.
- Export/import history as JSON.
- No network permission; app works offline.

## Build APK
Requirements: Android Studio (or JDK 17+, Android SDK Platform 35, Build Tools, Gradle 8.9+).

Open this folder in Android Studio, allow Gradle sync, then select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

Or from this directory run:

```bash
gradle assembleDebug
```

APK output:
`app/build/outputs/apk/debug/app-debug.apk`

Application ID: `com.resistcalc.app`
Version: `1.0` (versionCode 1)
