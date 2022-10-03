# Lords Eleventy Starter 🚀

A simple starting point for fast Websites :-)

## Features

* Eleventy 2.0
* Vite
* PostCSS
* Image Optimazation

## Getting started

Start by [generating a new repository based on this project](https://github.com/iLord-DEV/lords-eleventy-starter.git/generate).

Make sure you are using Node >= v16!

```sh
node -v
```

If your Version is under 16, please update or install a version manager [like nvm](https://github.com/nvm-sh/nvm)

After cloning (or downloading) the repository to your local machine, install all dependencies with the command

```sh
npm install
```

## Run dev server

The project comes with Eleventy’s built-in development server. You can start the server with

```sh
npm start
````

or

```sh
npx @11ty/eleventy --serve
````

## Build

To trigger a production build, use

```sh
npm run build
````

or

```sh
npx @11ty/eleventy
```

## Deploy a fork of this template to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/iLord-DEV/lords-eleventy-starter.git)

## CSS

I switched from using Sass the past years to PostCSS and never looked back. You can write good ol CSS or use the missing benefits from Sass via PostCSS-Plugins. Like @import, Nesting, and even the hot stuff from the Future ;-)

## Images

Images are optimized and inserted via shortcode to your template files.

## Known Bugs/Quirks

* Vite does not hande files in the publich folder as expected
* sharpOptions not working?

[Autoprefixer](https://github.com/postcss/autoprefixer) adds necessary browser prefixes. The [browserslist](https://github.com/browserslist/browserslist) settings can be adjusted in `package.json`.
