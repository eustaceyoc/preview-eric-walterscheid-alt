# Eric Walterscheid Investigations — alternative sample concept

A single-page sample website concept for Eric Walterscheid Investigations (private investigation, Alta Loma, California 91737). It is not the business's official website, and the page says so at the top and in the footer.

This is an alternative design to the first sample at https://preview-eric-walterscheid-investiga.vercel.app.

Live preview: https://preview-eric-walterscheid-alt.vercel.app

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

It's static HTML and CSS with a few lines of JS for the sticky header. There's no build step, no form and no analytics, and the fonts are self-hosted.

## Facts used (nothing else)

- Eric Walterscheid Investigations, Eric Walterscheid, private investigation
- Alta Loma, California 91737 (no street address published)
- +1 (626) 807-0692 · ericwalterscheidinvestigations@yahoo.com
- What to put in a first message, what to hold back, and "Please do not include sensitive case details in your initial email."

There are no specialties, licence number, years in business, results, testimonials, press, social accounts or staff on the page, and there's no photo of Eric.

## Photos

These are editorial Pexels photos under the Pexels License: paperwork desk by Kindel Media, camera by Amar Preciado, and notes and files by RDNE Stock project. None of them shows Eric, his office, his equipment or a case file. Full details are in `assets/provenance.json`.

## Indexing

The page carries `noindex, nofollow, noarchive, nosnippet` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything.
