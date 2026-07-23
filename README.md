# smartline-industrial-website

Single-page website for Smartline Industrial Supplies Inc. — Mississauga, ON.

## Contents

```
index.html     complete site (all sections, CSS + JS inline)
images/        category tiles and hero image
```

## Deploy with GitHub Pages

1. Push these files to the repository root on the `main` branch.
2. Settings → Pages → Source: **Deploy from a branch** → `main` / `/ (root)`.
3. Site publishes at `https://<user>.github.io/<repo>/`.

## Before going live

Replace the contact form placeholder in `index.html`:

```html
<input type="hidden" name="access_key" value="YOUR_WEB3FORMS_KEY_HERE"/>
```

Get a free key at web3forms.com and paste it in — enquiries will then be
delivered to sales@smartlineindustrial.com.

## Notes

- Filenames are case-sensitive on GitHub Pages. Image references are all
  lowercase except `carbideEM.jpg`; keep them exactly as they are.
- Navigation is anchor-based (`#products`, `#services`, `#catalog`, `#contact`).
- The catalog table filters and searches client-side. Rows link to the
  quote form; no prices are shown.
