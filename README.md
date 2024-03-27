# detect-pm

> Detect package managers automatically (`npm`, `yarn`, `bun` and `pnpm`).

[detect-pm](https://www.npmjs.com/package/detect-pm) comes from [https://github.com/antfu/install-pkg/blob/main/src/detect.ts](https://github.com/antfu/install-pkg/blob/main/src/detect.ts). The author is [antfu](https://github.com/antfu) who is my super idol.

## Installation

```bash
$ npm i detect-pm

$ yarn add detect-pm

$ pnpm add detect-pm
```

## Usage

```js
import { detectPackageManager } from 'detect-pm'

detectPackageManager().then(pm => {
    console.log(pm) // one of npm, yarn, pnpm or bun if detect, else null
})
```

## License

[MIT](./LICENSE)

