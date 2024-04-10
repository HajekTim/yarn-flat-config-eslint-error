# Commands to reproduce the error

```
yarn install
yarn add @eslint/js
yarn add eslint
yarn dlx @yarnpkg/sdks vscode
```

# Error message

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

# Environment data

Version: 1.88.0 (user setup) <br>
Commit: 5c3e652f63e798a5ac2f31ffd0d863669328dc4c<br>
Date: 2024-04-03T13:26:18.741Z<br>
Electron: 28.2.8<br>
ElectronBuildId: 27744544<br>
Chromium: 120.0.6099.291<br>
Node.js: 18.18.2<br>
V8: 12.0.267.19-electron.0<br>
OS: Windows_NT x64 10.0.22631<br>

ESLint Extension: v3.0.5 (pre-release)
