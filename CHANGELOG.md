# Changelog

Every version of every app, aggregated in one place. Releases are also
published on the GitHub **Releases** page of each module with the APK/installer
attached.

## Jewellery_Suite (Android)

### v1.0.9 — 2026-09-26
- ✨ Pawn slip scanning (on-device OCR) + Google document-scanner capture with
  camera/gallery fallback
- ✨ Book-style customer IDs (A-01 … Z-99 → A-001 …), shown on khata card,
  customer list, pawn loan card and search
- ✨ Pawn Loans: Investment / Interest due / Outstanding + All·Active·Released +
  Gold / Silver / Mixed; ID proof captured on the loan
- ✨ Interest Calculator: Normal & Compound, real-calendar date range, monthly
  or annual rate
- 🔧 Pawn form: customer name, address, mobile no, customer ID; icon-only photo
  buttons; dashboard simplified with no duplicate menu items
- 🐛 Dashboard/drawer open, pawn release, outstanding mismatch, village-tag
  layout and 12.1-months bugs fixed

### v1.0.8 — 2026-09-26
- ✨ Side dashboard (Home button): QR codes → User Details → Languages →
  Notifications → Reminders → Dark mode (Beta) → Settings → Customers → Sync →
  Admin → About App → Help & Support → Logout; profile photo on the Home button
- ✨ Logout moved inside the menu; Admin toggle for delete/release password;
  pawn Release asks password
- ✨ About App (APK size + live app-data size), User Details (photo/phone/email)
- ✨ Core module tiles smaller + uniform; Dark mode tagged Beta
- 🔧 Customers / Sync / Settings move to the side dashboard
- 🐛 Save-with-photo bug, refinance interest fixed; raw deletions now fully
  guarded by the Admin setting

### v1.0.7 — 2026-09-26
- ✨ History module (Khata + Pawn activity & deletions, filters, auto-clear, admin Clear Now)
- ✨ Refinance type in "You Gave" (rolls outstanding → fresh principal + new interest, schedule restarts)
- ✨ Admin-guarded delete for customers & khatas
- 🔧 Outstanding card → 3 sections (Principal | TOTAL PAYABLE | Outstanding)
- 🔧 Schedule tiles: single Due/Paid date, partial-payment green/red split bar, interest-only single tile, REFINANCE divider rows
- 🔧 Long-press ledger tile → Delete
- 🔧 Khata chip shows DUE 15-10-26 for far-future reminders
- 🐛 "Due 1 Day Ago" showing after a reminder was set — fixed
- 🐛 Duplicate due date on schedule tiles — fixed
- 🐛 Home module numbers not refreshing after deletes — fixed

### v1.0.6 — 2026-09-26
- ✨ "Other" type in You Gave (note-only display, no type word)
- 🔧 Ledger note logic (note always shown for every type)

### v1.0.5 — 2026-09-26
- ✨ Profile: heading chips (Rating / Reminder), SMS with pre-filled body
- 🔧 Ledger: two columns, You Gave red / You Got green, note lines
- 🔧 Loan row shows P + I total and is editable
- 🔧 Card: Principal + Interest | Outstanding + paid-of line
- ✨ Payment schedule sheet (weeks, On-time counter, lateness wording)
- ✨ Khata: village strip (Investment / Outstanding / To Collect / Members),
  reminder-driven due wording, home module tiles with Investment + Outstanding

### v1.0.4 — 2026-09-25
- ✨ Ledger daily running balance, customer reminders, WhatsApp logo,
  You-Gave type (principal / late fee / interest), schedule P / I / T strip