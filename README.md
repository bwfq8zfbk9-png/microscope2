# Portfolio site

## Files

- `index.html` — landing page with hero image + centered text
- `projects.html` — projects page
- `hero.jpg` — your landing image (you provide this — see below)

## Adding your hero image

1. Save your image as `hero.jpg` in the same folder as `index.html`.
2. That's it — it'll show up automatically.

If your image is `.png` or `.webp` instead of `.jpg`:
- Either rename it to `hero.jpg`, OR
- Open `index.html`, find the line `background-image: url('hero.jpg');` and change it to your filename, e.g. `url('hero.png')`.

## Tips for the hero image

- Landscape orientation works best (wider than tall).
- High resolution (at least 2000px wide) so it stays sharp on big screens.
- Darker images make the white text more readable. If your image is bright, you can increase the overlay darkness: in `index.html`, find `--overlay: rgba(0, 0, 0, 0.25);` and bump 0.25 up to something like 0.4 or 0.5.

## Editing the text

- The big text on the landing page: in `index.html`, look for `<h1>Your headline here.</h1>` and replace it.
- The subtitle below it: look for `<div class="subtitle">Replace this with your own text</div>`.
- Project entries: in `projects.html`, edit the `.project` blocks. Each has a year, title, and description.

## Deploying

Push these files to your GitHub repo (no build step needed). Cloudflare Pages will pick up the changes automatically.
