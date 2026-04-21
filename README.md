# Atlas Rug Gallery

Static website for Atlas Rug Gallery, Fort Worth, Texas. Family run since 1986.

**Live site:** _coming soon_

## Stack

Static HTML, CSS, and JavaScript. No build step, no backend, no database.

## Structure

```
.
├── index.html          Home (with Since 1986 section)
├── about.html          Our Story
├── rugs.html           Antique & Modern Collections
├── cleaning.html       Hand Cleaning & Pet Stain Removal
├── at-home.html        Try at Home
├── trade.html          Interior Designers & Staging
├── heritage.html       Wool & Heritage
├── auctions.html       Auctions
├── contact.html        Visit & Contact
└── assets/
    ├── styles.css
    ├── site.js
    └── images/
```

## Local preview

Open any HTML file in a browser. No server required.

```bash
# or start a simple local server
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Go to Settings, Pages.
3. Source: Deploy from a branch. Branch: `main`. Folder: `/ (root)`.
4. Save. The site publishes within a minute at `https://<username>.github.io/atlas-rug-gallery/`.

For a custom domain, add a `CNAME` file with the domain name, then configure DNS with a CNAME record pointing to `<username>.github.io`.

## Placeholders to fill in

Search across all `.html` files and replace:

| Placeholder | Where | Replace with |
|---|---|---|
| `[ZIP]` | contact.html | Fort Worth zip code |
| `[PHONE NUMBER]` / `[PHONE]` | contact.html and every footer | Phone number |
| `[EMAIL ADDRESS]` / `[EMAIL]` | contact.html and every footer | Email address |
| `[WEBSITE]` | contact.html | Website URL |
| `[FOUNDER NAME]` | about.html | Founder's name |
| `[OWNER NAME]` | about.html | Current owner's name |
| `[OWNER SIGNATURE]` | about.html | Signature line |
| `[YEAR]` | about.html | Three timeline year entries |

## Contact form

Currently alerts on submit. To collect submissions, point the form at Formspree, Netlify Forms, or another form backend.

## License

All rights reserved. Atlas Rug Gallery, Fort Worth, Texas.
