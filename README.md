# libre-apps.org

Site of the libre-apps organization: free and open source apps that deliver real value, with no ads and no unnecessary data collection.

Served by GitHub Pages at <https://libre-apps.org>. One static page, no build, no dependencies and no third party requests: `index.html`, `assets/css/site.css` and the images in `assets/img/`. English and Portuguese live side by side in the HTML; the BR and EN buttons (or `?lang=pt|en`) pick one. The page opens in the light theme; the moon button switches to dark.

Run it locally:

```bash
python3 -m http.server 8000
```

The logo files and the color palette are in [`brand/`](brand/).

When `site.css` changes, bump `?v=` in `index.html` so browsers fetch the new file.
