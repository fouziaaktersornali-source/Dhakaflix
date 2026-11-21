1. Android Studio (Koala or newer) > Open > select this folder > wait for Gradle sync.
2. Edit app/src/main/java/com/dhakaflix/app/Config.kt : add category folder URLs, optional TMDB key.
3. Connect phone (same Wi-Fi as server) > Run. Or Build > Build APK(s).

APK without a PC: create a GitHub repo, upload all these files (keep the .github folder),
open Actions > Build APK > Run workflow, then download "DhakaFlix-APK" artifact when it finishes.
