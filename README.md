<div align="center">
  <h1>🚀 Zero-CLS 3D Portfolio Boilerplate</h1>
  <p><strong>A 100-Lighthouse-score HTML/CSS boilerplate for WebGL 3D models. Zero Cumulative Layout Shift, Pointer-Events scroll, and enterprise-grade SEO injection.</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/Lighthouse-100%2F100-success?style=for-the-badge&logo=lighthouse" alt="Lighthouse 100">
    <img src="https://img.shields.io/badge/Core_Web_Vitals-Passed-brightgreen?style=for-the-badge" alt="CWV">
    <img src="https://img.shields.io/badge/Vanilla-HTML%2FCSS-orange?style=for-the-badge&logo=html5" alt="HTML/CSS">
  </p>
</div>

---

## 😫 The Pain Point
Are you tired of embedding `<model-viewer>` into your landing pages only to see your Lighthouse score tank to 40? 
Does your 3D portfolio suffer from massive layout shifts (CLS) while assets load? 
Does your drag-to-scroll carousel get stuck on mobile devices?

## 💊 The Solution
This is an **Apple-grade, production-ready boilerplate** designed for 3D Artists, Industrial Designers, and B2B Agencies. We stripped out bloated frameworks (No Tailwind, No Bootstrap) and built a surgical, "Zero-Space" architecture.

### ✨ Core Features
*   **Zero Cumulative Layout Shift (CLS):** Strict aspect-ratio containers ensure your 3D models load without jarring page jumps.
*   **Render-Blocking Immunity:** Scripts are deferred and loaded at `body-end`. Your text and UI load instantly (First Contentful Paint < 0.5s).
*   **Pointer-Events Architecture:** We ditched legacy `scroll-snap-type` and `mouse-events`. Enjoy buttery-smooth drag-to-scroll carousels on both Desktop and Mobile.
*   **B2B SEO Ready:** Includes safe JSON-LD schema injection protocols to prevent inline JavaScript (like particles) from corrupting your Google indexing.

## 🚀 Quick Start
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/zero-cls-3d-portfolio.git
   ```
2. Open `index.html` in your browser. (Note: For local 3D models to load properly, use a local server):
   ```bash
   python -m http.server 8000
   ```
3. Replace the placeholder `.glb` files in the `assets/` directory with your own.

## 🛠 Bonus Tool: `perf_fix.py`
Inside the `scripts/` folder, you will find our custom Python tool. If you modify the HTML and add too many fonts or external APIs, run this script. It will automatically:
- Combine and reduce Font Weights.
- Inject `dns-prefetch` and `preconnect` headers.
- Force `fetchpriority="high"` on your Hero images.

## 💖 Support Open Research
If this boilerplate saved your Lighthouse score or helped your B2B agency close a deal, consider buying me a coffee. It fuels the late-night performance hacking!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/phantrongtan)

## 🧠 Philosophy
> "Work Smart, Not Hard. Use First Principles."

Built by the engineers behind high-conversion B2B 3D platforms. We believe in Vanilla CSS, semantic HTML, and respecting the user's CPU. 

---
<div align="center">
  <i>If this saved your Lighthouse score, drop a ⭐!</i>
</div>
