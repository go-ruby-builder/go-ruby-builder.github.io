<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-builder/brand/main/social/go-ruby-builder.png" alt="go-ruby-builder/go-ruby-builder.github.io" width="720"></p>

# go-ruby-builder.github.io

The organization's institutional landing page, served at
<https://go-ruby-builder.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-builder/docs](https://github.com/go-ruby-builder/docs), served at
<https://go-ruby-builder.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
