# Savvy CSS Border Garnishes

[![Latest NPM release][npm-badge]][npm-badge-url]
[![Dependencies][dependencies-badge]][dependencies-badge-url]
[![Dev Dependencies][devDependencies-badge]][devDependencies-badge-url]
[![License][license-badge]][license-badge-url]

_Border garnishes for Savvy CSS._

## Installation

You can install this package using [yarn](https://yarnpkg.com/en/docs/install):

```shell
yarn add --dev @savvy-css/border-garnishes
```

... or using [NPM](https://docs.npmjs.com/getting-started/installing-node):

```shell
npm install --save-dev @savvy-css/border-garnishes
```

## Usage

Within a project that's capable of importing CSS, simply import
the module by its package name within your own CSS:

```css
@import "@savvy-css/border-garnishes";

```

Importing this module will add [its properties](/lib/border-garnishes.css) to your project. To override them, simply define them in any portion of your CSS that's imported/processed later.

### Using Custom Properties

You'll notice that some rules attempt to reference a custom CSS property
before falling back to a default value. This allows you to override
the defaults by defining these properties within your own project.

⚠️ Be sure to define your properties _before_ this module is imported.


[npm-badge]: https://img.shields.io/npm/v/@savvy-css/border-garnishes.svg
[npm-badge-url]: https://www.npmjs.com/package/@savvy-css/border-garnishes
[license-badge]: https://img.shields.io/npm/l/@savvy-css/border-garnishes.svg
[license-badge-url]: LICENSE
[dependencies-badge]: https://img.shields.io/david/savvy-css/border-garnishes.svg
[dependencies-badge-url]: https://david-dm.org/savvy-css/border-garnishes
[devDependencies-badge]: https://img.shields.io/david/dev/savvy-css/border-garnishes.svg
[devDependencies-badge-url]: https://david-dm.org/savvy-css/border-garnishes#info=devDependencies

