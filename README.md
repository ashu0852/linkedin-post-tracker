# LinkedIn Daily Post Tracker 📅

> A minimalist, zero-friction daily post tracker for LinkedIn creators and founders.
> Track your 3 daily posts (**8:00 AM · 2:00 PM · 8:00 PM**) in a clean, weekly 7-day row.

🌐 **Live Web App**: [https://ashu0852.github.io/linkedin-post-tracker/](https://ashu0852.github.io/linkedin-post-tracker/)

---

## ✨ Features

- **One Row = Seven Days**: Clean horizontal week row with 7 days (Monday through Sunday) displaying day names, calendar dates, and today's badge.
- **Three Daily Posting Slots**:
  - 🌅 **8:00 AM** (Morning slot)
  - ☀️ **2:00 PM** (Afternoon slot)
  - 🌙 **8:00 PM** (Evening slot)
- **1-Click Circle Toggle**: Just click a circle to mark it selected/posted; click again to unselect. As easy as that.
- **🔥 Posting Streak Counter**: Automatically calculates consecutive days with scheduled/posted content.
- **📊 Real-time Progress**: Live daily (`X / 3`) and weekly (`X / 21`) completion statistics.
- **🔒 100% Private & Client-Side**: All your data is stored locally in your browser (`localStorage`). No tracking, no backend database required, and nothing leaves your device.
- **📁 CSV Export**: Download your posting logs anytime as a CSV spreadsheet.
- **⌨️ Keyboard Shortcuts**:
  - `←` / `→`: Navigate weeks
  - `T`: Jump to Today
  - `1`, `2`, `3`: Quick-toggle today's 8 AM, 2 PM, 8 PM slots
- **🔊 Audio Feedback**: Optional subtle click sound on selection (can be muted).
- **☀️ Clean Light Mode**: Focused, distraction-free aesthetic with LinkedIn blue accents.

---

## 🚀 Getting Started

### Option 1: Use Live in Your Browser (No install needed)
Open **[https://ashu0852.github.io/linkedin-post-tracker/](https://ashu0852.github.io/linkedin-post-tracker/)** on your computer, tablet, or phone. Bookmark it or add to home screen!

### Option 2: Run Locally (Offline)
Clone this repository and double-click `index.html` in any browser:
```bash
git clone https://github.com/ashu0852/linkedin-post-tracker.git
cd linkedin-post-tracker
open index.html
```

Or serve with any static web server:
```bash
npx serve .
# or
python3 -m http.server 3000
```

---

## 🔒 Privacy & Data Storage

- Every user gets a **fresh, clean tracker** automatically.
- Your marks and notes are saved exclusively in your browser's `localStorage`.
- You can clear your data anytime using the **"Clear My Data"** button in the footer.
- You can export a backup of your logs anytime via the **Download CSV** button in the header.

---

## 📄 License

MIT License. Free to use, modify, and distribute.
Created by [Ashutosh Singh](https://github.com/ashu0852).
