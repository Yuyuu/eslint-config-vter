# ESLint config for my personal projects

## Installation

Add the module to your project:

    npm install --save-dev eslint-config-vter

Create a `.eslintrc.js` file at the root with at least:

```js
module.exports = {
  'extends': 'vter'
};
```

## Major configurations

* `vter` (redirects to backend, see below)
* `vter/configurations/backend`
* `vter/configurations/frontend`