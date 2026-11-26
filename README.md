# Zerui Gong — academic homepage

One static page (`index.html`), no build step. Academic structure (intro, research, experience, education, beyond research), styled with the GOATLab / team6907.org design language.

## Run locally

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Layout

- `index.html`: all markup, CSS and script.
- `assets/portrait.jpg`: profile photo (3:4).
- `assets/world-dots.png`: dotted world map used as a CSS mask in the hero (tinted by theme). Singapore sits at 78.839% / 55.211% of the image.
- `assets/papers/`: paper thumbnails. Videos are 640×400 H.264 loops with a JPG poster; static figures are 800×500 JPGs. Files named `name-2.jpg`, `name-3.jpg`… are extra slides for the figure slideshow.
- `assets/beyond/`: video loops for the Beyond Research cards.

## Deploy

Served as-is by GitHub Pages from a repository named `Ry3nG.github.io` (root of the default branch), at https://ry3ng.github.io/.
