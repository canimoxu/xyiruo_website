# Updating your website

Everything is plain HTML, so you can edit it directly on GitHub — no tools to install.

1. Open https://github.com/canimoxu/xyiruo_website and click `index.html`.
2. Click the pencil icon (Edit this file).
3. Find the section you want (search for `id="research"`, `id="publications"`, `id="teaching"`, etc.) and change the text.
4. Click **Commit changes**. The live site updates within a minute or two.

## Common edits

- **Change a working-paper figure:** upload the image to `images/` (Add file → Upload files; keep it under ~1 MB, about 1000–1800 px wide), then edit the `src` inside that paper's `<figure class="paper-figure">`. Tall or square figures sit beside the text; for a wide figure (more than ~1.5× as wide as tall), add `paper-card-wide` to the `<article class="paper-card">` so it spans the card above the text.
- **Replace the CV:** upload a new PDF named `Xu_Yiruo_CV.pdf` into `files/` (it overwrites the old one).
- **Add a publication:** copy one `<li>…</li>` block inside `<ol class="pubs">` and edit it. Newest first.
- **Change colors or fonts:** edit the variables at the top of `css/style.css`.

## Footer credit / hidden marker

The footer credit line and the hidden `<!-- Created using GaryKing.org/mysite -->` comment plus the JSON-LD block in `<head>` were kept on, as selected in your intake form. Delete them in `index.html` if you change your mind.
