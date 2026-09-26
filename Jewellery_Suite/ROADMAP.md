# Roadmap / Status

What is **updated (done)** and what is **pending (next versions)**, so nothing
gets forgotten and you can always verify a feature yourself.

Legend: ✅ done — 🔜 planned for next version — ⏳ not started

## ✅ Updated — shipped

| Version | Feature |
|---------|---------|
| 1.0.8 (built) | Drag-to-delete everywhere (khata, members, pawn loans, pawn items, pawn ledger); bin hidden until you drag |
| 1.0.9 (built) | Pawn slip scan (on-device OCR) + Google document scanner capture; book-style customer IDs (A-01 … Z-99 → A-001 …) |
| 1.0.9 (built) | Pawn Loans: Investment / Interest due / Outstanding, All·Active·Released, Gold / Silver / Mixed; ID proof on the loan |
| 1.0.9 (built) | Interest Calculator: Normal + Compound, real-calendar From→To, monthly/annual rate |
| 1.0.8 (built) | Settings (More → Settings) — Zoom / smart fit (80–150% + auto), Dark mode, QR codes (gallery + swipe), Interest Calculator |
| 1.0.8 (built) | Pawn New Loan — "+" to add a customer with full ID-proof fields; photo-save bug fixed |
| 1.0.8 (built) | Customer ID — numeric book sequence (type 5102 → next 5103…; blank continues; editable; IDs reused after delete) |
| 1.0.7 | History module (Khata + Pawn activity/deletions, filters, auto-clear 1/3/6/12 mo, admin Clear Now) |
| 1.0.7 | Refinance type in You Gave (rolls outstanding → principal + new interest, schedule restarts, previous weeks kept) |
| 1.0.7 | Delete customer / khata with admin password (cascades loans + ledger) |
| 1.0.7 | Profile card → Principal | TOTAL PAYABLE | Outstanding + clean paid line |
| 1.0.7 | Schedule: single Due/Paid date, partial-payment green/red split, interest-only single tile, REFINANCE divider rows |
| 1.0.7 | Long-press ledger tile → Delete (no confirm) |
| 1.0.7 | Khata chip shows DUE 15-10-26 for far-future reminders |
| 1.0.6 | "Other" type in You Gave (note-only display) |
| 1.0.5 | Profile header chips + SMS pre-fill, two-column ledger with notes, editable P+I row, schedule sheet, khata village strip + reminder wording, home module investment/outstanding |

## ✅ v1.0.8 — released (2026-09-26)

- **Drag-to-delete** everywhere (replaces tap/long-press delete; the trash bin is
  fully hidden during normal use and appears only while a drag starts). Admin
  password still required for khata / member / pawn-loan deletes.
- **Collection date picker**: exact receive date (past or future), drives
  on-time/late and the payment schedule; same picker on edit.
- **Refinance polish**: full gold rectangle tile + edit dialog shows Amount and
  New Interest boxes.
- **Customer ID — numeric book sequence**: enter a start number (e.g. 5102) and
  every following customer auto-continues (5103…); blank continues the previous
  sequence; deleted IDs are reused; IDs are editable. Shown on the profile +
  khata member card.
- **Pawn module (revised)**: **Amount Paying** / **Amount Requesting** buttons
  (interest-first on paying, auto `Released` at ₹0 balance), **Interest Paid**
  + **Release**; every action writes a ledger row with entered + effective
  dates; profile shows every event. **Drag-to-delete** on pawn loans, pawn
  items (loan totals recompute) and ledger entries (effect is undone).
- **Pawn New Loan "+"** → full customer form (photo, ID proof type/number/
  front/back) without leaving the pawn screen; photo-save bug fixed.
- **Home desk simplified**: core modules = logo + name only ("Pawns", not
  "Active pawns"); KPI strip + tiles sized so big phone fonts don't overflow.
- **Settings** (More → Settings): **Zoom / smart fit** (slider + preview,
  works alongside big phone display/font settings without overflow), **Dark
  mode**, **QR codes** (bank/UPI, swipe between like PhonePe), and the full
  settings list (unbuilt entries → "Coming in a later release").
- **Home menu (top-left)**: Logout, Customers, Settings, QR codes, Appearance,
  About phone, Help & support, Languages, Notifications, Reminders, Theme,
  Biometric & screen lock, Change password.
- **More → Interest Calculator** utility.

## ⏳ Pending — later versions

- **Maps (v1.0.9+)**: real Google Maps picker, current location, house-location
  capture on new customer (manual or auto-captured at collection time) —
  needs a Google Maps API key.
- Pawn dashboard tiles (outstanding + active count, Gold/Silver/Mixed, search),
  "Interest Rate X%/Month", released-items list.
- Jewellery module itself (items entries + their drag-delete).
- QR-code UPI payment flow (click-to-pay / bank-details auto-fill).
- Push notifications / reminders engine.
- Desktop / iOS / Linux / web builds of the suite.

---

*Why some items wait:* each change is verified on the phone before it ships.
The maps work needs a Google Maps API key (nothing is configured in the repo
yet). The pawn module is big, so we prefer to plan it with you one piece at a
time rather than guess.