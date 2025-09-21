# ⚡YB Watch World ⚡

> *A sleek, modern landing page for exploring premium analog & digital watches.*

---

## 🔥 Project Overview

**YB Watch World** is a responsive single-page website (HTML + CSS + minimal JS) built to showcase curated watch collections — analog, digital, and luxury timepieces. The site provides a clean product layout, hover animations, a responsive hamburger menu for mobile, a contact form, and social links.

**Purpose / Uddeshya (Hindi):**
Is website ka maqsad users ko watches ke baare mein jankari dena, unke collections dikhana aur interested visitors se contact collect karna hai. Ye demo landing page shop-style presentation ke liye bana hai.

---

## ✨ Key Features

* Responsive navigation with a hamburger menu for small screens (JS toggles menu + icon).
* Hero image and CTA button (`Shop Now`).
* Multiple collection sections: Luxury, Analog, Digital — each with image gallery and feature cards.
* Elegant hover effects (scale, glow, underline animations) for images, headings and buttons.
* Contact form (front-end only) with stylish rounded inputs and focus glow.
* Social links bar with animated hover states.
* Subtle background image reveal on About section (`.me:hover`).

---

## 📂 Suggested File / Folder Structure

```
YB-Watch-World/
├─ index.html               # The HTML you provided
├─ css/
│  └─ style.css            # The CSS you provided (or embedded)            
├─ assets/
│  ├─ images/               # All image files (omega.jpg, rolex.webp, etc.)
│  └─ logo/ybbb.png
├─ thankyou.html            # Simple confirmation page (form target)
└─ README.md                # This document
```

> Tip: Keep your image files optimized (webp / compressed jpg) inside `assets/images/` and reference them with correct relative paths.

---

## ⚙️ How to run (Local)

1. Clone or copy the project folder to your machine.
2. Open `index.html` in any modern browser (Chrome, Edge, Firefox). No server required for static HTML/CSS/JS.
3. For development, open browser DevTools (F12) and use the mobile device toolbar to preview responsiveness.

If you later convert this to a hosted site, upload the folder to any static hosting (GitHub Pages, Netlify, Vercel).

---

## 🛠️ Customization Ideas

* Replace placeholder images in `assets/images/` with high-quality product photos.
* Hook the contact form to a backend (Node / PHP / Formspree) to collect messages.
* Add product detail modals or a lightweight product carousel.
* Integrate a filter or category tabs for watch types (Analog / Digital / Luxury).
* Add simple animations using `@keyframes` or small libraries (AOS) for scroll reveal.

---

## ✅ Accessibility & Responsiveness Notes

* Nav items switch to a fixed, slide-in menu under 768px width.
* Ensure images include meaningful `alt` attributes (already present for watch images).
* Use readable color contrasts for text on dark backgrounds (gold on black is used here). If you need WCAG-perfect contrast, consider slightly brighter text or subtle background overlays.

---

## 🧾 Code Highlights

* `nav` JS: toggles `right` CSS property and swaps FontAwesome classes between `fa-bars` and `fa-times`.
* `.me::before` technique: preloads a background image and fades it in on hover for the About section.
* Responsive layout uses `@media (max-width: 800px)`/`768px` to stack gallery items.

---

## 📸 Screenshots (recommended)

Include screenshots in `assets/screenshots/` such as:

* `desktop-home.png`
* `mobile-menu.png`
* `about-hover.png`

Add them to the repo and reference them in the README using `![alt text](assets/screenshots/desktop-home.png)`.

---

## ✍️ About & Credits

**Project name:** YB Watch World
**Made by:** YASHU
**Contact:** +91 95608 46824 • [yashuu19@gmail.com](mailto:yashuu19@gmail.com)

**Description (short):** YB Watch World is a showcase landing page to explore and learn about watches — designed with a dark, elegant theme and gold accents.

---

## 📜 License

This project is released by Yashu — feel free to reuse and modify the code (attribution appreciated).

---

## 🔁 Next steps I can do for you (choose any)

* Convert this to a GitHub-ready repository with `.gitignore`, `LICENSE`, and ready-to-publish structure.
* Make the contact form functional (example Node.js or Formspree integration).
* Convert the site into a responsive React component or a small Flask app.
* Optimize CSS (extract repeated rules, reduce specificity) and compress images.

---


