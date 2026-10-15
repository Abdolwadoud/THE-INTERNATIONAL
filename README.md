# THE INTERNATIONAL — Android starter

This is **version 0.1 (prototype)**: a responsive, trilingual student learning dashboard. It includes sample course cards, subject filters, local lesson-completion tracking, and basic offline caching. It is not yet a production school platform: real lessons, student accounts, teacher/admin tools, cloud sync, assessments, privacy review, and accessibility/device testing remain future work.

## Preview locally
Open `index.html` in a browser. For service-worker/offline testing, serve this folder over localhost/HTTPS.

## Build an Android debug APK using GitHub Actions (free-tier limits apply)
1. Create a GitHub repository and upload the contents of this folder.
2. The workflow `.github/workflows/android-apk.yml` installs Node/Java/Android SDK, copies the web files to `www`, creates the Capacitor Android project, and builds a debug APK.
3. Open the repository's **Actions** tab, select **Build Android APK**, and run it.
4. When complete, download the `THE-INTERNATIONAL-debug-apk` artifact from that workflow run.
5. Install the APK on your Android device only after checking the build and Android's installation warning.

This creates a **debug APK for testing**, not a Play Store release. Do not put passwords, private student information, or API secrets in this static prototype.
