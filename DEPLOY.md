# GitHub Pages deploy

This folder is the standalone website export.

From the project root, run:

```text
npm run sync:github-pages
npm run check:site
```

Both commands should pass before publishing.

Upload or push the contents of this folder to the GitHub repository you want to use for the site:

- `index.html`
- `.nojekyll`
- `headshots/`
- `work-photos/`

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
