# Vrushank Dhande — Portfolio Website

A personal portfolio website for Vrushank Dhande, Artificial Intelligence Engineer based in Pune, India.

## 🌐 Live Demo

> https://vrushankdhande.github.io/

---

## 📋 Overview

A single-page portfolio built with pure HTML, CSS, and vanilla JavaScript — no frameworks and no build tools. Features a dark theme with a purple/teal accent palette, smooth scroll animations, and a fully responsive layout.

---

## ✨ Features

- **Hero Section** — Introduction with animated status badge, social links, and a live AI bot CTA
- **About** — Background summary with stats (projects, years of experience, etc.)
- **Skills** — Categorized skill tags: ML/AI, Data Engineering, Databases, and Tools
- **Projects** — Featured project card + grid of GitHub projects with language tags and years
- **Writing & AI** — Links to Medium blog and a live Streamlit AI bot
- **Contact** — Email, phone, location, and social media links
- **Animated AI background** — canvas neural network (drifting nodes, cursor-reactive links, travelling data pulses) over a soft aurora and grid; pauses when the tab is hidden and is static with `prefers-reduced-motion`
- **Motion** — hero blur-in, tech marquee, 3D card tilt, magnetic buttons, cursor follower, scroll parallax, text-decode section labels, staggered tag pop-ins (all disabled for `prefers-reduced-motion`)
- **Polish** — floating glass nav with active-section highlight and mobile menu, scroll progress bar, loader and photo skeleton, staggered scroll reveals, count-up stats, card spotlight hover, back-to-top button

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, `clamp()`) |
| Scripting | Vanilla JavaScript (Canvas 2D, Intersection Observer API) |
| Fonts | Google Fonts — Space Grotesk, Inter, JetBrains Mono |

No npm, no bundler, no framework. Just open `index.html` in a browser. The only external dependency is Google Fonts.

---

## 📁 Project Structure

```
vrushankdhande.github.io/
├── index.html    # HTML + CSS + JS
├── photo.jpg     # Hero photo (720px wide, ~75 KB)
└── README.md
```

---

## 🚀 Getting Started

### Local

```bash
# Clone the repository
git clone https://github.com/vrushankdhande/vrushankdhande.github.io.git
cd vrushankdhande.github.io

# Open directly in browser
open index.html
# or
python3 -m http.server 8000   # then visit http://localhost:8000
```

### Deploy to GitHub Pages

1. Push `index.html` and `photo.jpg` to the root of the `vrushankdhande.github.io` repository.
2. Go to **Settings → Pages** and set the source to the `main` branch, root folder.
3. The site is served at `https://vrushankdhande.github.io/`.

### Deploy to Netlify / Vercel

Drag and drop the folder (`index.html` + `photo.jpg`) into the Netlify/Vercel dashboard — done.

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
| Projects | 10+ GitHub projects, incl. the Travel Reimbursement Approval Agent |
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
