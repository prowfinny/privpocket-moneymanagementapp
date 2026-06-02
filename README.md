# 🔐 PrivPocket

> *Bank-grade encryption. Zero cloud. Your money, your rules.*

[![Download](https://img.shields.io/badge/⬇_Download_APK-A78BFA?style=for-the-badge)](https://github.com/prowfinny/privapocket-policy/releases/latest)
[![Version](https://img.shields.io/badge/v6.0-38BDF8?style=for-the-badge)](https://github.com/prowfinny/privapocket-policy/releases)
[![Android](https://img.shields.io/badge/Android_8.0+-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://github.com/prowfinny/privapocket-policy/releases/latest)
[![Contact](https://img.shields.io/badge/privpocket@gmail.com-2DD4A0?style=for-the-badge)](mailto:privpocket@gmail.com)

---

PrivPocket is a **100% offline** personal finance app for Android. Every number you enter is encrypted with AES-256-GCM before it touches storage. Nothing is synced, uploaded, or phoned home — not even to us.

---

## Install

> [!IMPORTANT]
> Not on Google Play — enable sideloading first.

**Settings → Apps → [your browser] → Install unknown apps → Allow**

Then [download the latest APK](https://github.com/prowfinny/privapocket-policy/releases/latest), install, and follow the setup wizard:
`Language → Create account → Set PIN → Done`

---

## What it does

**Track money across multiple wallets**
Bank accounts, cash wallets, and cards — each with a custom color. Balances update instantly when you log a transaction.

**Log in 3 taps**
Amount on the haptic numpad → category chip → save. Every button has spring-physics feedback. Transactions take under 5 seconds.

**Bank SMS auto-detection** *(the highlight)*
When your bank sends a payment SMS, PrivPocket intercepts it, extracts the amount and merchant, and **silently adds the transaction** to your default account. A notification fires — tap **Undo** if it got it wrong. Works with closed app.

**Budgets with real feedback**
Set monthly limits per category. The app alerts you at 80% and again when you go over. Animated rings, per-category colors.

**Subscriptions that actually remind you**
2-day renewal reminders, every billing cycle — not just the first one.

**Plus a lot more:**

| Tool | What it does |
|:--|:--|
| 📊 Stats | Category donut · 6-month trend · savings rate · avg/day |
| 💰 Loan tracker | Lent/borrowed with partial repayments and progress bars |
| 🎯 Savings goals | Deadlines + "save X/month to hit it on time" |
| 🧾 Receipt scanner | Snap a receipt → ML Kit OCR → amount pre-filled |
| 💸 Salary estimator | Weekend-adjusted next payday · Plus+ time estimation |
| 🔁 Recurring | Auto-post salary/rent/bills every month |
| 📅 Bill calendar | Month grid of all renewal dates |
| 🤖 Aaron | Offline in-app guide (Alpha) |

---

## Privacy

The server never sees your transactions, balances, categories, or names. Ever.

| Stored on server | Never stored anywhere |
|:--|:--|
| SHA-256 hash of your email | Your transactions |
| Hashed PIN (for reinstall restore) | Your balances |
| Plus+ license status | Your account names |
| — | Your card numbers |

Everything financial is encrypted on-device with ASOX (AES-256-GCM + Android Keystore). Wipe the app and the key is gone — no recovery, no backdoor.

---

## Plus+

One-time **€5** · No subscription · No expiry
