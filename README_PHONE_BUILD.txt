Build APK from phone with GitHub Actions
========================================

1. Unzip this project.
2. Upload the folder to a GitHub repository from your phone browser.
3. Commit the file `.github/workflows/build-apk.yml`.
4. Open the repository tab **Actions** and wait for the workflow to finish.
5. Download the APK from **Artifacts**.

The app builds as a debug APK at:
`app/build/outputs/apk/debug/app-debug.apk`


If your GitHub Actions build failed before, replace the project files with this fixed version.
This version patches a likely Android compile issue and accepts Android SDK licenses in the workflow.
