# primer2-template

A ready-to-use Jekyll site template powered by [primer2-theme](https://github.com/bagustris/primer2-theme) — a two-column GitBook-style theme for GitHub Pages.

## Quick start

1. Click **Use this template** → **Create a new repository**
2. Go to **Settings → Pages** → set Source to **GitHub Actions**
3. Edit `_config.yml` with your site title and description
4. Replace `index.md` and other pages with your content

## Adding pages

Create `.md` files with front matter:

```yaml
---
layout: default
title: My Page
order: 2          # controls sidebar order (optional)
---
```

To hide a page from the sidebar:

```yaml
---
layout: default
title: Hidden Page
nav_exclude: true
---
```

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then visit [localhost:4000](http://localhost:4000).

## License

MIT
