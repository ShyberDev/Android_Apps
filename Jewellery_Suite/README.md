# 💍 Jewellery_Suite

The jeweller's **khata & pawn shop suite** — an offline-first Android app
(Flutter) for keeping loan books, daily collections and pawn records on a
phone. Built for one-handed use by a shopkeeper; works with **no network**.

---

## What it does

| Area | What you can do |
|------|-----------------|
| **Khata (ledger)** | Give money, collect money, daily running balance, notes on every entry |
| **Customers** | Profile per person — rating, reminder chip, call / SMS (pre-filled) / WhatsApp, ID photos |
| **Payment schedule** | Weekly/monthly instalments, On-time counter, due / late wording, partial-payment splits |
| **Refinance** | Roll an outstanding balance into a fresh principal + new interest; schedule restarts from today |
| **Pawn** | Pledged jewellery loans with item details (in this repo's roadmap) |
| **Home** | One-glance dashboard: collected today, pawn outstanding, active khata |
| **History** | Recent activity & deletions for Khata + Pawn, village filters, auto-clear, admin "Clear Now" |

## ⬇️ Install on your phone

> ℹ️ The APK lives on the **primary release repo**
> [ShyberDev/Jew_Pawn-Lending-Suite](https://github.com/ShyberDev/Jew_Pawn-Lending-Suite)
> — this mirror repo keeps the source only (small GitHub footprint).

1. Open the Releases page:
   `https://github.com/ShyberDev/Jew_Pawn-Lending-Suite/releases`
2. Pick the latest version and download the `jewellery_suite_vX.Y.Z.apk` file
   under **Assets**.
3. Open the file on your Android phone; when Android warns about *unknown
   sources*, allow it — this is a normal sideload.
4. Done. Your data stays on the phone.

## 📦 Tech stack

- Flutter (Dart) — Android APK build
- Local SQLite database (offline-first)
- Optional sync to a Frappe backend (can be disabled entirely)

## 🧭 Status — updated vs pending

The live tracker lives in [ROADMAP.md](./ROADMAP.md). Every version bump also
updates `CHANGELOG.md` here and at the repository root.

## 🛠 Building it yourself

From the `mobile/jewellery_suite` folder:

```bash
flutter pub get
flutter build apk --release
# output: build/app/outputs/flutter-apk/app-release.apk
```