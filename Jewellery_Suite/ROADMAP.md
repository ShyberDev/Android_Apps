# Roadmap / Status

What is **updated (done)** and what is **pending (next versions)**, so nothing
gets forgotten and you can always verify a feature yourself.

Legend: ✅ done — 🔜 planned for next version — ⏳ not started

## ✅ Updated — shipped

| Version | Feature |
|---------|---------|
| 1.0.7 | History module (Khata + Pawn activity/deletions, filters, auto-clear 1/3/6/12 mo, admin Clear Now) |
| 1.0.7 | Refinance type in You Gave (rolls outstanding → principal + new interest, schedule restarts, previous weeks kept) |
| 1.0.7 | Delete customer / khata with admin password (cascades loans + ledger) |
| 1.0.7 | Profile card → Principal | TOTAL PAYABLE | Outstanding + clean paid line |
| 1.0.7 | Schedule: single Due/Paid date, partial-payment green/red split, interest-only single tile, REFINANCE divider rows |
| 1.0.7 | Long-press ledger tile → Delete (no confirm) |
| 1.0.7 | Khata chip shows DUE 15-10-26 for far-future reminders |
| 1.0.6 | "Other" type in You Gave (note-only display) |
| 1.0.5 | Profile header chips + SMS pre-fill, two-column ledger with notes, editable P+I row, schedule sheet, khata village strip + reminder wording, home module investment/outstanding |

## 🔜 Planned — next version (v1.0.8, confirmed scope — awaiting final Go)

- **Drag-to-delete** (instead of tap-to-delete): long-press a tile to lift &
  highlight it, drag across the screen, drop on a bottom trash bin to delete.
  The trash icon buttons on customer / khata rows are replaced by this too
  (admin password still required for customer/khata).
- **Collection date picker**: set the exact receive date when collecting
  (past or future — "he paid next week too"), mini-calendar from the tile,
  drives on-time/late and the payment schedule.
- **Refinance polish**: stronger highlight (rectangle tile) for the refinance
  marker; the edit dialog shows the interest box when you edit a refinance row.
- **Customer ID (khata) — scheme confirmed**: short ID like **A-99** (letter =
  village A…Z, number 1…99 since villages have ≤ ~100 members). Auto-assign
  next free number per village. When a village's numbers are all used:
  **recycle Ids of deleted / absent / inactive customers first**; only if
  nothing is free, widen to three digits **A-001** and continue the sequence.
  Show the ID on the customer profile + khata member card. (Pawn customer ID —
  to be discussed later.)
- **Pawn module 🧭 — shipped inside v1.0.8 (confirmed)**:
  - Tap **Principal** → dialog with two options:
    - **Principal Paying** — borrower pays principal **down** (decreases
      principal + linked interest)
    - **Principal Requesting more** — borrower takes **more** money on the
      item (increases principal)
  - Dialog has **Amount** (e.g. ₹10,000) **+ Interest** boxes.
  - **Principal Paying** creates a **new ledger row** for the item with a
    **selectable date** (today or any exact date — also works if the item was
    released during partial days, so interest recalculates from that date).
  - Plus: **Interest Paid** button (pay accrued interest), **Release** button
    (item handed back), and profile shows every interest-paid / principal /
    release event like the khata ledger.

## ⏳ Pending — later versions

- **Maps (v1.0.9+)**: real Google Maps picker, current location, house-location
  capture on new customer (manual or auto-captured at collection time) —
  needs a Google Maps API key.
- Pawn dashboard tiles (outstanding + active count, Gold/Silver/Mixed, search),
  "Interest Rate X%/Month", released-items list.
- Desktop / iOS / Linux / web builds of the suite.

---

*Why some items wait:* each change is verified on the phone before it ships.
The maps work needs a Google Maps API key (nothing is configured in the repo
yet). The pawn module is big, so we prefer to plan it with you one piece at a
time rather than guess.