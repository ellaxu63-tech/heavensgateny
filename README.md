# heavensgateny.com

Only redirects `heavensgateny.com` (and `www.`) to **https://heavensgate.nyc**,
keeping the page, so `heavensgateny.com/gallery.html` goes to
`heavensgate.nyc/gallery.html`. The website itself is in the HeavensgateNYC repository.

- `index.html` and `404.html` hold the redirect (the same file; `404.html` catches every other address).
- `CNAME` is what makes GitHub Pages serve this repo on heavensgateny.com. Keep it.
- To point somewhere else, change `target` and the two `heavensgate.nyc` links in `index.html`, and copy it over `404.html`.
