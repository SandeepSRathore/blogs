# My Learnings

Personal blog built with [Jekyll](https://jekyllrb.com) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, published at <https://sandeepsrathore.github.io/blogs>.

## Writing a post

Create a file in `_posts/` named `YYYY-MM-DD-short-title.md`:

```markdown
---
title: My Post Title
date: 2026-10-19 10:00:00 +0530
categories: [TopCategory, SubCategory]
tags: [tag1, tag2]
---

Post content in Markdown.
```

Posts dated in the future are not published until that date.

Commit and push to `main`. The GitHub Actions workflow in `.github/workflows/pages-deploy.yml` builds and deploys the site in a couple of minutes.

See the [Chirpy writing guide](https://chirpy.cotes.page/posts/write-a-new-post/) for images, callouts, math, and diagrams.

## Previewing locally (optional)

Requires Ruby 3.x (macOS ships 2.6, which is too old):

```sh
brew install ruby        # then add Homebrew Ruby to your PATH as brew instructs
bundle install
bundle exec jekyll serve # open http://127.0.0.1:4000/blogs/
```
