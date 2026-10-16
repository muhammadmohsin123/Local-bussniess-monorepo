# Local Business Monorepo

Marketing websites for local businesses. Each business gets its own folder.

| Business | Folder | Location |
|---|---|---|
| Bite & Delight Pizza Cafe | [`bites-and-delights/`](bites-and-delights/) | Jhang More, Muzaffargarh |
| The Sicilian Eatery | [`the-sicilian-eatery/`](the-sicilian-eatery/) | Jhang Road, Muzaffargarh |

## Run a site locally

Each site is a static `index.html`. Serve its folder:

```bash
cd bites-and-delights
python3 -m http.server 8000
```

Then open http://localhost:8000.

`the-sicilian-eatery/` is fully self-contained: its photos are embedded in `index.html`,
so you can also just double-click the file — no server needed.

## Add a new business

1. Create a folder named after the business (kebab-case), e.g. `the-sicilian-eatery/`.
2. Put the site's `index.html` (and any assets) inside it.
3. Add a row to the table above.
