# Florida Home Installers — Website

A single-page marketing website for **Florida Home Installers**, a women-owned window, door
and siding installation company in Lakeland, Florida.

## Viewing the site

No build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html      Page markup and content
styles.css      All styling (responsive, mobile-first breakpoints)
script.js       Mobile nav, scrollspy, sticky header, form handling
images/         Photography used across the page
```

## Business details used

| Field | Value |
| --- | --- |
| Name | Florida Home Installers |
| Address | 2222 S Combee Rd #7, Lakeland, FL 33801 |
| Phone | (321) 710-5864 |
| Hours | Mon–Fri 9:00 AM – 9:00 PM · Sat 10:00 AM – 5:00 PM · Sun closed |
| Rating | 4.8★ from 20 Google reviews |
| Owner | Danielle DiDonato |

Services covered: replacement windows, impact/hurricane windows, doors and sliding glass,
siding installation, and bathroom remodeling.

## Notes

- **The estimate form does not send email.** This is a static site with no backend, so the form
  validates the visitor's details and then offers a pre-filled text message or a tap-to-call
  link. Wiring it to real email delivery requires a backend or a form endpoint.
- **Photography is licensed stock imagery** of window, door and siding work — not the company's
  own project photos. Replace the files in `images/` with real job photos when available; keep
  the same filenames and no markup changes are needed.
- External dependencies are limited to Google Fonts and the Google Maps embed, both over HTTPS.
