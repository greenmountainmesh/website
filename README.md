# Green Mountain Mesh website

This site is built with [Hugo](https://gohugo.io/) and deploys automatically to the `production` branch when changes are pushed to `main`.

## Write your first blog post!

If you have something to share with the Green Mountain Mesh community, you are welcome to open a pull reqeust with a new blog post included!

Blog posts live in `content/blog/` and use YAML front matter. Example:

```yaml
---
title: "Post title"
date: 2026-01-28
author: "your-github-username"
summary: "Short summary of the post."
---
```

The `Verify Blog Author` workflow checks that the `author` field matches the GitHub user who opened the pull request. If it does not, the PR check will fail.


## Local development

```sh
hugo server -D
```

The site will be available at http://localhost:1313.


