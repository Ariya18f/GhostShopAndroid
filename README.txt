GHOST SHOP - Android Studio / GitHub Actions project

This is a native Android WebView wrapper around the Ghost Shop prototype (local HTML assets).

=== Fastest way to get an installable APK (recommended) ===
1. Create a new public or private repository on GitHub.
2. Upload the contents of this GhostShopAndroid folder (keep the folder structure, branch = main).
3. Go to the Actions tab → select "Build Ghost Shop APK" → Run workflow.
4. When it finishes, download the Artifact named Ghost-Shop-APK.
5. Extract it → you will find app-debug.apk → install on your phone.

=== Alternative: Build with Android Studio ===
1. Install Android Studio.
2. Open this folder as a project.
3. Let Gradle sync (it will download SDK Platform 35 if needed).
4. Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Find the APK at: app/build/outputs/apk/debug/app-debug.apk

Notes:
- This is a debug APK (fine for personal testing).
- The shop is a frontend prototype only. Real payment, backend, order delivery and admin panel are not implemented yet.
