# EnterpriseApp

![CI](https://github.com/newaeonweb/enterpriseAppBoilerplate/workflows/CI/badge.svg)

It is a simple baseline code to start enterprise big applications with a solid structure.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.3.

## Project Structure

The most important feature is the ui-elements project library, where you must place all the components for your ui, this means that the EnterpriseAppBoilerplate is a UI framework agnostic, so you can use any ui.

```
.
|____example-app
| |____.browserslistrc
| |____e2e
| | |____protractor.conf.js
| | |____src
| | | |____app.e2e-spec.ts
| | | |____app.po.ts
| | |____tsconfig.json
| |____karma.conf.js
| |____src
| | |____app
| | | |____app-routing.module.ts
| | | |____app.component.html
| | | |____app.component.scss
| | | |____app.component.spec.ts
| | | |____app.component.ts
| | | |____app.module.ts
| | |____assets
| | | |____.gitkeep
| | |____environments
| | | |____environment.prod.ts
| | | |____environment.ts
| | |____favicon.ico
| | |____index.html
| | |____main.ts
| | |____polyfills.ts
| | |____styles.scss
| | |____test.ts
| |____tsconfig.app.json
| |____tsconfig.spec.json
| |____tslint.json
|____ui-elements
| |____karma.conf.js
| |____ng-package.json
| |____package.json
| |____README.md
| |____src
| | |____lib
| | | |____navbar
| | | | |____navbar.component.html
| | | | |____navbar.component.scss
| | | | |____navbar.component.spec.ts
| | | | |____navbar.component.ts
| | | |____ui-elements.module.ts
| | |____public-api.ts
| | |____test.ts
| |____tsconfig.lib.json
| |____tsconfig.lib.prod.json
| |____tsconfig.spec.json
| |____tslint.json
```

## Development server

Prepare the ui library `npm run ui:build`
To see the example app run `npm run start:example`. Navigate to `http://localhost:3000/`.

## Code scaffolding

We recommend the use of: [Nx Console](https://nx.dev/latest/angular/cli/console) if you use vscode you can find [here](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console).

## Build

You are free to prepare your own build, and we recommend the use of: [buildkite](https://buildkite.com/)

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

For this moment we only have one component in our library so this boilerplate is a working in progress...More news coming soon!
