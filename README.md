# Daily Khata (Android)

An offline daily expense and deposit tracker in taka. All data stays on your phone.

## Get the APK without Android Studio

1. Create a free account at github.com and make a new repository (private is fine).
2. Upload everything in this folder to it, keeping the folder layout. The hidden `.github` folder must go too. Easiest on a computer: unzip, then drag all the contents into the "Upload files" page.
3. Open the repository's **Actions** tab. The "Build APK" workflow starts by itself. If it does not, choose it and press **Run workflow**.
4. When it shows a green tick (about 3 to 5 minutes), open the run and download **daily-khata-apk** from the Artifacts list. Unzip it to get `app-debug.apk`.
5. Copy `app-debug.apk` to your phone and open it. If Android asks, allow "Install unknown apps" for your file manager or browser.

## Build with Android Studio instead

Open this folder in Android Studio and run the `app` configuration, or use Build > Build APK(s).

## Notes

- Entries are stored inside the app. Uninstalling the app deletes them, so use **Export all as CSV** now and then to keep a copy.
- The page is `app/src/main/assets/index.html`. Edit it to change the app.
- This is a debug-signed APK for personal use. It cannot be published on Google Play as is.
