# Hilary Klein — Artist Portfolio Website

A personal portfolio website for Hilary Klein, acrylic painter based in Silver City, New Mexico.  
The site showcases her psychedelic Southwest wildlife paintings with a full-screen hero, clickable lightbox gallery, and contact footer.

---

## Files Included

| File | Description |
|------|-------------|
| `hilary-klein.html` | Main website — single file, fully self-contained |
| `painting1.jpg` | Bumblebee Heart |
| `painting2.jpg` | Coyote & Swallowtail |
| `painting3.jpg` | Jackrabbit & Marigolds |
| `robots.txt` | Blocks AI crawlers and image scrapers |
| `README.md` | This file |

---

## Features

- **Full-width hero** — Coyote painting fills the entire screen with slow zoom animation and elegant typography
- **About section** — Artist statement rooted in Silver City and the Gila wilderness
- **Mosaic gallery** — Three paintings displayed in a varied grid layout
- **Lightbox** — Click any painting to open it full screen. Navigate with arrow buttons or keyboard arrow keys. Close with Escape or the X button
- **Responsive design** — Works on desktop, tablet, and mobile
- **Footer** — Contact section with email link
- **robots.txt** — Blocks known AI training crawlers including GPTBot, CCBot, Amazonbot, Bytespider and many others

---

## Color Palette

Colors are pulled directly from Hilary's paintings:

| Name | Hex | Used For |
|------|-----|----------|
| Midnight Purple | `#1E0A2E` | Primary background |
| Deep Purple | `#2D1248` | Secondary background |
| Gold | `#F5C400` | Accents, borders, highlights |
| Cyan | `#00D4C8` | Secondary accent, links |
| Cream | `#FDF6E8` | Body text |

---

## Typography

- **Cormorant Garamond** — Display headings, italic accents (via Google Fonts)
- **Cinzel** — Section labels, navigation logo (via Google Fonts)
- **Lato Light** — Body text, navigation links (via Google Fonts)

---

## How to Add More Paintings

1. Copy your image file into the same folder as `hilary-klein.html`
2. Find the `<div class="mosaic">` section in the HTML
3. Copy an existing tile block and paste it inside the mosaic div
4. Update the `data-src`, `data-title`, `src`, `alt`, and label text to match your new painting
5. Update the `data-index` number to the next sequential number

Example tile block:
```html
<div class="tile" data-src="your-painting.jpg" data-title="Painting Title" data-index="3">
  <img src="your-painting.jpg" alt="Painting Title — Hilary Klein">
  <div class="tile-overlay">
    <div class="tile-info">
      <span class="tile-name">Painting Title</span>
      <span class="tile-meta">Acrylic on Canvas</span>
    </div>
  </div>
  <div class="tile-zoom">⊕</div>
</div>
```

---

## How to Update Your Email Address

Find this line in the footer section of `hilary-klein.html`:
```html
<a href="mailto:hello@hilaryklein.com" class="footer-email">hello@hilaryklein.com</a>
```
Replace `hello@hilaryklein.com` with your real email address in both places.

---

## How to Deploy

1. Purchase a domain (recommended: `hilaryklein.com`) via Namecheap, Google Domains, or Squarespace
2. Choose a hosting provider — simple options include:
   - **Netlify** (free tier, drag and drop deployment)
   - **GitHub Pages** (free, good for single page sites)
   - **Squarespace** or **Wix** (easier but less flexible)
3. Upload ALL files to the root directory of your hosting account — the HTML file and all painting images must be in the same folder
4. Upload `robots.txt` to the root directory so it lives at `yourdomain.com/robots.txt`

---

## robots.txt — AI Crawler Blocking

The included `robots.txt` blocks the following known AI and data mining crawlers:

- GPTBot (OpenAI)
- ChatGPT-User (OpenAI)
- Google-Extended (Google AI)
- CCBot (Common Crawl)
- anthropic-ai (Anthropic)
- Claude-Web (Anthropic)
- FacebookBot (Meta)
- Amazonbot (Amazon)
- Bytespider (ByteDance/TikTok)
- Cohere-ai
- Diffbot
- ImagesiftBot
- PetalBot
- And more

Google and Bing search crawlers are still allowed so your site remains discoverable.

> **Note:** Well-behaved bots respect robots.txt. Malicious scrapers may not. For stronger image protection, consider watermarking your paintings before uploading them to the web.

---

## Future Additions (Planned)

- [ ] More paintings added to gallery
- [ ] Contact form
- [ ] Shop / prints for sale
- [ ] Exhibitions and events section
- [ ] Social media links
- [ ] Image watermarking
- [ ] SEO meta tags

---

## About the Artist

Hilary Klein is an acrylic painter based in Silver City, New Mexico.  
Her psychedelic Southwest wildlife paintings explore the sacred relationship between animals, landscape, and spirit — rooted in the Gila wilderness.

*"The color speaks to me."* — Hilary Klein

---

Built with care. © 2024 Hilary Klein. All rights reserved.
