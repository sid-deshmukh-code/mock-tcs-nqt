# TCS NQT Full Mock Test 🎯

A free, offline-capable mock test for TCS NQT preparation — 309 PYQ-style questions across 31 topics, with instant explanations and automatic progress saving.

**[▶ Open Mock Test](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)** ← update after hosting

---

## Features

- 309 questions across Quant, Logical Reasoning, Verbal, DSA, Programming, Networking, OS, Databases, Cloud, AI/ML, and more
- Instant one-liner explanations after each answer
- 90-minute countdown timer
- Topic filter — practice one section at a time
- Progress auto-saved to your browser (localStorage) — resume anytime
- Full answer review with section-wise score breakdown
- Works completely offline after first load — no account, no server, no tracking

> **Disclaimer:** This is an unofficial practice resource, not affiliated with or endorsed by Tata Consultancy Services (TCS).

---

## Host on GitHub Pages (Step-by-Step)

### Prerequisites
- A GitHub account — [sign up free](https://github.com/signup)
- The file `tcs_nqt_test.html` downloaded to your computer

---

### Step 1 — Create a new repository

1. Go to [github.com/new](https://github.com/new)
2. Fill in:
   - **Repository name:** `tcs-nqt-mock-test` (or anything you like)
   - **Visibility:** Public ✅ (required for free GitHub Pages)
   - Leave everything else as default
3. Click **Create repository**

---

### Step 2 — Upload the HTML file

1. On your new repo page, click **"uploading an existing file"** (or drag-and-drop)
2. Drag `tcs_nqt_test.html` into the upload area
3. **Important:** Rename it to `index.html` before uploading, OR in the commit screen change the filename to `index.html`
   - GitHub Pages serves `index.html` as the homepage automatically
4. Scroll down, click **Commit changes**

---

### Step 3 — Enable GitHub Pages

1. In your repo, go to **Settings** (top menu)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then refresh — you'll see a green banner:
   > *Your site is live at* `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

---

### Step 4 — Update this README (optional)

Replace the placeholder link at the top of this file with your actual URL.

---

## File Structure

```
your-repo/
├── index.html      ← the entire app (single file, no dependencies)
└── README.md       ← this file
```

Everything is self-contained in one HTML file. No npm, no build step, no backend.

---

## How Progress Saving Works

All data is stored in your **browser's localStorage** — it never leaves your device.

| What is saved | When |
|---|---|
| Question order (shuffled) | On test start |
| Each answer / skip | Immediately after selection |
| Timer (seconds remaining) | Every 30 seconds |
| Current question index | On every navigation |

When you reopen the page, a **Resume Session** prompt appears if a session was in progress. You can resume or discard and start fresh.

To manually clear saved data: click **"Clear saved data"** on the welcome screen.

---

## Sharing

Once live, share the URL directly — anyone can open it and take the test in their own browser. Each person's progress saves to their own device independently.

---

## Topics Covered

| Category | Topics |
|---|---|
| Aptitude | Quantitative, Time & Work, Time & Distance, Probability, Data Interpretation |
| Reasoning | Logical Reasoning, Puzzles & Brain Teasers, Analytical |
| Verbal | Verbal Ability |
| Core CS | Data Structures, Algorithms, Programming Concepts, Advanced Programming |
| Systems | Operating Systems, Networking, Database Management |
| Engineering | Software Engineering, Web Technologies, System Design Basics |
| Emerging Tech | Cloud Computing, Cybersecurity, AI & ML, IoT, Blockchain, DevOps |
| Fundamentals | Computer Fundamentals, General Computer Knowledge |

---

## License

Free to use for personal study. Not for commercial redistribution.
