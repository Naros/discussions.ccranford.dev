# discussions.ccranford.dev

Comments for [ccranford.dev](https://ccranford.dev), powered by [giscus](https://giscus.app).
Each post's comment thread lives in this repository's Discussions, under the Announcements category.

`giscus-theme.css` is the comment widget's theme, matching the site's dark ocean palette.
The site loads it through jsDelivr:

```
https://cdn.jsdelivr.net/gh/Naros/discussions.ccranford.dev@main/giscus-theme.css
```

jsDelivr caches `@main` for up to 12 hours.
To make a theme change show up immediately, replace `@main` with the commit SHA in the site's `hugo.toml` (`params.giscus.theme`).
