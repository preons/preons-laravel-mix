# Preons Laravel Mix
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

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

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://kammadata.com/"><img src="https://avatars0.githubusercontent.com/u/4562670?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gemma Black</b></sub></a><br /><a href="https://github.com/preons/preons-laravel-mix/commits?author=gemmadlou" title="Code">💻</a> <a href="https://github.com/preons/preons-laravel-mix/commits?author=gemmadlou" title="Documentation">📖</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!