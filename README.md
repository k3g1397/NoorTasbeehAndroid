# Noor Tasbeeh — Android Studio project

This is a starter Android app project that wraps the Noor Tasbeeh UI in an Android WebView. It includes local saved settings/counts, personal target controls in Settings, a notification bridge for target completion, and vibration support.

## Build an APK in Android Studio

1. Install the latest stable Android Studio.
2. Extract this ZIP.
3. In Android Studio choose **Open** and select the `NoorTasbeehAndroid` folder.
4. Allow Gradle sync and install any requested Android SDK platform (compile SDK 35).
5. Connect an Android phone with USB debugging enabled, or use an emulator, then press **Run** to test.
6. To create an installable APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**. Android Studio shows the output path when finished.
7. To publish on Google Play: use **Build > Generate Signed Bundle / APK > Android App Bundle**, create and safely back up your upload key, then upload the signed `.aab` in Google Play Console.

## Before publishing

- Test on a real phone, especially target completion, vibration, reset confirmation, and notification permission.
- Add your own launcher icon, store screenshots, privacy policy, and support email.
- Review the current Google Play policy and target API requirements before release.
- The package name is `com.noortasbeeh.app`; changing it later can complicate publishing.
- This is a starter project, not a store-approved release. Android Studio/Gradle must build it and Google must review it before public listing.
