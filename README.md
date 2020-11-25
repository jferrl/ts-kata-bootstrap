# TS Kata Bootstrap

The main purpose of this repository is to have a TypeScript kata bootstrap with a basic end-to-end project setup and workflow for writing Node code with TypeScript.
Proyect structure based on [microsoft/TypeScript-Node-Starter](https://github.com/microsoft/TypeScript-Node-Starter)

## Commands

All the different build steps are orchestrated via [npm scripts](https://docs.npmjs.com/misc/scripts).

| Npm Script   | Description                                                         |
| ------------ | ------------------------------------------------------------------- |
| `start`      | Runs node on `dist/index.js` which is the apps entry point          |
| `build`      | Full build. Runs ALL build tasks (`build-ts`)                       |
| `test`       | Runs tests using Jest test runner                                   |
| `watch-test` | Runs tests in watch mode                                            |
| `build-ts`   | Compiles all source `.ts` files to `.js` files in the `dist` folder |
