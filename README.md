# Testing gulp-gh-pages

A one-page example for a tutorial I wrote on deploying to GitHub Pages with gulp-gh-pages. The tutorial is gone from my site, but there's a [copy on the Wayback Machine](http://web.archive.org/web/20161128031340/http://charliegleason.com:80/articles/deploying-to-github-pages-with-gulp).

Status: archived. Made in 2014, not maintained.

Live: https://superhighfives.github.io/testing-gulp-gh-pages/

## Running it

```sh
npm install
npx gulp deploy
```

This uses Gulp 3, so it needs an old version of Node.

## How it works

- `gulpfile.js` has one `deploy` task that pushes everything in `dist/` to the `gh-pages` branch.
- `index.html` is the page that ends up on GitHub Pages.
