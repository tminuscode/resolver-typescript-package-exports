# resolver-typescript-package-exports

Reproduces bug https://github.com/import-js/eslint-import-resolver-typescript/issues/210

```bash
npm i
npm start
npm run lint
```

Runs fine with `ts-loader` but linter fails to resolve module which is exported by an upstream package.
