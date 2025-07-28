# Crowns by Design – Simple Website

This repository contains a lightweight, responsive website for **Crowns by Design**, a dental laboratory based in Bellingham, WA.

## Files

- `index.html` – Main one-page site with sections for About, Services, Why Us, and Contact.
- `style.css`  – Core styles (Google Fonts + Font Awesome are loaded via CDN).

## Preview Locally

1. Clone or download the repository.
2. Open `index.html` directly in any browser, **or** serve the folder using a local server:

```bash
python3 -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

- Update phone number, email, or address in the **Contact** section inside `index.html`.
- Replace Unsplash hero image by editing the `background-image` URL in `style.css` (`#hero` selector).
- Adjust brand colors in the `:root` CSS variables at the top of `style.css`.

## Deployment

Because the site is 100 % static, you can host it for free on services such as GitHub Pages, Netlify, or Vercel. Simply deploy the two files as-is.

---

Made with ❤️ for Crowns by Design.