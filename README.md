# Arpita Priyadarshini Sahoo — Portfolio Website

A single-file, dependency-free portfolio website (HTML + CSS + JS, no build step).

## How to view it
Just open `index.html` in any browser (double-click it, or drag it into a browser tab).

## Photo status
✅ Already added: profile photo, App Building Onramp, Simulink Onramp, PLC (LinkedIn
Learning), MATLAB Certified, and all 3 achievement photos (DRDO certificate, HAL
certificate, LiFi project build).

⚠️ Still placeholders — you don't have images for these yet:
- Artificial Intelligence — IBM
- Oracle Cloud Infrastructure 2025 — Oracle
- Master PLC Programming — Alison

To add them once you have the certificate images:
1. Drop the image files into `assets/images/` (e.g. `ai_ibm.jpg`, `oci_2025.jpg`,
   `master_plc.jpg`).
2. In `index.html`, find the `CERTS` array in the `<script>` at the bottom and set
   `hasImage:true` for that certificate (it currently reads `hasImage:false`).
3. Or just upload the images to Claude and say "add these certificate images" —
   it'll wire them in for you.

## How to host it (get a real URL)
Any of these work great for a static site like this:
- **Netlify** (drag-and-drop the folder at app.netlify.com/drop)
- **Vercel** (vercel.com — import as a static project)
- **GitHub Pages** (push to a GitHub repo, enable Pages in settings)

Once hosted, keep the same URL forever — put it on your CV, LinkedIn, and email signature.

## Sections included
Landing · About · Work Experience · Education · Projects · Skills · Certifications · Achievements · Contact

## Tech
Vanilla HTML5, CSS3 (custom properties, Grid/Flexbox), vanilla JS (IntersectionObserver, Canvas).
No npm install, no build tools — works standalone in any modern browser.
