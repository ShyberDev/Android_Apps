# App changelog — Jewellery_Suite (mirrors the releases page)

See the aggregated [CHANGELOG](../CHANGELOG.md) and the Releases page
(`https://github.com/ShyberDev/Android_Apps/releases`) for the same history
with APK downloads.

## v1.0.9 (2026-09-26)
- ✨ Scan the pawn slip (New Pawn Loan) — on-device OCR fills ID Number, Customer
  Name, Item, Loan amount, Date, Item details, Address; Google document scanner
  capture (auto edge crop / straighten, like Drive) with camera fallback
- ✨ Book-style customer IDs: A-01 … A-99, B-01 … Z-99, then A-001 … Z-999
- ✨ Pawn Loans: Investment / Interest due / Outstanding strip, All·Active·Released
  tabs, Gold / Silver / Mixed filters
- ✨ Interest Calculator: Normal + Compound, From→To calendar on the real
  calendar (12 months, not 12.1), Monthly or Annually rate
- ✨ ID proof (type, number, front/back) captured on the pawn loan
- 🔧 New Pawn Loan form: Customer Name / Address / Mobile no / Customer ID; photo
  buttons are camera + gallery symbols only
- 🔧 Dashboard simplified: Payments → General → System → Logout; no duplicate
  entries between the dashboard and Settings
- 🔧 Dark mode surfaces applied app-wide (still Beta)
- 🐛 Side dashboard never opened (tap did nothing) — fixed
- 🐛 Pawn release did nothing after the admin password — fixed
- 🐛 Outstanding no longer disagrees with the Pawn Dashboard total receivable
- 🐛 Khata list no longer squeezes the village name with a location tag

## v1.0.8 (2026-09-26)
- ✨ Side dashboard (Home button): QR codes → User Details → Languages →
  Notifications → Reminders → Dark mode (Beta) → Settings → Customers → Sync →
  Admin → About App → Help & Support → Logout; profile photo on the Home button
- ✨ Logout moved inside the menu (top-right logout icon removed)
- ✨ Admin setting: toggle password for delete / release (khata, customer, pawn
  loan deletes + pawn Release); default On
- ✨ Pawn Release now asks for confirmation + admin password
- ✨ About phone → About App: app name, APK size, live app-data size, Policies /
  Licences / Privacy / Feedback / Terms list
- ✨ User Details: your photo, name, phone, email (photo shows on Home button)
- ✨ Core module tiles smaller + all the same size (logo + name only)
- ✨ Dark mode tagged Beta (not applied everywhere yet)
- 🔧 Customers / Sync / Settings live in the side dashboard; More keeps Reports,
  History, Interest Calculator, Settings
- 🐛 Save-with-photo pawn bug fixed; refinance edit interest kept; khata delete
  frees customer IDs; admin confirmation can be disabled

## v1.0.7 (2026-09-26)
- ✨ History module, Refinance type, admin-guarded customer/khata delete
- 🔧 Profile card 3 sections, schedule tiles (single date, partial split,
  interest-only, REFINANCE dividers), long-press delete, khata DUE-date chip
- 🐛 Stale "Due X Days Ago" chip, duplicate schedule dates, stale home numbers

## v1.0.6 (2026-09-26)
- ✨ "Other" type in You Gave; ledger note rules

## v1.0.5 (2026-09-26)
- ✨ Profile chips + SMS pre-fill, two-column ledger + notes, schedule sheet,
  khata village strip + reminder wording, home module values

## v1.0.4 (2026-09-25)
- ✨ Daily ledger balance, reminders, WhatsApp logo, You-Gave types, schedule strip