# Yashwant's Productivity Dashboard

A deploy-ready, single-page productivity dashboard with a dark cosmic engineering theme.

## Files

```text
dashboard/
+-- index.html
+-- manifest.webmanifest
+-- service-worker.js
+-- netlify.toml
+-- _redirects
+-- robots.txt
+-- .gitignore
+-- assets/
    +-- favicon.svg
```

## Open Locally

Double-click `index.html`.

Some browser features, like the service worker install cache, only run from `http://`, `https://`, or `localhost`. The page itself still works from a double-clicked file.

## Deploy

Upload the whole `dashboard` folder to GitHub Pages or Netlify.

For Netlify, this folder is already configured with `netlify.toml` and `_redirects`.

## Notes

- Habit and task state saves in `localStorage`.
- Chart.js loads from CDN for the analytics charts.
- The app shell is cached by `service-worker.js` after the first web-served visit.
