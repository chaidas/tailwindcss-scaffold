# TailwindCSS quickstart
A (slightly opinionated) TailwindCSS scaffold.

## Quickstart
* Clone this repository 
* `npm install`
* Edit `index.html` for your HTML content
* Edit `src/css/styles.css` for your custom CSS content
* Development: `npm run tailwind:dev` to start a watcher and re-build `dist/web.css` 
  when `src/css/styles.css` is changed
* Production: `npm run tailwind:prod` builds `dist/web.css` once ensuring all style names
not found on `index.html` are purged

## PostCSS plugins present
* https://github.com/postcss/postcss-import
* https://github.com/postcss/postcss-nested
* https://github.com/cssnano/cssnano - runs only when `NODE_ENV=prod`
* https://github.com/postcss/autoprefixer