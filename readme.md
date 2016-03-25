# minimal-boilerplate

> Front-End boilerplate with npm run tasks built-in.

No more complex and large configuration task files, `minimal-boilerplate` has a very tiny configuration footprint via npm scripts.

**Status:** Work in progress...

## Features

- Task automation with [npm run](http://substack.net/task_automation_with_npm_run).
- CommonJS Modules in the browser with [browserify](http://browserify.org/).
- Watch browserify builds with [watchify](https://github.com/substack/watchify).
- Live preview and development with [browser-sync](https://browsersync.io/)
- Automatically compile and watch Sass files with [node-sass](https://github.com/sass/node-sass).
- Javascript and CSS bundles for production with [clean-css](https://github.com/jakubpawlowicz/clean-css) and [UglifyJS 2](https://github.com/mishoo/UglifyJS2).

## Installation
Clone this repository and install dependencies.

```sh
$ npm install
```

## Tasks

#### Development

```sh
$ npm start
```

Or

```sh
$ npm run dev
```

#### Build

```sh
$ npm run build
```

## Configuration

Easy customization tasks via `"scripts"` in `package.json`.

## License
MIT license

© 2016 [José Luis Quintana](http://git.io/joseluisq)
