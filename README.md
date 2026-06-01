# PrivPocket 🛡️

**Your money. Your device. Nothing leaves it.**

PrivPocket is a 100% offline personal-finance app for Android. All data is
encrypted and stored on-device — no servers, no cloud, no telemetry.

![version](https://img.shields.io/badge/version-5.0-a78bfa)
![platform](https://img.shields.io/badge/Android-8.0%2B-38bdf8)
![offline](https://img.shields.io/badge/offline-100%25-2dd4a0)

## Features
- 📊 Accounts & cards (up to 10), with masked card numbers and biometric reveal
- 💸 Transactions, budgets, and spending analytics
- 🔁 Subscriptions with renewal reminders, provider & card linking
- 🔐 ASOX encryption (AES-256-GCM, Android Keystore) for all data at rest
- 🔑 Mandatory 6-digit PIN + biometrics, **2FA** (authenticator app + passkeys)
- 🌍 English & Serbian (🇷🇸), multi-currency with conversion
- ⭐ PrivPocket Plus+ (offline code redemption; license survives reinstall)
- 🎨 AMOLED-black theme with a clean white-grayish gradient

## Privacy
- Zero network requests for your financial data — everything stays local.
- Encryption key is hardware-backed and destroyed on "Delete all my data".
- The only network call is an optional check for app-update announcements.

## Install
1. Download the latest `app-release.apk` from **Releases**.
2. On your phone, allow "Install unknown apps" for your browser/file manager.
3. Open the APK and install. First sign-up creates your account.

## Tech
Kotlin · Jetpack Compose · Material 3 · Room · DataStore · WorkManager ·
Credential Manager (passkeys) · MVVM + Repository.

## Support
📧 privpocket@gmail.com · [Privacy Policy](privacy-policy) · [Terms of Service](terms-of-service)

---
© PrivPocket. Built offline, on purpose.
