# Leatham — Technology, Cloud & Data Consultancy

A simple, fast, single-page marketing site for a technology, cloud and data
consultancy. Static HTML/CSS/JS — no build step, no dependencies.

## Files

| File         | Purpose                                          |
|--------------|--------------------------------------------------|
| `index.html` | Page structure and content                       |
| `styles.css` | Styling (dark theme, responsive, accessible)     |
| `script.js`  | Mobile nav, footer year, contact-form validation |

## Run it

Just open `index.html` in a browser. Or serve it locally:

```sh
# Python
python -m http.server 8000

# Node
npx serve .
```

Then visit http://localhost:8000.

## Customise

- **Brand / copy:** edit text directly in `index.html`.
- **Colours / spacing:** tweak the CSS variables in `:root` at the top of `styles.css`.
- **Contact form:** `script.js` validates input but does **not** send anywhere.
  Connect it to a form service (e.g. Formspree, Netlify Forms) or your own API
  by handling the `submit` event in `script.js`.

## Deploy

Drop the three files on any static host — GitHub Pages, Netlify, Cloudflare
Pages, S3 + CloudFront, etc.
