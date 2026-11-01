WINTER ARC — ANDROID / GOOGLE PLAY PROJECT

WHAT THIS IS
- Refreshed mobile-first Winter Arc interface in www/index.html.
- Existing workout schedule, exercise how-to guide, weekly stats and local progress storage are retained.
- Capacitor configuration and Android wrapper setup scripts are included.
- This ZIP is source code, NOT a compiled APK/AAB and NOT a published Play Store app.

BUILD THE ANDROID PROJECT
1. Install Node.js (LTS) and Android Studio on a computer.
2. Extract this ZIP and open a terminal in the extracted folder.
3. Run: npm install
4. Run: npx cap add android
5. Run: npx cap sync android
6. Run: npx cap open android
7. In Android Studio, test on a device/emulator. Then use Build > Generate Signed Bundle / APK > Android App Bundle.
8. Follow Google Play Console's current testing, app-content, privacy, target-API and release requirements before submitting.

IMPORTANT PUBLISHING NOTES
- A Google Play developer account and its applicable registration fee are required. Since the app owner is under 18, a parent/guardian should own and manage the account and publishing process.
- Complete the Play Console Data safety form accurately. This version stores progress locally on the device and does not have an account or cloud sync. Review all third-party SDKs before making privacy claims.
- Add a public privacy policy URL if required by the Play Console/app category, and prepare screenshots, app description, icon and feature graphic.
- The included SVG is a design source icon; Android launcher icon assets may need generation/adaptation in Android Studio before release.
- The app has not been security-tested, accessibility-audited, or tested across Android devices. Test before release.

SAFETY
The training content is designed as gradual, age-appropriate general exercise guidance. Keep rest days, avoid max-effort daily testing, stop if pain/dizziness occurs, and ask an adult to check pull-up bar installation. A parent/guardian should review the app before publication.
