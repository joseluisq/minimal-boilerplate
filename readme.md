# minimal-boilerplate

> Minimal Front-End boilerplate with npm run tasks built-in.

No more complex and large configuration task files, `minimal-boilerplate` has a very tiny configuration footprint via npm scripts.

**Status:** Work in progress...

## Features

- Task automation with [npm run](http://substack.net/task_automation_with_npm_run).
- CommonJS Modules in the browser with [browserify](http://browserify.org/).
- Watch Browserify builds with [watchify](https://github.com/substack/watchify).
- ES6 with [Babel](http://babeljs.io/).
- Live preview and development server with [browser-sync](https://browsersync.io/).
- Automatically watch and compile Sass files with [node-sass](https://github.com/sass/node-sass).
- Javascript and CSS bundles for production with [UglifyJS 2](https://github.com/mishoo/UglifyJS2) and [clean-css](https://github.com/jakubpawlowicz/clean-css).

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
