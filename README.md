# Jesse Mulure — Portfolio Website

A dark luxury editorial portfolio website with smooth animations, scroll reveals, and a custom cursor.

## Files
- `index.html` — Main HTML structure
- `styles.css` — All styles and animations

---

## 🚀 Hosting on Netlify (Recommended — Free & Professional)

Netlify is the best choice for a portfolio: instant HTTPS, fast CDN, easy custom domain, and a clean shareable URL like `jessemulure.netlify.app`.

### Method A — Drag & Drop (Fastest, no account needed)
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag your **entire project folder** onto the page
3. Netlify gives you a live URL instantly
4. Click **"Claim your site"** to save and customise the URL

### Method B — GitHub + Netlify (Best for ongoing updates)
1. Create a free account at [https://github.com](https://github.com)
2. Create a new repository (e.g. `jesse-portfolio`)
3. Upload both `index.html` and `styles.css`
4. Go to [https://netlify.com](https://netlify.com) → Sign Up with GitHub
5. Click **"Add new site" → "Import an existing project"**
6. Select your GitHub repository
7. Click **Deploy** — done!

Every time you push changes to GitHub, Netlify auto-deploys them.

### Custom Domain on Netlify
- In your Netlify dashboard → **Domain Settings**
- Add your custom domain (e.g. `jessemulure.com`)
- Netlify provides free SSL automatically

---

## 🐙 Hosting on GitHub Pages (Also free)

1. Create a GitHub repository named exactly: `yourusername.github.io`
   (e.g. `jessemulure.github.io`)
2. Upload `index.html` and `styles.css` to the repository
3. Go to **Settings → Pages → Source → main branch**
4. Your site is live at `https://jessemulure.github.io`

**Netlify is recommended** over GitHub Pages because it's faster, looks more professional, and easier to set up a custom domain.

---

## ✏️ Customisation Tips

### Add Your Photo
In `index.html`, find the `about-placeholder` div and replace it:
```html
<!-- Replace this: -->
<div class="about-placeholder">...</div>

<!-- With this: -->
<img src="your-photo.jpg" alt="Jesse Mulure" style="width:100%;height:100%;object-fit:cover;" />
```

### Add Real Portfolio Images
Each `.portfolio-item` has a coloured gradient background. Replace with your actual work screenshots by adding an `<img>` tag inside `.portfolio-item-inner`.

### Change Contact Links
Update the email, website URL, and social links in the Contact and Footer sections.

### Update Skills
Adjust the `--pct` values in the Skills section to match your actual proficiency levels.

---

## 📱 Responsive
The site is fully mobile-responsive with a hamburger navigation menu for small screens.

---

Built with pure HTML, CSS & Vanilla JS. No frameworks. No dependencies.
