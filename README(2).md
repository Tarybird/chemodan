# 🧳 Chemodan — Trip Packing Constructor

A minimalist offline-first packing list app. Build reusable **scenarios** (e.g. "Train", "Tent", "Chargers") and combine them into a checklist for any trip. Syncs across all your devices via Firebase.

---

## ✨ Features

- **Scenario builder** — create named packing blocks with custom emoji and items
- **Trip composer** — pick any combination of scenarios per trip
- **Checklist** — tap to check off items with a live progress bar
- **Google sign-in** — each user has their own private data
- **Firebase sync** — scenarios available on all your devices instantly
- **Offline mode** — works without internet, syncs automatically when back online
- **Installable PWA** — add to home screen on iPhone or Android
- **Single file** — everything in one `index.html`, zero build tools

---

## 📱 Install on your phone

**iPhone (Safari):** Share button → "Add to Home Screen"

**Android (Chrome):** Three-dot menu → "Add to Home Screen"

---

## 🚀 Live app

**[tarybird.github.io/chemodan](https://tarybird.github.io/chemodan/)**

Sign in with Google — your data is private and synced across devices.

---

## 🛠️ Tech stack

| What | How |
|------|-----|
| UI | Vanilla HTML + CSS + JS |
| Font | Manrope (Google Fonts) |
| Database | Firebase Firestore |
| Auth | Firebase Authentication (Google) |
| Offline | IndexedDB persistence |
| Hosting | GitHub Pages |

---

## 💡 How it works

Create scenarios once:
- 🚂 **Train** → earplugs, eye mask, spare clothes in a bag, slippers
- ⛺ **Tent** → sleeping mat, pillowcase, sleeping bag, headlamp
- 🔌 **Chargers** → phone charger, watch charger, power bank, adapter
- ✈️ **Flight** → passport, boarding pass, neck pillow

Then for each trip — pick the right combination and get a ready checklist.

---

## 📄 License

MIT
