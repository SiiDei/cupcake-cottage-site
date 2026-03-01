Cupcake Cottage — static site image instructions

This repository serves a small static site (`index.html`).

Hero image
- Place your preferred hero photograph at `images/hero.jpg`.
- The site uses a `picture`-style fallback so if `images/hero.jpg` is missing, the included `images/hero.svg` will be displayed instead.
- To use responsive images, replace `images/hero.jpg` with multiple sizes and update the `srcset` in `index.html`.

Product images
- Add product images in `images/products/` with these filenames (or update names in `index.html`):
  - `vanilla.jpg`
  - `chocolate.jpg`
  - `strawberry.jpg`
  - `red-velvet.jpg`
  - `lemon.jpg`
  - `custom.jpg`

Gallery
- Place gallery images in `images/gallery/` and update the `galleryImages` array in `index.html` if you want to control which files show up.

Sample git commands to add images:

```bash
git add images/hero.jpg images/products/vanilla.jpg images/products/chocolate.jpg
git commit -m "Add hero and product images"
git push
```

If you want, I can:
- add a `srcset` example to `index.html` and generate small example images,
- or convert the SVG hero into a raster `hero.jpg` sample (requires binary image creation).

