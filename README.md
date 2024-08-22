# Ryan Fitton TailWind
This repository contains Tailwind static HTML files for [ryanfitton.co.uk](https://ryanfitton.co.uk)

Uses TailWind `3.4.10` and features light/dark mode styles.

Fonts:
* Sans: [Red Hat Text](https://fonts.google.com/specimen/Red+Hat+Text)
* Serif: [Brygada 1918](https://fonts.google.com/specimen/Brygada+1918)

Author: 
* Author: [Ryan Fitton](mailto:ryan@ryanfitton.co.uk)
* Author URL: [https://ryanfitton.co.uk](https://ryanfitton.co.uk)

Preview this on Github Pages:

* https://ryanfitton.github.io/ryanfitton-tailwind-2024/archive--portfolio.html
* https://ryanfitton.github.io/ryanfitton-tailwind-2024/archive--posts.html
* https://ryanfitton.github.io/ryanfitton-tailwind-2024/archive--tags.html
* https://ryanfitton.github.io/ryanfitton-tailwind-2024/index.html
* https://ryanfitton.github.io/ryanfitton-tailwind-2024/page.html
* https://ryanfitton.github.io/ryanfitton-tailwind-2024/single--article.html
* https://ryanfitton.github.io/ryanfitton-tailwind-2024/single--portfolio.html)


-------------

## Setup

1. Requires PHP `8.3.10`, Npm `v10.8.1` and Node `v20.16.0` (lts/Iron). [Releases](https://nodejs.org/download/release/v20.16.0/), [Changelog](https://github.com/nodejs/node/blob/main/doc/changelogs/CHANGELOG_V20.md#20.16.0), [Docs](https://nodejs.org/dist/v20.16.0/docs/api/). - Higher versions may also work.

2. Setup Tailwind: `npm run tailwind-init`

3. For development:

  * Run the dev server: `npm run tailwind-server`, then can be accessed on [http://localhost:8080/](http://localhost:8080/)
  * Run the watchers (SCSS, JS): `npm run watch:tailwind`

4. For a static production build run: `npm run build:tailwind`


## Packages required

* `@tailwindcss/typography`: `^0.5.13`
* `autoprefixer`: `^10.4.19`
* `postcss`: `^8.4.39`
* `postcss-cli`: `^11.0.0`
* `postcss-import`: `^16.1.0`
* `postcss-nested`: `^6.0.1`,
* `postcss-nesting`: `^13.0.0`
* `postcss-preset-env`: `^9.6.0`
* `tailwindcss`: `^3.4.10`
