LEDGER - build your Android app (APK) in the cloud, free
1. github.com -> New repository (name: ledger) -> "uploading an existing file".
2. Upload everything from this folder. If the hidden .github folder won't upload:
   Add file -> Create new file, name it  .github/workflows/build-apk.yml
   and paste the contents of build-apk.yml from this folder.
3. Actions tab -> "Build Ledger APK" -> Run workflow (it also runs on every upload). Wait ~5 minutes.
4. Open the finished run -> Artifacts -> Ledger-APK -> download, unzip -> app-debug.apk
5. Send app-debug.apk to your Android phone, tap it, allow "install unknown apps".
   Open Ledger -> Settings -> Enable notifications.
