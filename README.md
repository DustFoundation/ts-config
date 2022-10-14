# @dustfoundation/ts-config

[![NPM Version](https://badgen.net/npm/v/@dustfoundation/ts-config)](https://npmjs.com/package/@dustfoundation/ts-config)
[![Minimum Node.js Version](https://badgen.net/npm/node/@dustfoundation/ts-config)](https://npmjs.com/package/@dustfoundation/ts-config)

Node.js shared config for TypeScript

## Installation

```bash
npm install --save-dev @dustfoundation/ts-config
```

## Usage

You can use config by extending it in your `tsconfig.json`:

```json
{
  "extends": "@dustfoundation/ts-config",
  "compilerOptions": {
    "outDir": "dist"
  }
}
```
