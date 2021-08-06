# AJ's Blog Setup

`www` - blog source in Markdown
`docs/` - static blog build in HTML/CSS/JS

## Create Post

```
% cd www
% hugo new post/start-of-summer.md
```

## Preview Site Locally

Will automatically refresh to show your changes as you make them in Markdown.

```
% cd www
% hugo -D server
```

## Build Site For GitHub

This will build the docs/ site (HTML/CSS/JS content) from the markdown in your www/ source.

```
% cd www
% hugo -D
```

Always build, then push to GitHub to ensure latest blog changes show up in [my blog](https://ajcreates.dev).

