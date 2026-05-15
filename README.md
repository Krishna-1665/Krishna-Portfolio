# Krishna Bhardwaj — Personal Portfolio

A clean, dark-themed personal portfolio website built with pure HTML, CSS, and JavaScript. No frameworks or build tools required — just open `index.html` in a browser.

## 📁 File Structure

```
portfolio/
├── index.html       # Main HTML file
├── style.css        # All styles
├── script.js        # Interactivity (nav, scroll reveal, etc.)
├── README.md        # This file
└── assets/          # (Create this folder and add your photo here)
    └── profile.jpg  # Your profile photo
```

## 🚀 Getting Started

1. Unzip the folder
2. Add your profile photo:
   - Create an `assets/` folder inside the portfolio folder
   - Add your photo as `assets/profile.jpg`
   - In `index.html`, replace the `<div class="avatar-placeholder">` block with:
     ```html
     <img src="assets/profile.jpg" alt="Krishna Bhardwaj" />
     ```
3. Open `index.html` in your browser — done!

## 🛠 Customization

- **Name / Bio**: Edit `index.html` directly
- **Colors**: Change `--purple` and `--purple-light` in `style.css` under `:root`
- **Projects**: Add/remove `.proj-card` blocks in the Projects section
- **Skills**: Add/remove `.skill-card` blocks in the Skills section
- **Social links**: Update `href` values in the Hero and Contact sections

## 🌐 Deployment

You can deploy this for free on:
- **Vercel**: Drag and drop the folder at vercel.com
- **Netlify**: Drag and drop at netlify.com
- **GitHub Pages**: Push to a repo and enable Pages in Settings

## ✨ Features

- Responsive (mobile, tablet, desktop)
- Smooth scroll navigation
- Scroll-triggered reveal animations
- Floating avatar with animated ring
- Active nav link highlighting
- Hamburger menu for mobile
- Glow background effects
- Hover interactions on all cards
