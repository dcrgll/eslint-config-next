# ESLint Config NextJS

This is an extensive ESLint configurations for NextJS based projects. Its compatible with ESLint >=9.

## Installation

```sh
npm install --save-dev eslint typescript-eslint @dc_/eslint-config-next
```

## Usage

In an ´eslint.config.mjs´ file:

```javascript
import eslintConfig from '@dc_/eslint-config-next'

export default eslintConfig
```

Or

```javascript
import eslintConfig from '@dc_/eslint-config-next'

export default [
  ...eslintConfig,
  // other configurations below, for example:
  {
    rules: {
      '@typescript-eslint/no-unsafe-member-access': 'off'
    }
  }
]
```
