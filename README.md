# Typescript React Starter Kit #
[![Build Status](https://travis-ci.org/hyldmo/typescript-react-starter-kit.svg?branch=master)](https://travis-ci.org/hyldmo/typescript-react-starter-kit)
[![Coverage Status](https://coveralls.io/repos/github/hyldmo/typescript-react-starter-kit/badge.svg?branch=master)](https://coveralls.io/github/hyldmo/typescript-react-starter-kit?branch=master)
[![Greenkeeper badge](https://badges.greenkeeper.io/hyldmo/typescript-react-starter-kit.svg)](https://greenkeeper.io/)
[![dependencies Status](https://david-dm.org/hyldmo/typescript-react-starter-kit/status.svg)](https://david-dm.org/hyldmo/typescript-react-starter-kit)
[![devDependencies Status](https://david-dm.org/hyldmo/typescript-react-starter-kit/dev-status.svg)](https://david-dm.org/hyldmo/typescript-react-starter-kit?type=dev)
[![Known Vulnerabilities](https://snyk.io/test/github/hyldmo/typescript-react-starter-kit/badge.svg?targetFile=package.json)](https://snyk.io/test/github/hyldmo/typescript-react-starter-kit?targetFile=package.json)
----

## Overview ##
This repository showcases a bunch of different technologies and frameworks that I use when developing React projects, combined into an opinionated boilerplate.

## Features ##
- [Typescript](http://www.typescriptlang.org/) for type-checking
- [TSLint](https://palantir.github.io/tslint/) to ensure consistent style
- [React](https://reactjs.org/)
- [React Router](https://reacttraining.com/react-router/)
- [Redux](https://redux.js.org/) + [Redux Saga](https://redux-saga.js.org/)
- [Cypress](https://www.cypress.io/) for end-to-end testing
- [Jest](https://facebook.github.io/jest/) for unit/snapshot testing
- Code coverage from [coveralls.io](https://coveralls.io/)
- [Webpack](https://webpack.js.org/)
  - Hot Module Reloading
  - Bundle hashing to allow for easy caching (npm dependencies are also splitted so that you can update your source code without making the user reload the vendor bundle)
- [less](http://lesscss.org/) support
- Autoprefixing with [PostCSS](http://postcss.org/)
- [Stylelint](https://stylelint.io/) for linting less/CSS
- [Travis](https://travis-ci.org/) for CI
- [Bundle-Loader](https://www.npmjs.com/package/bundle-loader) for chunking lazy-loaded dependencies out of your main bundle. Example usage at the [official documentation](https://webpack.js.org/loaders/bundle-loader/), practical usage can be found in [Root.tsx](src/components/App/Root.tsx#L26).
- [Long-term production asset caching](https://webpack.js.org/guides/caching/) in the back of [hash-all-modules-plugin](https://www.npmjs.com/package/hash-all-modules-plugin) and content hashes.

To get started, run `yarn` to fetch dependencies and `yarn dev` to start the development server
