<h2 align="center">Prettier Configurations</h2>
<p align="center">
  <a href="https://www.npmjs.com/package/@salimabsi/prettier-config">
    <img alt="npm version" src="https://img.shields.io/npm/v/@salimabsi/prettier-config.svg?style=flat-square">
    <img alt="weekly downloads from npm" src="https://img.shields.io/npm/dw/@salimabsi/prettier-config.svg?style=flat-square">
  </a>
  <br />
  <p align="center">
    Prettier configurations I personally use for my projects.
  </p>
  <pre><p align="center">npm i -D @salimabsi/prettier-config</p></pre>
</p>

&nbsp;

## Basic Usage

Add the following line to your `package.json` file:

```json
{
  "prettier": "@salimabsi/prettier-config"
}
```

## Configuration Overrides

To override configurations, include the following code in your `.prettierrc.js` file:

```js
module.exports = {
  ...require('@salimabsi/prettier-config'),
  printWidth: 120,
}
```
