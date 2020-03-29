# `q-prettier-config`

> Woqutech [Prettier](https://prettier.io) config.

## Usage

**Install**

```bash
$ npm install -D q-prettier-config
```

**A: Edit `package.json`**

```json
{
  "prettier": "q-prettier-config"
}
```

**B: Create and edit `.prettierrc.js`**

```js
module.exports = {
  ...require('q-prettier-config'),
  // extend the configuration to overwrite some properties from the shared configuration
  // semi: false,
}
```
