# GitHub Pages deploy

This folder is the standalone website export.

From the project root, run:

```text
npm run sync:github-pages
npm run check:site
```

Both commands should pass before publishing.

Upload or push the contents of this folder to the GitHub repository you want to use for the site.

Important: upload the folder contents, not the parent `github-pages` folder and not the zip file as a single file. `index.html` must sit at the repository root with `headshots/` and `work-photos/` beside it.

- `index.html`
- `.nojekyll`
- `headshots/`
- `work-photos/`

The final repository root should look like:

```text
index.html
.nojekyll
headshots/brandon-current-headshot.png
work-photos/career-day-learning-room-2.avif
work-photos/youth-media-group.jpg
work-photos/yalp-magazine-thumbnail.jpg
work-photos/podcast.jpeg
work-photos/film-thumbnail.png
work-photos/blog-thumbnail.png
work-photos/community-practice.png
work-photos/workshop-room.jpg
```

For a user site, use a repository named:

```text
stuffxbran.github.io
```

Then enable GitHub Pages from the repository settings:

```text
Settings -> Pages -> Deploy from a branch -> main -> /root
```

The live site will be:

```text
https://stuffxbran.github.io/
```
