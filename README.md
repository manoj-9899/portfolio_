# Developer Portfolio Website

A clean, modern, high-performance portfolio website built with HTML5, Tailwind CSS, and vanilla JavaScript. 

---

## 🚀 How to Run the Website

Run the following command in your terminal:

```bash
npm start
```
or directly with Node:
```bash
node server.js
```
or with Python:
```bash
python3 -m http.server 3000
```

Open your browser and navigate to:
**[http://localhost:3000](http://localhost:3000)**

---

## 📝 How to Update Your Details in `index.html`

All content is cleanly organized in `index.html` with section comment headers:

### 1. Your Name & Title
- Search for `Austin Serb` in `index.html` and replace with your name.
- Update the `<title>` tag in `<head>`.
- In the **Hero Section**, update your location badge (`Seattle, WA`), headline, and pitch paragraph.

### 2. Social Links & Email
- Search for `austin@serbyte.net` and replace with your email address.
- In both the **About Section**, **Contact Section**, and **Footer**, update links to:
  - GitHub (`https://github.com/...`)
  - LinkedIn (`https://www.linkedin.com/in/...`)
  - X / Twitter (`https://x.com/...`)
  - Facebook (`https://www.facebook.com/...`)

### 3. Projects
- In the **Featured Projects Section** (`#projects-grid`), each project card has:
  - **Category / Badge:** (e.g., `Zero Re-Render State Library`)
  - **Title:** (e.g., `React-Zero-UI`)
  - **Action Link:** (e.g., GitHub URL or live demo link)
  - **Thumbnail Image:** Placed in `assets/images/` and referenced via `src="assets/images/..."`

### 4. Photos & Profile Images
Replace the images in `assets/images/` with your own:
- `assets/images/profile.webp` — Main portrait photo
- `assets/images/founder.jpg` — Small avatar in the hero button
- `assets/images/signature.png` — Signature image in the about section
- `assets/images/react-zero-ui.jpg`, `bespoke.webp`, `automedics.webp`, `iao.webp` — Project thumbnails

### 5. Tech Stack & Services
- In the **Technologies Section** (`#technologies`), you can customize the 10 tech stack icons and tooltips.
- Update the 6 capability badges (Full Stack Development, UI/UX Design, etc.).

---

## 📁 File Structure

```
├── index.html            # Main webpage (clean, formatted, and easily editable)
├── server.js             # Zero-dependency local web server (Node.js)
├── package.json          # npm start / dev scripts
├── custom-icons.svg      # SVG icon sprite sheet
├── icons.svg             # Additional SVG icons (mail, arrow)
├── favicon.ico           # Website favicon
├── README.md             # Guide to editing and running
└── assets/
    ├── css/
    │   └── style.css     # Tailwind CSS & design tokens
    ├── js/
    │   └── main.js       # Navbar, mobile menu, scroll & card animations
    ├── fonts/
    │   └── Switzer_Variable.woff2 # Switzer variable font
    └── images/
        ├── profile.webp
        ├── founder.jpg
        ├── signature.png
        ├── framer-noise.png
        ├── react-zero-ui.jpg
        ├── bespoke.webp
        ├── automedics.webp
        └── iao.webp
```
# portfolio_
