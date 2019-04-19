# Harland Clarke Standard Prettier Config

> Harland Clarke Standard [Prettier](https://prettier.io) config.

## Usage

**Install with `npm`**:

``` bash
npm install --save-dev HarlandClarke/prettier-config
```

**Install with `yarn`**:

```bash
yarn add --dev @HarlandClarke/prettier-config
```

### Enable via .prettierrc.js

Provides per project override functionality

**Create `.prettierrc.js`**:

``` js
module.exports = {
  ...require("@harlandclarke/prettier-config"),

  // Custom rules
};
```

### Enable via package.json

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@harlandclarke/prettier-config"
}
```
