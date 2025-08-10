# 🏋️ Local Gym Workout Tracker

A **mobile-first**, fully **offline** workout tracker that runs in your browser, saves all data in **localStorage**, and can optionally **sync backups to GitHub**.

> **Note**: This tool was custom-built for my **personal use** by **GPT-5**.  
> Repo is public only because GitHub Pages requires public visibility for free hosting — otherwise it would be private.

---

## 🚀 Features

- **Muscle groups**: Chest, Back, Arms, Shoulders, Legs, Forearms.
- **Per-exercise templates** — add or delete as you wish.
- **Last workout recall** — today’s session is prefilled from your last session in that muscle group.
- **3 sets fixed** (weight & reps) for each exercise.
- **Calendar view** — click a date to see what you did.
- **Add notes** for form cues, tempo, or any reminders.
- **Export / Import JSON** — move data between devices.
- **Optional GitHub Sync** — push and pull backups from a repo file.

---

## 📱 Mobile-first UI

Designed for mobile screens — works perfectly on your phone while training. Also looks sharp on desktop.

---

## 📦 Installation & Hosting

1. **Clone or download** this repo.
2. Keep `index.html` in the root of the repo.
3. **GitHub Pages**:
   - Go to **Settings → Pages**.
   - Set **Branch**: `main` and **Folder**: `/ (root)`.
   - Save → Your site is live in ~1 minute.
4. **Vercel**:
   - Import repo → Framework: *Other* → Root: `/`.
   - Deploy.

---

## 🔄 Moving Data Between Devices

You have two options:

### **Manual method**
- **Export JSON** from the top menu.
- On another device → **Import** the file.

### **GitHub Sync method** (optional, advanced)
1. Click **Settings** in the app.
2. Fill:
   - Owner: your GitHub username.
   - Repo: your repo name.
   - Branch: usually `main`.
   - File path: e.g. `backup.json`.
   - Token: [create a fine-grained personal access token](https://github.com/settings/tokens) with **Contents: Read & Write** for this repo only.
3. Click **Save Settings**.
4. Use **Sync Now** or enable **Auto-sync**.

⚠ **Security**: The token is stored only in your browser’s localStorage and never shared or exported. Do **not** commit your token to the repo.

---

## 🛠 Development

The app is pure **HTML + CSS + JavaScript**:
- No build tools.
- No npm install.
- Open `index.html` directly in your browser to run locally.

---

## 📜 License

MIT License — free to use, modify, and host your own copy.

---

## 💡 Author

Built by **Hilmi** — Web3 builder, productivity enthusiast, and early-rising gym-goer.  
Coded entirely by **GPT-5** for my **personal** gym workout tracking.
