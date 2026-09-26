# Contributing

Thank you for wanting to help with the ShyberDev apps. These few rules keep
every module in the same shape so nothing gets confusing.

## The short version

1. **Pick a module** (`Jewellery_Suite/…`) and open an *Issue* first —
   tell us what you want to change and why.
2. Fork, create a branch from `develop`, make focused commits.
3. Open a *Pull Request* against `develop`. Reference the issue.
4. We review, merge, and ship a version bump + release with a downloadable
   APK/installer.

## Version & release process (what we do on every change)

- Every change to an app bumps the version by **+0.1** (e.g. 1.0.6 → 1.0.7).
- `develop` always carries the newest work; `main` = the latest public release.
- Every release gets:
  - a **semantic tag** `vX.Y.Z`,
  - a **release note** with exactly three headings:
    - ✨ **What's New**
    - 🔧 **Features Added / Modified**
    - 🐛 **Bug Fixes**
  - the built **APK / installer attached** to the release.
- `CHANGELOG.md`, `NEWS.md` and the module's `ROADMAP.md` are updated at the
  same time, so readers always know what is **updated** vs **still pending**.

## Code style

- The apps are **offline-first**: they must work with zero network. Never make
  a server required to read or write local data.
- English UI, Telugu data is fine inside records (names, notes).
- Keep it simple and mobile-friendly — the primary user is a shopkeeper on a
  phone held in one hand.

## Reporting a bug

Include: app version (look in Settings / About, or the version name on the
release), the exact steps, what you expected, and what actually happened.
Screenshots or a short screen recording help a lot.