# monorepo-package
A monorepo nodejs package to be used as part of [monorepo-root](https://github.com/kshutkin/monorepo-root).

A seed nodejs project for a monorepo package.

Main points:
- Uses [rollup.js](https://rollupjs.org/) to bundle files.
- Uses [typescript](https://www.typescriptlang.org) as a default syntax.
- Uses [jest](https://jestjs.io) for tests.
- Supports submodules (additional entry points) and umd format.

Please edit exports field in package.json to have more entry points. For every additional entry point please add a package.json for typings (please check `./core` folder for example).

For other fields in package.json please provide meaningful defaults.

In jest config please provide correct scope(s)/patterns for sibling packages.

Also change details in LICENSE file.

Can be cloned with:
```
npx degit kshutkin/monorepo-package folder-name
```

Where folder-name should be replaced with desired folder name.

After cloning please add it to the parent package.json in packages in the correct position.

Root seed: [monorepo-root](https://github.com/kshutkin/monorepo-root).
