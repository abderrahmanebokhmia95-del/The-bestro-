# THE BISTRO — Android APK

This project is prepared to wrap the React app as a native Android app using Capacitor.

## Build locally

```bash
npm install
npm run android:add
npm run android:build
```

The APK will be at:

`android/app/build/outputs/apk/debug/app-debug.apk`

## Build without a PC using GitHub Actions

1. Create a GitHub repository.
2. Upload this project.
3. Open **Actions** → **Build THE BISTRO APK**.
4. Run the workflow.
5. Open the completed workflow and download the artifact **THE-BISTRO-debug-apk**.
6. Extract the ZIP and install `app-debug.apk` on Android.

Capacitor is the native wrapper used here; the web app itself remains React/Vite.
