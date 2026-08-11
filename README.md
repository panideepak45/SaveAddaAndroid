# Save Adda Android + AdMob

This Android project opens https://saveadda.in/ in a WebView and includes
Google Mobile Ads SDK support.

IMPORTANT:
- The project currently contains Google's official TEST AdMob App ID and TEST banner ad unit ID.
- Do NOT publish with test IDs.
- Before release, replace the test App ID in AndroidManifest.xml with your real
  AdMob App ID and replace the test banner ID in MainActivity.kt with your real
  AdMob banner ad unit ID.
- Create the app and ad units in Google AdMob first.
- Follow Google's current consent/privacy requirements for users in applicable regions.

Build:
1. Open this folder in Android Studio.
2. Sync Gradle.
3. Build > Build APK(s).

The existing website remains responsible for the Save Adda downloader functionality.
