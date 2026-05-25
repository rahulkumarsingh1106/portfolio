# Rahul Kumar Singh — Portfolio Website

A two-page dark-themed B2B marketing portfolio.

## 📁 File Structure

```
/
├── index.html          ← Landing / Home page (upload this as the main page)
├── experience.html     ← Full experience & portfolio page
├── css/
│   ├── index.css       ← Styles for index.html
│   └── style.css       ← Styles for experience.html
├── js/
│   ├── index.js        ← JS for index.html
│   └── main.js         ← JS for experience.html
├── assets/
│   └── rahul.png       ← Profile photo
└── README.md

```

## 🚀 Deploy to GitHub Pages

### Step 1 — Create Repository
1. Go to **github.com** → Sign in → Click **+** → **New repository**
2. Name it: `yourusername.github.io`
3. Set to **Public** → Click **Create repository**

### Step 2 — Upload Files
1. In your new repo, click **Add file → Upload files**
2. Upload ALL files maintaining the folder structure above
3. Make sure `index.html` is at the **root level** (not inside a subfolder)
4. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **root**
4. Click **Save**

### Step 4 — Done!
Your site goes live at: `https://yourusername.github.io`

## 🔗 Page Flow
- **index.html** → Landing page (hero, about, highlights, competencies, impact, contact)
- **experience.html** → Full career experience & portfolio (opened via "View Experience In Detail" CTAs)
- Both pages link back to each other

## ✏️ Quick Edits
- Update contact details in `index.html` (search for `singh91.rahulkumar@gmail.com`)
- Update the LinkedIn URL (search for `singhkumarrahul`)
- Swap photo: replace `assets/rahul.png` with your updated photo (same filename)
- Colors: defined as CSS variables at the top of each CSS file
