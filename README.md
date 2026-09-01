# reneefonseca.com

Personal academic site for Renée Fonseca — a hand-built static site (no build step).

- Everything served lives in [`site/`](site/): `index.html`, `publications.html`,
  `talks.html`, `awards.html`, a shared `style.css`, and assets under
  `img/`, `cv/`, and `audio/`.
- Deployed on Netlify, which publishes `site/` directly (see `netlify.toml`).
- Preview locally: `python3 -m http.server 4173 --directory site`

Design: Newsreader + Inter, with a night/red/teal/amber palette where color
encodes grouping (teal = methods, red = populations, amber = building).
