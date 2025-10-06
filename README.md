# Minimal Photo Site (GitHub Pages)

## How to use
1. Create a public repo named `yourusername.github.io` on GitHub.
2. Upload **index.html** to the repo root.
3. Create a folder **photos/** and upload your JPG/PNG files into it.
4. Edit `index.html` and add your filenames inside the `PHOTOS` array, e.g.

```js
{ src: 'photos/seattle-01.jpg', alt: 'Seattle' },
{ src: 'photos/lisbon-01.jpg', alt: 'Lisbon' },
```

5. Enable GitHub Pages: **Settings → Pages → Deploy from a branch → main → /(root)**.
6. Open `https://yourusername.github.io`.

## Tips
- Resize photos to ~1600–2048px long edge, JPEG quality ~80% for fast loads.
- Filenames and paths are **case-sensitive** on the web.
