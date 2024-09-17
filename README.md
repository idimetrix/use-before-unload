# use-before-unload3
React side-effect hook that shows browser alert when user try to reload or close the page.

## Installation

To install the package, use npm:

```bash
pnpm add use-before-unload3

yarn install use-before-unload3

npm install use-before-unload3
```

## Usage

```typescript
import { useBeforeUnload } from 'use-before-unload3';

useBeforeUnload('Message');
```

## tsup
Bundle your TypeScript library with no config, powered by esbuild.

https://tsup.egoist.dev/

## How to use this
1. install dependencies
```
# pnpm
$ pnpm install

# yarn
$ yarn install

# npm
$ npm install
```
2. Add your code to `src`
3. Add export statement to `src/index.ts`
4. Test build command to build `src`.
Once the command works properly, you will see `dist` folder.

```zsh
# pnpm
$ pnpm run build

# yarn
$ yarn run build

# npm
$ npm run build
```
5. Publish your package

```zsh
$ npm publish
```


## test package
https://www.npmjs.com/package/use-before-unload3
