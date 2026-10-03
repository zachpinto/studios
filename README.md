# Who owns the movies

An interactive map of Hollywood's studios, their film labels, TV networks and streamers, and their biggest titles.

## Deploying on GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html`, this `README.md` and the whole `logos` folder to the repository's main branch.
3. Go to **Settings → Pages**, set **Source** to "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Changing a logo

Logos load from `logos/<circle-id>.<ext>`, listed in `STATIC_LOGOS` inside `index.html`.
To swap one, replace the file in `logos/` with a new image of the same name.
To add one, put the image in `logos/` and add a line to `STATIC_LOGOS`, for example `"lionsgate-tv":"logos/lionsgate-tv.png"`.
