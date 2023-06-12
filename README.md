# @jmondi/tsconfig

An opinionated TypeScript config preset for strict and standardized development. Configs for both Node.js and browser environments.

## Install

```bash
pnpm add @jmondi/tsconfig
```

## Usage


### Node.js

```json5
{
  "extends": "@jmondi/tsconfig",
  "compilerOptions": {
    /* add your own options */
  },
}
```


### Browser

```json5
{
  "extends": "@jmondi/tsconfig/browser",
  "compilerOptions": {
    /* add your own options */
  },
}
```

### Extra Config

```json5
{
  "extends": ["@jmondi/tsconfig", "@jmondi/tsconfig/extra-strict"],
  "compilerOptions": {
    /* add your own options */
  },
}
```
