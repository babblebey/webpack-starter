# webpack starter (a webpack boilerplate)

A webpack boilerplate project packed with Babel

## Installation

Clone this repo and install all dependencies.

```bash
npm install
```

## Usage

### Development server

```bash
npm run serve
```

You can view the development server at `localhost:9000`.

### Production build

```bash
npm run build
```

## Features

- [webpack](https://webpack.js.org/)
- [Babel](https://babeljs.io/)

## Dependencies

### webpack

- [`webpack`](https://github.com/webpack/webpack) - A Module bundler.
- [`webpack-cli`](https://github.com/webpack/webpack-cli) - The Command line interface for webpack
- [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server) - The webpack Development server

### Babel

- [`@babel/core`](https://www.npmjs.com/package/@babel/core) - Transpiles ES6/ES2015+ to backwards compatible JavaScript for cross-browser usage
- [`@babel/preset-env`](https://babeljs.io/docs/en/babel-preset-env) - Smart preset for Babel

### Loaders

- [`babel-loader`](https://webpack.js.org/loaders/babel-loader/) - Transpiles files with Babel through webpack