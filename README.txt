BILL SPLITTER - Android project
================================
App name: Bill Splitter   |   Package: com.billsplitter.app   |   Android 10 or newer
The whole app is app/src/main/assets/index.html (same file as Bill_Splitter_v4.html).

OPTION A - Android Studio (on a computer)
1. Unzip, then File > Open and pick the BillSplitter folder. Let Gradle sync.
2. Build > Build Bundle(s) / APK(s) > Build APK(s).
3. The file is at app/build/outputs/apk/debug/app-debug.apk. Send it to your phone and install it
   (allow "install unknown apps" when asked).

OPTION B - Free cloud build with GitHub (no Android Studio)
1. Make a free GitHub account and a new repository.
2. Upload ALL files from this folder, including the hidden .github folder.
3. Open the Actions tab > Build APK > Run workflow. After about 5 minutes, download
   the Bill-Splitter-APK artifact (a zip containing app-debug.apk) and install it.

Notes
- Screenshots and CSV exports are saved into Downloads/Bill Splitter.
- The first screenshot needs internet (it loads a small capture library).
- Your data is stored inside the app on the phone. Uninstalling the app deletes it.
