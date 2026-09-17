# iamnafets.com

Stefan Mai's personal site, published by GitHub Pages from `master` at the repository root. The site uses Jekyll; the historical posts and their URLs are preserved.

## Local development

Install a supported Ruby, then run `bundle install` and `bundle exec jekyll serve`. `bundle exec jekyll build --safe` builds the site with GitHub Pages' safe-mode constraints. Generated output lives in `_site/` and is ignored by Git.

Styles live in `assets/css/site.css`; the layout uses local assets and system fonts, without a JavaScript runtime. `_config.yml` contains the canonical HTTPS origin. Keep `CNAME` set to `www.iamnafets.com`.

## nafhud information pages

- `/nafhud/`: application homepage
- `/nafhud/privacy/`: privacy policy
- `/nafhud/terms/`: terms of use

Keep data-handling statements aligned with nafhud's actual implementation. Do not put credentials, private email, or private workflow data in this public repository.
