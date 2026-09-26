# advaitkhaire.com

Personal site built with [Hugo](https://gohugo.io) and the
[Bear Blog theme](https://github.com/janraasch/hugo-bearblog).

## Local development

```
hugo server -D
```

## Structure

- `content/_index.md` — homepage
- `content/blog/` — blog posts
- `content/links.md` — links page
- `hugo.toml` — site config, menu, theme params

## Deployment

This repo is set up to deploy via Cloudflare Pages (build command: `hugo --gc --minify`,
output directory: `public`). See the setup notes shared alongside this repo.
