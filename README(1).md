# 🧳 Chemodan — Trip Packing Constructor

A minimalist, offline-first packing list app that lets you build reusable **scenarios** (e.g. "Train", "Tent", "Chargers") and combine them into a checklist for any trip.

No accounts. No backend. No tracking. Just one HTML file.

![App screenshot](screenshot.png)

---

## ✨ Features

- **Scenario builder** — create named packing blocks with custom emoji and items
- **Trip composer** — pick any combination of scenarios per trip
- **Checklist** — tap to check off items with a live progress bar
- **Persistent storage** — all data saved in `localStorage`, survives browser restarts
- **Installable PWA** — add to home screen on iPhone or Android, works like a native app
- **Single file** — everything in one `index.html`, zero dependencies, works offline

---

## 📱 How to install on your phone

### iPhone (Safari)
1. Open `index.html` in Safari
2. Tap the **Share** button (square with arrow)
3. Scroll down → **"Add to Home Screen"**
4. Done — the app icon appears on your home screen

### Android (Chrome)
1. Open `index.html` in Chrome
2. Tap the **three-dot menu** → **"Add to Home Screen"**
3. Done

---

## 🚀 Deploy to the web (optional)

### Option A — GitHub Pages (free, recommended)
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder `/`
4. Your app will be live at `https://yourusername.github.io/chemodan/`

### Option B — Netlify (drag & drop)
1. Go to [netlify.com](https://netlify.com) and sign in
2. Drag the `index.html` file onto the Netlify dashboard
3. Get a live URL instantly (e.g. `https://chemodan.netlify.app`)

### Option C — Vercel
```bash
npm i -g vercel
vercel --prod
```

---

## 🗂️ Project structure

```
chemodan/
├── index.html      # The entire app — HTML + CSS + JS in one file
└── README.md
```

---

## 🛠️ How it works

The app is built with **vanilla HTML, CSS, and JavaScript** — no frameworks, no build tools, no dependencies.

- All scenarios and settings are stored in the browser's `localStorage`
- The UI has 3 tabs: **Scenarios** (create/edit packing blocks), **Trip** (combine scenarios), **Checklist** (track packing progress)
- Items are added via comma or Enter key — chip-style input
- Each scenario has a custom emoji, name, and list of items

---

## 💡 Usage example

Create scenarios once:
- 🚂 **Train** → earplugs, eye mask, spare clothes in a bag, slippers, water bottle
- ⛺ **Tent** → sleeping mat, pillowcase, sleeping bag, headlamp, stakes
- 🔌 **Chargers** → phone charger, watch charger, power bank, adapter
- ✈️ **Flight** → passport, boarding pass, neck pillow, compression socks

Then for each trip — just pick the right combination and get a ready checklist.

---

## 📄 License

MIT — do whatever you want with it.
