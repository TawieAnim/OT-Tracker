# OT Tracker Android APK

Mobile OT calculator based on:
- Basic salary: S$2,910
- Weekly hours: 44
- OT multiplier: 1.5x
- OT rate: approximately S$22.89/hour
- Default break: 90 minutes

## Build APK with GitHub Actions
1. Create a GitHub repository.
2. Upload all files/folders from this project.
3. Push to `main` (or `master`).
4. Open the repository's **Actions** tab.
5. Select **Build OT Tracker APK**.
6. Wait for the workflow to finish.
7. Open the completed workflow and download the **OT-Tracker-APK** artifact.
8. Extract it and install `app-debug.apk` on Android.

The app stores OT records locally on the device using browser local storage inside the Android WebView.
