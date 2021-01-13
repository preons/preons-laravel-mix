# Preons Laravel Mix

## Install

```bash
yarn add preons-laravel-mix
```

Add preons to the `webpack.mix.js` file:

```javascript
const mix = require('laravel-mix');
require('preons-laravel-mix');

mix.preons();
```

Add a Preons config to the `resource` folder. You can install Preons globally using `npm install preons -g` and run `preons config > resources/preons.yml`.
