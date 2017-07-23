# Neutrino Sass Middleware [![Build Status](https://travis-ci.org/markelog/neutrino-middleware-sass.svg?branch=master)](https://travis-ci.org/markelog/neutrino-middleware-sass)

> Neutrino middleware for importing and loading sass from modules

## Installation

```bash
$ npm install --save-dev neutrino-middleware-sass
```

## Usage

```js
// Using object or array middleware format

// Use with default options
module.exports = {
  use: [
    'neutrino-middleware-style-loader', // If it's not added by the preset you using
    'neutrino-middleware-sass'
  ]
};

// Usage showing default options
module.exports = {
  use: [
    ['neutrino-middleware-sass', {

      // See https://github.com/webpack-contrib/sass-loader for all options
      includePaths: ["absolute/path/a", "absolute/path/b"],
      sourceMap: true
    }]
  ]
};
```
