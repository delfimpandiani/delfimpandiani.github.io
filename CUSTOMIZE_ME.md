## 4. Your publications

File: `content/publications.md`

Replace the fake papers with your real ones. No publications yet? List your thesis, a conference presentation, or remove sections you don't need.

## 5. Your research

File: `content/research.md`

Describe your actual research projects and interests.

## 6. Your teaching

File: `content/teaching.md`

Add courses you teach or have taught. Not teaching yet? Delete this file and remove it from `config/_default/menus.en.toml`.

## 7. Delete the workshop guide

File: `content/guide.md` and the entry in `config/_default/menus.en.toml`

Once you're done with the workshop, delete this guide page and remove it from the menu.

## 8. Your Netlify URL

File: `config/_default/hugo.toml`

Change `baseURL` to your actual Netlify URL (or custom domain).

File: `netlify.toml`

Change `HUGO_BASEURL` to match.

## 9. Profile photo (optional)

The template ships with a placeholder image (`assets/img/Rooster.png`), referenced by the `image` line under `[params.author]` in `config/_default/languages.en.toml`.

To use your own photo:
1. Put your image in `assets/img/`
2. Update that `image` line to point to your file, e.g. `image = "img/your-photo.jpg"`
