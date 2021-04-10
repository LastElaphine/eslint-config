# LastElaphine ESLint Config

See [ESLint sharable configs guide](https://eslint.org/docs/developer-guide/shareable-configs)

## Installation
Install the package with
`yarn add -D @lastelaphine/eslint-config`

or

`npm install --save-dev @lastelaphine/eslint-config`

## eslint Setup

Now add the config to either the `package.json`:

```json
{
  "eslintConfig": {
    "extends": ["@lastelaphine"]
  }
}
```

or to the `.eslintrc` or `.eslintrc.js`:

```js
module.exports = {
  extends: ["@lastelaphine"],
};
```

### React preset
```js
module.exports = {
  extends: ["@lastelaphine/eslint-config-react"],
};
```
### Typescript preset

```js
module.exports = {
  extends: ["@lastelaphine/eslint-config-ts"],
};
```

### Typescript + React preset
```js
module.exports = {
  extends: ["@lastelaphine/eslint-config-tsx"],
};
```