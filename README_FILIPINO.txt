AI Pocket Assistant — Android Studio project
Target: Android 13 compatible (min SDK 23, compile SDK 35)
Branding caption: “AI creating by Ryan”
Includes Shizuku API/provider integration:
- Checks whether Shizuku server is running
- Requests user-granted Shizuku permission
- Phone Fix / MLBB / Research & Build starter UI

Important:
- This ZIP is Android source code, NOT a compiled APK.
- It is not yet connected to an online AI model.
- Shizuku permission does not grant root and does not automatically fix the phone or play MLBB.
- Build using Android Studio with Android SDK 35 and JDK 17:
  Open this folder as a project, allow Gradle sync, then Build > Build APK(s).
- Expected output: app/build/outputs/apk/debug/app-debug.apk
