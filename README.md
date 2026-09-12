# KFC Cambodia — Outlets Page (Clone)

A clean, responsive front-end clone of the KFC Cambodia store-locator page, built to practice HTML, CSS and vanilla JavaScript.

**Live demo:** https://rimsovannara.github.io/kfc-clone/

> ⚠️ Unofficial, educational project. Not affiliated with, endorsed by, or connected to KFC or Yum! Brands. All trademarks belong to their respective owners.

## Features

- Single, dependency-free `index.html` — no build step, no framework
- Responsive layout (mobile → desktop)
- Live search by outlet name or address
- Filter by region (Phnom Penh, Siem Reap, Battambang, Sihanoukville, Koh Kong)
- Click-to-call phone links and "Directions" links that open Google Maps
- All 14 outlets with real addresses and phone numbers

## Run locally

It's a static page — open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html      the whole page (markup, styles, and outlet data/script)
assets/         logo, favicon and hero image
```

To add or edit an outlet, update the `outlets` array near the bottom of `index.html`.

## Notes

This was originally a full-page mirror of https://kfc.com.kh/all-store/. It has been
rebuilt as a single clean page: the WordPress/plugin assets were removed and the
markup, styling and data rewritten from scratch.

## License

Code is released under the MIT License (see [LICENSE](LICENSE) if present). Brand
names, logos and imagery are the property of their respective owners and are used
here for educational purposes only.
