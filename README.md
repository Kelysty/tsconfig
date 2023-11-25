# @kelysty/tsconfig

## Install

Using `npm`:

```bash
npm install --save-dev @kelysty/tsconfig
```

Using `yarn`:

```bash
yarn add --dev @kelysty/tsconfig
```

## Usage

### JSON

Add `tsconfig.json` file in the project root with the following content. 
Creating tsconfig with `json` extension is the most common approach and one of the best practice.

```json
{
  "extends": "@kelysty/tsconfig/tsconfig.json"
}
```

### JS/TS

Alternatively you can create `tsconfig.js` or `tsconfig.ts` file in the root of your project with following content:

```js
module.exports = {
    extends: ["@kelysty/tsconfig"]
}
```
