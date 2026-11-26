# Notes for agents

- Plain static site: keep it one `index.html`, no frameworks or build tools.
- Academic tone and structure, modelled on https://truetqy.github.io/. Keep it minimal; the owner prefers fewer sections and plain wording over flourishes. No self-referential copy about the site or its design.
- Design tokens live in the `:root` block (light) and are redefined for dark mode. Reuse them; do not hard-code new colours.
- Owner's name: Zerui Gong (龚泽睿). Do not bold it in author lists, and do not label or highlight first-author papers.
- Paper/project thumbnails are 16:10: 800×500 JPG figures, or 640×400 muted H.264 loops (no audio, under ~400 KB) with a poster JPG. No "clip"/"video" badges on thumbnails.
- Multi-figure thumbnails use `<a class="thumb slides">` with `img.s` slides and a `.sbar` progress bar; the script handles timing.
- Every animation must have a `prefers-reduced-motion` fallback.
- Clicking a paper/project thumbnail opens the `<dialog id="lightbox">` preview (figures or video, with a link out); the title link goes to the project page.
- The location chip doubles as a button that toggles between coordinates and live Singapore time; keep both strings short enough to fit the callout.
- There is a print stylesheet (`@page` + `@media print`); check Save as PDF after layout changes.
- Update the "Last updated" line in the footer when content changes.
