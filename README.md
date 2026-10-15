# 5 Minute Alert (Android)

Har 5 minute pe notification + alarm sound + vibration deta hai.
Phone restart ke baad bhi alerts apne aap dobara shuru ho jaate hain.

## APK banane ke 2 tareeke

### A) GitHub Actions (phone/laptop, kuch install nahi karna)
1. GitHub pe nayi repo banao aur is folder ki saari files push karo (branch `main`).
2. Repo > **Actions** > "Build APK" run hone do (~3-5 min).
3. Run ke andar **Artifacts** se `FiveMinAlert-debug-apk` download karo, zip kholo, `app-debug.apk` install karo.

### B) Android Studio
Folder open karo > **Build > Build APK(s)**. APK `app/build/outputs/apk/debug/app-debug.apk` me milegi.

## Install ke baad
- Notification permission **Allow** karo.
- App kholo > **Alerts shuru karo**.
- Battery optimization settings me app ko **Unrestricted / Not optimized** karo, warna Android alerts late kar sakta hai.
