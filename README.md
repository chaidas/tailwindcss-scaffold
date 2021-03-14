# TailwindCSS quickstart

A (slightly opinionated) TailwindCSS scaffold.

## Quickstart

-   Clone this repository
-   `npm install`

## Development

-   Edit `index.html` as needed using TailwindCSS classes
-   Add any custom CSS content in `src/css/styles.css`
-   `npm run tailwind:dev` starts a watcher and re-builds `dist/web.css`
    when `src/css/styles.css` is changed

## Production

-   `npm run tailwind:prod` builds `dist/web.css` once
    (ensuring all style names not found on `index.html` are purged)

## PostCSS plugins present

-   https://github.com/postcss/postcss-import
-   https://github.com/postcss/postcss-nested
-   https://github.com/cssnano/cssnano - runs only when `NODE_ENV=prod`
-   https://github.com/postcss/autoprefixer

## Helpful links

-   https://tailwindcss.com/docs/customizing-colors - The default color palette that
    comes out-of-the-box
-   https://tailwindcss.com/docs/breakpoints - The default breakpoints
-   https://nerdcave.com/tailwind-cheat-sheet - A lovely cheatsheet
-   https://tailwindcss.com/docs/adding-base-styles - Base styles
-   https://tailwindcss.com/docs/flex - Flextastic stuff