# @esxl/config-jest

A shareable Jest [configuration](https://jestjs.io/docs/configuration) for all EcmaScript based projects.

## Install

```bash
npm install --save-dev @esxl/config-jest
```

## Use

This package simply exports a Jest [configuration](https://jestjs.io/docs/configuration) Object.

You may either use it as a [`preset`](https://jestjs.io/docs/configuration#preset-string) for your Jest configuration, or import it and extend at will programmatically.

### Use as a preset

In your Jest configuration, add the following `preset`:

```json
{
  "preset": "@esxl/config-jest"
}
```

### Use programmatically

```js
import baseConfig from "@esxl/config-jest";

export default {
  ...baseConfig,
  // Add your own configuration here
};
```
