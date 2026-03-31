# A.I. NXTGEN Studio Website

**Exploring the Future of AI, Robotics, XR, and Emerging Technologies**

A 24/7 multidisciplinary research laboratory.

## 🚀 Live Site

→ **https://ainxtgen.github.io**

*(Deploys automatically from the `dev` branch via GitHub Pages)*

---

## 📁 Project Structure

```
ainxtgen-website/
├── _config.yml          # Jekyll config (site name, theme, plugins)
├── _data/
│   └── navigation.yml   # Main navigation menu
├── index.md             # Homepage
├── team/
│   └── team.md          # Team page
├── research/
│   ├── research.md      # Research overview
│   ├── ai.md             # AI vertical
│   ├── bci.md            # BCI vertical
│   ├── robotics.md       # Robotics vertical
│   ├── xr.md             # XR vertical
│   └── solar.md          # Solar vertical
├── publications/
│   └── pubs.md          # Publications page
├── datasets/
│   ├── datasets.md       # Datasets overview
│   ├── benchmarks.md     # AI Benchmarks
│   ├── bci.md           # BCI Datasets
│   └── robotics.md      # Robotics Data
├── contact.md            # Contact page
├── 404.md               # 404 error page
├── Gemfile              # Ruby dependencies
├── css/
│   └── dark-mode.css    # Custom dark mode styles
└── _includes/
    ├── head-custom.html  # Custom head (fonts, dark mode, animations)
    └── footer-custom.html # Custom footer
```

---

## 🛠️ Setup & Deployment

### Option 1: GitHub Pages (Recommended — FREE)

1. **Create a GitHub account** at https://github.com

2. **Create a new repository** named:
   ```
   ainxtgen/ainxtgen.github.io
   ```

3. **Push this codebase** to the `dev` branch:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch dev
   git remote add origin https://github.com/ainxtgen/ainxtgen.github.io.git
   git push -u origin dev
   ```

4. **Enable GitHub Pages:**
   - Go to repository **Settings** → **Pages**
   - Source: select `dev` branch
   - Site will publish to `https://ainxtgen.github.io`

5. **Custom domain (optional):**
   - In Settings → Pages → Custom domain: `ainxtgen.xyz`
   - Add a CNAME record in your DNS pointing `ainxtgen.xyz` → `ainxtgen.github.io`

### Option 2: Local Development

```bash
# Install Ruby + Bundler
gem install bundler

# Clone and install dependencies
cd ainxtgen-website
bundle install

# Run locally
bundle exec jekyll serve --watch

# Visit http://localhost:4000
```

---

## 🎨 Customization

### Update Site Info
Edit `_config.yml`:
- `title` — Your site name
- `email` — Contact email
- `description` — Site tagline

### Update Navigation
Edit `_data/navigation.yml` — add/remove/rename menu items

### Add Team Members
Edit `team/team.md` — add bios, photos, roles

### Add Research Content
Edit pages in `research/` — each markdown file is a research area

### Change Hero Image
Replace `/img/web.gif` (or `hero.gif`) with your own animated or static image

### Update Dark Mode Colors
Edit `css/dark-mode.css` — modify the CSS variables at the top:
```css
:root {
  --dark-bg: #0d0d14;
  --dark-accent: #00b4ff;
  /* etc. */
}
```

---

## 🔧 Theme

Built on **[Bulma Clean Theme](https://github.com/chrisrhymes/bulma-clean-theme)** with:
- Jekyll for static site generation
- GitHub Pages hosting (free)
- Dark mode by default (custom CSS override)
- Responsive/mobile-friendly layout

---

## 📝 Updating Content

All content is in **markdown files** — no code experience needed to edit text.

To update any page, just open the relevant `.md` file and edit the text. Changes go live automatically after pushing to GitHub.

---

## ❓ Need Help?

- Jekyll Docs: https://jekyllrb.com/docs/
- Bulma Clean Theme: https://github.com/chrisrhymes/bulma-clean-theme
- GitHub Pages: https://pages.github.com/

---

*Built with 🤖 by A.I. NXTGEN Studio — 2026*
