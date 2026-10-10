JR~XAU Android APK build source

This project packages the existing JR~XAU HTML dashboard inside a simple Android WebView app.
It is NOT an APK yet. The APK is built by the GitHub Actions workflow at .github/workflows/build-apk.yml.

BUILD FROM A PHONE (requires a GitHub account):
1. Create a new GitHub repository named JR-XAU-Android.
2. Upload the contents of this ZIP to the repository root (not the ZIP itself).
3. Open the repository's Actions tab.
4. Select "Build JR~XAU APK" and tap "Run workflow".
5. When complete, open the workflow run and download the "JR-XAU-debug-apk" artifact.
6. Extract the downloaded artifact ZIP; it contains app-debug.apk.
7. Open the APK on Android and allow Chrome/Files to install unknown apps if Android asks.

LIMITATIONS:
- This creates a debug APK for personal testing, not a Play Store release.
- The bundled dashboard's data-feed connection must still be tested on the phone.
- This does not connect to HFM MT5 or verify broker trade outcomes, and does not create a 24/7 hosted backend.
