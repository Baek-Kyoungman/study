---
layout: page
title: UX
navigation: 11
---

# UX

You can use the millidocs theme with github pages by adding it as a `remote_theme`.

```
---
title: Millidocs Theme
description: Documentation for small projects
url: "https://my-url"

remote_theme: alexander-heimbuch/millidocs

markdown: kramdown
kramdown:
  syntax_highlighter_opts:
    disable : true

exclude:
  - Gemfile
  - Gemfile.lock
  - README.md

---
```

For more details visit the [Github Blog Post](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/).