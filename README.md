Commands ran:

```
yarn install
yarn add @eslint/js
yarn add eslint
yarn dlx @yarnpkg/sdks vscode
```

Error message:

```
[Error - 9:48:06 PM] An unexpected error occurred:
[Error - 9:48:06 PM] Error [ERR_MODULE_NOT_FOUND]: Cannot find package '@eslint/js' imported from C:\Users\timmi\VSCodeProjects\yarn-flat-config-eslint-error\eslint.config.mjs
Did you mean to import @eslint-js-npm-9.0.0-5e980024c8-10c0.zip/node_modules/@eslint/js/src/index.js?
    at new NodeError (node:internal/errors:405:5)
    at packageResolve (node:internal/modules/esm/resolve:863:9)
    at moduleResolve (node:internal/modules/esm/resolve:912:20)
    at defaultResolve (node:internal/modules/esm/resolve:1105:11)
    at nextResolve (node:internal/modules/esm/loader:166:28)
    at ESMLoader.resolve (node:internal/modules/esm/loader:840:30)
    at ESMLoader.getModuleJob (node:internal/modules/esm/loader:429:18)
    at ModuleWrap.<anonymous> (node:internal/modules/esm/module_job:77:40)
    at link (node:internal/modules/esm/module_job:76:36)
```
