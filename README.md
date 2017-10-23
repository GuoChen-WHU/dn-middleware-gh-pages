# dn-middleware-gh-pages

This is a dawn middleware for publishing files to GitHub Pages based on [gh-pages](https://github.com/tschaub/gh-pages).

## Usage

Change dawn publish config in .dawn/pipe.yml to this:

```
publish:
  - name: gh-pages
    dir: build
```

Then, run `dn publish` to publish your static files to github repo.

More [options](https://github.com/tschaub/gh-pages).