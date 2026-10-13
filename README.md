# Global Tether Ventures

The website for Global Tether Ventures, the company I built so my curiosity never has to settle on one thing.

It's a single static page: no framework, no build step, no dependencies beyond Google Fonts.

## What's in here

- `index.html` is the whole site. Styles are inline.
- `README.md` is this file.

## Run it locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

The site is hosted on Cloudflare Pages, deployed from this repo.

- Framework preset: None
- Build command: leave empty
- Build output directory: `/`

Every push to the main branch goes live. The custom domain is set up in the Cloudflare Pages project, not in this repo.

## Editing

All the copy is plain HTML in `index.html`. The page has four parts: the intro, the story timeline, the contact section and the footer. To add a new chapter to the story, copy one of the timeline blocks (the ones with a dot and an `h2`) and change the text and link.

Resonance is left out on purpose and will be added once it's live.
