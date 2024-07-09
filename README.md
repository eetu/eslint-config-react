# eslint-config-react

ESlint configuration for React typescript projects

## Install

```bash
yarn add -D eslint-config-react@https://github.com/eetu/eslint-config-react#1.0.0 eslint prettier typescript typescript-eslint
```

Add file eslint.config.js

```JavaScript
import eslintReactConfig from "eslint-config-react";

module.exports = {
  extends: ["eslint-config-node"],

  export default [
    ...eslintReactConfig,
    {
      files: ["**/*.ts", "**/*.tsx"],
    }
  ]
};
```
