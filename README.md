# Tsion Mehari — Artist Portfolio

A responsive HTML/CSS portfolio scaffold based on the Figma reference shared in chat. It uses a pale blue-white canvas, spacious editorial typography, sketch-like accents, a collage-inspired artwork grid, and placeholder artwork panels.

## Preview
Open `index.html` in a browser, or enable GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder).

## Replace the placeholders
1. Add your exported image files to an `images/` folder in the repository.
2. In `index.html`, replace each `.art-image` placeholder `div` with an image, for example:
   `<img class="art-image" src="images/my-artwork.jpg" alt="Short description of the artwork">`
3. For the portrait, replace `.portrait-placeholder` with an `<img>` and update `styles.css` to use `object-fit: cover`.
4. Change the sample introduction, about text, project labels, and `hello@example.com` to your own details.

The site works without the artwork files; the colored blocks are intentional placeholders. For large assets, export JPG/WebP versions from Figma, resize them to around 1600px on the longest edge, and keep each image around 1–2 MB where possible. You can upload images separately rather than bundling them into one ZIP.
