# magenta-with-ts

A demo of using `@magenta/music` as a dev-dependency, and authoring code in
TypeScript.

Run:
```
yarn install
yarn build
```

Get:
 ```
ERROR in ./node_modules/@magenta/music/es6/index.js
Module not found: Error: Can't resolve 'tf' in '/Users/noms/Code/testing-magenta-built-delete/magenta-viewer-demo/node_modules/@magenta/music/es6'
 @ ./node_modules/@magenta/music/es6/index.js 1:82-95
 @ ./src/index.ts

ERROR in /Users/noms/Code/testing-magenta-built-delete/magenta-viewer-demo/src/index.ts
./src/index.ts
[tsl] ERROR in /Users/noms/Code/testing-magenta-built-delete/magenta-viewer-demo/src/index.ts(18,21)
      TS2307: Cannot find module '@magenta/music'.
error Command failed with exit code 2.
info Visit https://yarnpkg.com/en/docs/cli/run for documentation about this command.

 ```
