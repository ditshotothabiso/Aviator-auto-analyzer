# Aviator Auto Analyzer 2.0

Android app project with:
- Accessibility-based automatic reading of visible Aviator round history.
- Automatic local history collection (up to 5,000 rounds).
- Statistical signal engine with recent-window reach rates for 1.5x, 2x, 3x and 5x.
- Floating overlay panel over other apps.
- Manual round entry and local statistics.
- No betting automation and no Betway credentials.

## Install/build
This repository is ready for Android Studio. Open the `AviatorAuto` folder and build `app`.

GitHub Actions is also included. Push the project to GitHub and run **Build APK** under Actions. Download the generated `app-debug.apk` artifact.

## Permissions
Android Accessibility is required to read visible UI text. Overlay permission is required for the floating panel.

## Betway package matching
The reader accepts package names containing `betway`, plus Chrome and Huawei Browser. This avoids relying on a single regional Betway package ID.

## Important limitation
The signal is descriptive/statistical and does not guarantee the next multiplier. It does not place bets.
