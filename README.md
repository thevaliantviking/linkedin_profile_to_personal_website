# Victor Lundberg — Personal Portfolio

A small, static personal portfolio site for Victor Lundberg, Industrial
Electrician at General Motors. It's built from Victor's public LinkedIn
profile and public GitHub repositories, and is plain HTML, CSS, and
JavaScript — no backend, no build step, no analytics or tracking.

**Live site:** hosted on GitHub Pages (enable it in this repo's Settings →
Pages, serving from the default branch, if it isn't already).

## What's on the site

- **About**: a short summary of Victor's role, license, training, and programming work.
- **Resume**: experience, education, licenses and certifications, and skills.
- **Projects**: a few of Victor's public GitHub repositories
  ([github.com/thevaliantviking](https://github.com/thevaliantviking)).
- **Contact**: a contact form (goes nowhere by design; see "No
  backend" below) and a city-level map of Flint, Michigan.

The template's original "Portfolio" mockups, "Blog", testimonials, and
client-logo sections aren't part of Victor's profile, so they're
commented out in `index.html` rather than deleted, in case any of them
are wanted later.

## Content notes

Content comes from a LinkedIn data export. See `content-notes.md` for
exactly what was used and what's still missing. A few deliberate choices:

- License and credential numbers aren't printed on the page. Links only
  go to public verification or certificate pages.
- Expiry dates to update after renewal: Michigan Journeyman license
  (January 2027) and Basic Life Support card (March 2028).

## Running locally

No build step — it's a static site. Either open `index.html` directly in
a browser, or serve the folder locally, e.g.:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## No backend

The contact form has no server behind it (`action="#"`); submitting it
does nothing. There's no database, login system, or analytics/tracking
script anywhere in this site, by design.

## Credits

Built on top of the **vCard** personal portfolio template by
[codewithsadee](https://github.com/codewithsadee/vcard-personal-portfolio),
used and modified here under its MIT license (see `LICENSE`).

## License

MIT — see [`LICENSE`](./LICENSE). The original copyright notice is
preserved as required by the license.
