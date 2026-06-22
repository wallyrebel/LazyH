# Lazy H Dog Rescue — Website

Website for **Lazy H Dog Rescue**, a dog shelter in Ripley, Mississippi dedicated to
rescuing, caring for, and rehoming dogs across Tippah County.

## Site

The site is plain HTML/CSS/JS at the repo root — no build step.

- `index.html` — page structure & content
- `styles.css` — styling (responsive)
- `script.js` — mobile menu, scroll & reveal effects
- `assets/` — logo, property photo, and adoption application (PDF)

### View locally

Open `index.html` in any browser, or serve the folder:

```bash
python -m http.server 8765
# then visit http://localhost:8765
```

### Deploy

- **Cloudflare Pages** — connect this repo. No build command; set the
  **build output directory** to `/` (root). `index.html` is at the root.
- **Netlify Drop** — drag the repo folder onto <https://app.netlify.com/drop>
- **GitHub Pages** — Settings → Pages → serve from `main` / root

## Contact

- Email: lazyhdogrescue@gmail.com
- Phone: (662) 512-8584
- Address: 1330 Hwy 773, Ripley, MS 38663
