Excel Offline APK project

This project wraps your provided Excel V6 HTML file in an Android WebView. The HTML is bundled inside the APK; no internet permission is requested. JavaScript and DOM storage are enabled so the spreadsheet's formulas and localStorage-based autosave can run offline. CSV, JSON and XLSX exports are routed to Downloads/Excel Offline on Android.

Build using GitHub Actions from a phone:
1. Extract this ZIP.
2. Create a new GitHub repository from github.com in your phone browser.
3. Upload all extracted files and folders (including the hidden .github folder) to the repository root, on branch main.
4. Open the repository's Actions tab and run "Build Excel Offline APK" (or wait for the push build).
5. Open the successful run, find Artifacts, and download Excel-Offline-APK.
6. Extract the downloaded artifact ZIP; install app-debug.apk. Android may ask you to allow installs from that browser/file manager.

Notes: This is an unsigned debug APK for personal testing. The HTML app's own features/formula coverage remain those of the supplied HTML file; this wrapper does not make it fully equivalent to Microsoft Excel. Keep backups using Export Workbook / Save .xlsx.
