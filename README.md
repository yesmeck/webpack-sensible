# webpack-sensible

Add sensible default configs to webpack.

## Installation

```bash
$ yarn add webpack-sensible --dev
```

or

```bash
$ npm install webpack-sensible --save-dev
```

## Usage

```javascript
const WebpackSensible = require('webpack-sensible');

module.exports = {
  ...,
  plugins: [
    new WebpackSensible,
  ]
}
```
