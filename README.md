# DoodleJumpClone

Jump platforms to reach the top

## 🎮 Game Type
Standalone Android (Java)

## 📦 Package
`com.auroramarket.doodlejump`

## 🏷️ Category
Arcade

## ✨ Features
- Infinite gameplay
- Multiple themes
- Power-ups
- High scores

## 🏗️ Build Instructions


### Android Studio Build
1. Open the project in Android Studio
2. Sync Gradle files
3. Build APK: Build > Build Bundle(s) / APK(s) > Build APK(s)
4. Output: app/build/outputs/apk/


## 📱 Running on Device

1. Enable USB debugging on your Android device
2. Connect device via USB
3. Install the APK or deploy from Unity

## 🔒 License
MIT License - See LICENSE file for details

## 🌐 Domain
https://auroramarket.org

## 🚀 Deployment

### Play Store release
1. Configure app signing in Android Studio/Gradle.
2. Build a signed Android App Bundle (`.aab`).
3. Validate artifacts in `app/build/outputs/`.
4. Upload the signed bundle to Google Play Console.

## 🔐 Environment & Secrets
No runtime environment variables are required.
For CI/CD release automation, store signing credentials in repository secrets (for example: `ANDROID_KEYSTORE_BASE64`, `ANDROID_KEY_ALIAS`, `ANDROID_KEYSTORE_PASSWORD`, `ANDROID_KEY_PASSWORD`).

---

Built with ❤️ by Aurora Rayes LLC
