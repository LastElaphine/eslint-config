## Install

```sh
npm i @lastelaphine/eslint-config-react
```


## Use

This config is meant to be applied on top of one of the other base configs.

```js
module.exports = {
  'root': true,
  'extends': [
    '@lastelaphine/eslint-config-ts',
    '@lastelaphine/eslint-config-react'
  ]
};
```
