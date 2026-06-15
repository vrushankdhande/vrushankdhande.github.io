# Vrushank Dhande — Portfolio Website

A personal portfolio website for Vrushank Dhande, ML Engineer & Data Scientist based in Pune, India.

## 🌐 Live Demo

> Deploy `index.html` to any static hosting service (GitHub Pages, Netlify, Vercel, etc.)

---

## 📋 Overview

A single-page portfolio built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no build tools, no dependencies. Features a dark theme with a purple/teal accent palette, smooth scroll animations, and a fully responsive layout.

---

## ✨ Features

- **Hero Section** — Introduction with animated status badge, social links, and a live AI bot CTA
- **About** — Background summary with stats (projects, years of experience, etc.)
- **Skills** — Categorized skill tags: ML/AI, Data Engineering, Databases, and Tools
- **Projects** — Featured project card + grid of GitHub projects with language tags and years
- **Writing & AI** — Links to Medium blog and a live Streamlit AI bot
- **Contact** — Email, phone, location, and social media links
- **Smooth animations** — Intersection Observer–based fade-in on scroll

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, `clamp()`) |
| Scripting | Vanilla JavaScript (Intersection Observer API) |
| Fonts | Google Fonts — Space Grotesk, Inter |

No npm, no bundler, no framework. Just open `index.html` in a browser.

---

## 📁 Project Structure

```
portfolio/
└── index.html    # Single self-contained file (HTML + CSS + JS)
```

---

## 🚀 Getting Started

### Local

```bash
# Clone the repository
git clone https://github.com/vrushankdhande/portfolio.git
cd portfolio

# Open directly in browser
open index.html
# or
python3 -m http.server 8000   # then visit http://localhost:8000
```

### Deploy to GitHub Pages

1. Push `index.html` to the root of your repository (or a `docs/` folder).
2. Go to **Settings → Pages**.
3. Set the source branch and folder, then save.
4. Your site will be live at `https://vrushankdhande.github.io/<repo-name>/`.

### Deploy to Netlify / Vercel

Drag and drop `index.html` (or the folder) into the Netlify/Vercel dashboard — done.

---

## 🎨 Customization

All design tokens are CSS custom properties defined in `:root`:

```css
:root {
  --bg: #0a0a0f;
  --accent: #6c63ff;
  --teal: #14b8a6;
  --amber: #f59e0b;
  --text: #f1f0ff;
  /* ... */
}
```

Change colors, fonts, or spacing by editing these variables at the top of the `<style>` block.

---

## 📌 Sections & Links

| Section | Description |
|---|---|
| Hero | Intro + social links |
| About | Background, stats |
| Skills | ML, Data, DB, Tools |
| Projects | 10+ GitHub projects |
| Writing & AI | Medium blog + AI bot |
| Contact | Email, phone, socials |

**External links used:**
- GitHub: [github.com/vrushankdhande](https://github.com/vrushankdhande)
- LinkedIn: [linkedin.com/in/vrushankdhande](https://www.linkedin.com/in/vrushankdhande/)
- Medium: [@vrushankdhande](https://medium.com/@vrushankdhande/about)
- AI Bot: [vrushank-bot.streamlit.app](https://vrushank-bot.streamlit.app/)
- Kaggle: [kaggle.com/vrushankdhande](https://www.kaggle.com/vrushankdhande)

---

## 📬 Contact

| | |
|---|---|
| Email | vrushankdhande@gmail.com |
| Phone | +91 89777 07204 |
| Location | Pune, Maharashtra, India |

---

## 📄 License

This project is open source. Feel free to fork and adapt it for your own portfolio.

---

*Designed & built by Vrushank Dhande · Pune, India · 2026*
