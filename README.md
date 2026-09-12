# Personal website — quick reference

Files in this folder:

- `index.html` — About me (homepage)
- `research.html` — Research tab, currently shows "Coming soon."
- `research-future.html` — full Research layout (Work in progress /
  Publications / Working papers, with links and expandable abstracts).
  Not linked anywhere yet — swap its `<main>...</main>` content into
  `research.html` when you're ready to start populating the section.
- `css/style.css` — all styling for every page.
- `assets/` — put your `profile.jpg` and `cv.pdf` here.

## Publish it on GitHub Pages

1. Create a repository on GitHub named `yourusername.github.io`
   (replace `yourusername` with your actual GitHub username), public.
2. Upload all the files/folders from this project to that repository,
   keeping the same folder structure (`css/`, `assets/`, the `.html`
   files, all at the repository root).
3. Commit the changes.
4. Go to the repository's **Settings → Pages** and make sure the
   source is set to the `main` branch, root folder. (For a
   `yourusername.github.io` repo this is often already the default.)
5. Wait a minute, then visit `https://yourusername.github.io`.

## Updating later

- Edit any file (on GitHub.com directly, or locally with `git`),
  commit, and push — the live site updates automatically.
- To link a project's code: point a link at a GitHub repo URL, or
  upload a folder into this repository (e.g. `code/project-name/`)
  and link to it with a relative path.
