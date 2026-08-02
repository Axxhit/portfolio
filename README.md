# Akshit Mundra — Portfolio

A Kinetic Glassmorphic single-page portfolio built with pure HTML, CSS, and JavaScript. No frameworks, no build tools — just open and deploy.

## 🚀 Deploy to GitHub Pages

### Option 1: GitHub UI (Easiest)

1. Create a new repository on GitHub (e.g., `portfolio` or `akshit-mundra.github.io`)
2. Push all files to the `main` branch:
   ```bash
   cd portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/Axxhit/<repo-name>.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source** → Select `main` branch → Save
4. Your site will be live at `https://axxhit.github.io/<repo-name>/`

### Option 2: Custom Domain (username.github.io)

1. Name your repo `Axxhit.github.io`
2. Push files to `main`
3. Site auto-deploys at `https://axxhit.github.io`

## 📋 Setup Formspree Contact Form

1. Go to [formspree.io](https://formspree.io) and sign up
2. Create a new form and copy the form ID (e.g., `xyzabcde`)
3. In `index.html`, replace `YOUR_FORM_ID` in the form action URL:
   ```html
   <form action="https://formspree.io/f/xyzabcde" method="POST">
   ```
4. Deploy and test

## 📁 File Structure

```
portfolio/
├── index.html          # Single-page HTML
├── style.css           # Design system & styles
├── script.js           # Animations & interactions
├── Akshit_AI_26.pdf    # Downloadable resume
├── WhatsApp Image...   # Profile photo
└── README.md           # This file
```

## ✨ Features

- 🌌 Interactive particle constellation with mouse tracking
- ⌨️ Typewriter hero text cycling through roles
- 🔮 Glassmorphic frosted cards with 3D tilt effect
- 📊 Animated skill progress bars on scroll
- ⏰ Glowing vertical experience timeline
- 🎨 Ambient gradient mesh blobs with parallax
- 📱 Fully responsive with mobile hamburger menu
- 📬 Formspree-powered contact form
- 🚀 Zero dependencies — deploys anywhere

## License

MIT
