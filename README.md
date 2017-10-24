# GHCC Vue Admin Template

> Based heavily on the VueJS Webpack template. Added necessary folders and files for a ready-to-customize SPA for GHCC.

> A full-featured Webpack setup with hot-reload, lint-on-save, unit testing & css extraction.

> This template is Vue 2.0 compatible.

> No need to configure for SPA. Simply type `npm install` and make page components. And, be sure to have links of those pages in the `router.js` file and in the `HeaderBar.vue` if necessary.

## Get Started

``` bash
$ vue init snhd-development/ghcc_admin ghccapp_admin1
```

## Full Usage

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli). **It is recommended to use npm 3+ for a more efficient dependency tree.**

``` bash
$ npm install -g vue-cli
$ vue init snhd-development/ghcc_admin ghccapp_admin1
$ cd ghccapp_admin1
$ npm install
$ npm run dev
```

If port 8080 is already in use on your machine you must change the port number in `/config/index.js`. Otherwise `npm run dev` will fail.

## Documentation

- [For this template](http://vuejs-templates.github.io/webpack): common questions specific to this template are answered and each part is described in greater detail
- [For Vue 2.0](http://vuejs.org/guide/): general information about how to work with Vue, not specific to this template

## What's Included

- `npm run dev`: first-in-class development experience.
  - Webpack + `vue-loader` for single file Vue components.
  - State preserving hot-reload
  - State preserving compilation error overlay
  - Lint-on-save with ESLint
  - Source maps

- `npm run build`: Production ready build.
  - JavaScript minified with [UglifyJS](https://github.com/mishoo/UglifyJS2).
  - HTML minified with [html-minifier](https://github.com/kangax/html-minifier).
  - CSS across all components extracted into a single file and minified with [cssnano](https://github.com/ben-eb/cssnano).
  - All static assets compiled with version hashes for efficient long-term caching, and a production `index.html` is auto-generated with proper URLs to these generated assets.
  - Use `npm run build --report`to build with bundle size analytics.

- `npm run unit`: Unit tests run in PhantomJS with [Karma](http://karma-runner.github.io/0.13/index.html) + [Mocha](http://mochajs.org/) + [karma-webpack](https://github.com/webpack/karma-webpack).
  - Supports ES2015+ in test files.
  - Supports all webpack loaders.
  - Easy mock injection.

- `npm run e2e`: End-to-end tests with [Nightwatch](http://nightwatchjs.org/).
  - Run tests in multiple browsers in parallel.
  - Works with one command out of the box:
    - Selenium and chromedriver dependencies automatically handled.
    - Automatically spawns the Selenium server.
    
## Developer Notes

- We don't necessarily need to use Karma, Nightwatch or e2e. All of the GHCC Vue Admin apps do not use them. You are prompted for them in case you really feel like using them because you need them.
- All of the GHCC Vue Admin projects use Runtime-only on prompt.

## Suggested modules

- vue2-medium-editor : for Markdown editor
- medium-editor-autolist : to have ordered and unordered list with medium-editor.
- vue-flatpickr : for a pop-up calendar that can be customizable. Please refer to the `hp_admin*` project to see the dependencies, requirements and how to customize. Feel free to look at the [Flatpickr](https://chmln.github.io/flatpickr/) documentation. Some features might not be in `vue-flatpickr`.
