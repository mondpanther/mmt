# Mind Move Thrive

Live at **https://mindmovethrive.live**

These files *are* the website. There is no build step, no generator and no
dependencies — the host serves this folder exactly as it stands.

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
| `netlify.toml` | Tells Netlify to publish the root as-is, with no build |
| `.nojekyll` | Stops GitHub Pages running Jekyll over the folder |
| `_old-hugo/` | The previous Hugo + Wowchemy site, kept for reference only. Not used. |

See [HOW-TO-EDIT.md](HOW-TO-EDIT.md) for the editing guide.

## Hosting

**Netlify is the primary host.** It deploys automatically from `master` and
serves the `mindmovethrive.live` domain, including its HTTPS certificate.

**GitHub Pages is a secondary copy**, served from `master` / `(root)` at
https://mondpanther.github.io/mmt/. It needs no configuration and is kept as a
standby. To switch it off: Settings -> Pages -> Source -> None.

Because every link in the site is relative, the same files work unchanged on
both hosts and when opened directly from disk.

No GitHub Actions workflow is involved in either deploy.
