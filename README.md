# dn-middleware-gh-pages

A [dawn](https://github.com/alibaba/dawn) middleware for publishing files to GitHub Pages based on [gh-pages](https://github.com/tschaub/gh-pages).

## Usage

Change dawn publish config in .dawn/pipe.yml to:

```
publish:
  - name: gh-pages
```

Then, run `dn publish` to publish your static files to github repo.

More [options](https://github.com/tschaub/gh-pages).