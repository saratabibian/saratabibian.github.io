[README.md](https://github.com/user-attachments/files/26229318/README.md)
# Urban Planner Portfolio

Personal portfolio website for Alex Morgan — Urban Planner.

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in
2. Click **"New repository"** (top-right `+` button)
3. Name it exactly: `yourusername.github.io`  
   *(replace `yourusername` with your actual GitHub username)*
4. Set it to **Public**
5. Click **"Create repository"**

### Step 2 — Upload your files

**Option A — Upload via browser (easiest):**
1. On your new repository page, click **"uploading an existing file"**
2. Drag and drop `index.html` into the upload area
3. Scroll down and click **"Commit changes"**

**Option B — Via Git CLI:**
```bash
git init
git add index.html
git commit -m "Initial portfolio"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings → Pages**
2. Under **"Source"**, select **"Deploy from a branch"**
3. Choose branch: `main`, folder: `/ (root)`
4. Click **Save**

### Step 4 — Your site is live! 🎉

Visit: `https://yourusername.github.io` (takes ~2 minutes to go live)

---

## ✏️ Personalizing the site

Open `index.html` and find these sections to update:

| What to change | Search for |
|---|---|
| Your name | `Alex Morgan` |
| Your tagline | `Shaping cities, one block at a time` |
| Bio text | `I'm an urban planner with over a decade` |
| Stats (years, projects) | `12+`, `34`, `8`, `2.4M` |
| Projects | `project-card` blocks (6 total) |
| Skills | `skill-item` spans |
| Blog posts | `blog-card` blocks |
| Email & links | `alex@example.com`, LinkedIn/GitHub URLs |
| Location coordinates | `40.7128° N, 74.0060° W` |

---

## 🎨 Design features

- Dark mode with city-grid background
- Animated city map SVG in the hero
- Custom cursor with hover effects
- Scroll-triggered fade-in animations
- Fully responsive (mobile-friendly)
- No dependencies — pure HTML/CSS/JS

---

## 📁 File structure

```
yourusername.github.io/
└── index.html       ← everything lives here (single file)
```

To add more pages later (e.g. a full blog), create additional `.html` files and link to them.
