# creekhealthcare

Facilitate public facing business operations for creekhealthcare.

## Creek Health website demo

This is the standalone Creek Health design preview created by Cozy Digital. The complete website is in `index.html` at the repository root, not nested inside the Cozy Digital marketing site. It is an independent copy; edits here do not change the original demo.

## Files

- `index.html`: the full responsive website, including styles, JavaScript, service dialogs, care finder, FAQs, and demo inquiry form.
- `.nojekyll`: serves the site as ordinary static files on GitHub Pages.
- `README.md`: this setup guide.

No build step, package installation, API keys, backend, or database is required. Illustrative photography is loaded from Pexels.

## Enable GitHub Pages

Open https://github.com/ElvinLearning/creekhealthcare/settings/pages and choose:

1. Source: **Deploy from a branch**.
2. Branch: **main**.
3. Folder: **/ (root)**.
4. **Save**.

After GitHub Pages completes its deployment, the public address will be:

https://elvinlearning.github.io/creekhealthcare/

Publishing still requires the repository owner to enable Pages. The initial automated activation attempt was rejected with HTTP 403; a successful code import does not mean the site has been published.

Future changes committed to `main` will publish through the selected branch once Pages is enabled. Keep the files at the repository root. Do not add a `CNAME` until Creek Health's own domain is confirmed.

## Local preview

Open `index.html` directly, or run:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000/.

## Demo limitations

This is a presentation concept, not a live care-intake website. The form and care finder do not submit or store requests. Search indexing remains disabled. Services, service areas, business contact details, credentials, insurance participation, and policies require client confirmation before launch. Photographs are illustrative stock images, not Creek Health staff or clients.

## Import verification

Imported from `kaysongt/cozydigital-site/public/demos/creek-health/index.html` on November 16, 2026. The initial standalone copy is byte-for-byte identical to that tested demo.

- Git blob: `7636bc571e34622c77aae501f61dbd26381030eb`
- SHA-256: `bdc454c492435970d2eebeb428c1b12d242882e4ac911617ce22f52d9fa80ce7`

The existing demo at https://cozydigital.org/demos/creek-health/ was left unchanged.
