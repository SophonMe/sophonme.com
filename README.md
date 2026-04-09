# AIContext Feature Page

This folder contains the static feature page for AIContext.

## Files

- `index.html` - main scroll-driven landing page
- `favicon.svg` - trefoil favicon
- `index.snapshot-2026-04-08.html` - backup snapshot before later iterations

## Local Preview

Open `index.html` directly in a browser, or serve the folder with a simple static server.

Example:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Publish With GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder.
3. Enable GitHub Pages in repository settings.
4. Set the custom domain to `aicontext.me`.
5. Configure DNS in Cloudflare.

## Notes

- The page is designed as a single-file static experience.
- Animations and layout are implemented with plain HTML, CSS, and JavaScript.
- `sophonme.com` can redirect to `aicontext.me` via Cloudflare.
