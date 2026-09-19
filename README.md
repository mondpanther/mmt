# Mind Move Thrive

The website at **https://mondpanther.github.io/mmt/**

These files *are* the website. There is no build step, no generator and no
dependencies — GitHub Pages serves this folder exactly as it stands.

**To preview locally:** double-click `index.html`. It looks identical to the
live site, because it is the same files.

**To publish:** commit and push to `master`. Live about a minute later.

## Layout

| Path | Purpose |
| --- | --- |
| `index.html` | Front page: hero, About, Work with me, Podcast, newsletter list, Contact |
| `posts.html` | *Well, From Here* archive |
| `posts/` | One HTML file per post |
| `media/` | Photos and logo |
| `css/style.css` | All styling |
| `.nojekyll` | Stops GitHub Pages running Jekyll over the folder |
| `_old-hugo/` | The previous Hugo + Wowchemy site, kept for reference only. Not used. |

See [HOW-TO-EDIT.md](HOW-TO-EDIT.md) for the editing guide.

## GitHub Pages setting

Settings → Pages → **Deploy from a branch** → `master` → `/ (root)`.
No GitHub Actions workflow is involved.
