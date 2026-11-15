# Chaturanga — Android app

A minimal Android app that opens the Chaturanga chess site full screen.
It is just a WebView wrapper: no extra screens, no ads, no tracking.

- App name: **Chaturanga**
- Package: `com.chaturanga.app`
- Opens: https://suryansh9016-bot.github.io/chaturanga/
- Version: 1.0 (versionCode 1)

## How to build the APK

Push to the `main` branch (or run the workflow by hand from the
Actions tab). GitHub Actions builds the debug APK and uploads it as
the **chaturanga-apk** artifact (kept 30 days).

1. Open the repo on GitHub → **Actions** → **Build APK**.
2. Open the latest run → **Artifacts** → download **chaturanga-apk**.
3. The download is a zip; unzip it to get `app-debug.apk`.

## How to install it on a phone

1. Send `app-debug.apk` to the phone (WhatsApp, USB, Drive, anything).
2. Tap the file. The phone will ask to allow installing from that
   source ("Install unknown apps") — allow it. This is normal for
   apps installed outside the Play Store.
3. Tap **Install**. The Chaturanga icon (black knight) appears on the
   home screen.

## Updates

The app just opens the live site, so new packs, fixes and pieces on
the website show at once — no new APK is needed. A new APK is only
needed if the app itself changes (name, icon, permissions).
