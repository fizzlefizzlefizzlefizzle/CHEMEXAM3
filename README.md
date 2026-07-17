# CHEM 305 Exam 3 Study App

Interactive study tool for CHEM 305 Exam 3 at Folsom Lake College.  
Covers Chapters 8–10: Solutions, Chemical Reactions, and Acids/Bases.

## Features
- **Flashcards** — 35 cards across all three chapters with chapter filter, shuffle, and progress tracking
- **Topic Explanations** — expandable in-depth breakdowns of every testable concept
- **Practice Exam** — full 30-question MC (hidden until you answer) + 10 FR questions with 4 visual options each and explanations
- **Works offline** — installable as a PWA on your iPhone home screen

---

## How to deploy to GitHub Pages

### First time setup

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** in the top right → **New repository**
3. Name it `chem305` (or anything you want)
4. Set it to **Public**
5. Click **Create repository**

### Upload the files

1. On your new repo page, click **uploading an existing file** (or drag and drop)
2. Upload **all of these files at once**:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `README.md`
3. Scroll down, click **Commit changes**

### Enable GitHub Pages

1. Go to your repo → **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Set branch to **main**, folder to **/ (root)**
5. Click **Save**
6. Wait about 60 seconds, then your app is live at:
   **`https://YOUR-USERNAME.github.io/chem305/`**

---

## How to install on your iPhone

1. Open the live URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

The app will appear on your home screen and works fully offline after the first load.

---

## Updating the app

To make changes, just upload a new `index.html` to your repo (drag and drop → commit). GitHub Pages updates within a minute or two. On your phone, pull down to refresh the page once to pick up the new version.
