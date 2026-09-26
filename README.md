# 🗂️ Android_Apps — ShyberDev

The home for every app we build. Each app lives in its own **module folder**
here — Android, iOS, desktop, Linux or web — so it is easy to browse, easy to
contribute to, and never confused with the Frappe/ERPNext codebase.

> We build **offline-first** tools for small shops: fast, simple, and it works
> even without mobile network.

---

## 🎯 Goal

One tidy place where **anyone** (collaborators, anonymous visitors, pull
request reviewers) can understand:

1. **What** each app does and who it is for.
2. **What is done** and **what is still pending** (so nothing gets lost).
3. **How** to download the latest app (APK / installer).
4. **How** changes are made and released (consistent process, per version).

## 📁 Repository structure

```
Android_Apps/
├── README.md                    ← you are here
├── CHANGELOG.md                 ← what changed in every app, every version
├── NEWS.md                      ← short announcements per release
├── CONTRIBUTING.md              ← the process: branches, versions, releases, PRs
└── Jewellery_Suite/             ← App #1 — the jeweller's shop suite
    ├── README.md                ← about the app + how to install it
    ├── CHANGELOG.md             ← version history for this app
    ├── ROADMAP.md               ← updated features vs pending features
    └── mobile/                  ← the Flutter app source
```

## 🧩 Modules

| Module | Status | Platform | Latest release |
|--------|--------|----------|----------------|
| [Jewellery_Suite](./Jewellery_Suite) | ✅ Active | Android (Flutter) | [v1.0.7](https://github.com/ShyberDev/Android_Apps/releases) |
| *(future: desktop / iOS / Linux / web apps…)* | ⏳ Planned | — | — |

New apps are added as new folders here as we build them.

## ⬇️ How to download an app (APK guide)

1. Open the **Releases** page of the module’s repo (or the tag listed above).
2. Expand the version you want (the latest is usually at the top).
3. Under **Assets**, tap the `.apk` file (e.g. `jewellery_suite_v1.0.7.apk`).
4. On Android, confirm *"Allow installing from unknown sources / this app"*
   when asked — this is a normal sideload.
5. Open the installed app. That’s it — no account, no network needed.

Release notes are always grouped under three headings so it is easy to scan:

- ✨ **What's New** — new features
- 🔧 **Features Added / Modified** — improvements to existing features
- 🐛 **Bug Fixes** — what was fixed

## 🧭 How we work

- One app = one module folder.
- Every change ships as a **version bump (vX.Y.Z)** with a **release + APK**.
- Changes land on the `develop` branch first; `main` always matches the latest
  public release.
- All data stays **on the phone** (offline-first). Sync is optional and does
  not require our servers.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full process.

## 📰 News

Short release announcements live in [NEWS.md](./NEWS.md).