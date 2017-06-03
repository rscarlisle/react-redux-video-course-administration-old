# React/Redux Video Course Administration

[![Build Status](https://travis-ci.org/topheman/vanilla-es6-jspm.svg?branch=master)](https://travis-ci.org/topheman/vanilla-es6-jspm)
[![Sauce Test Status](https://saucelabs.com/buildstatus/vanilla-es6-jspm)](https://saucelabs.com/u/vanilla-es6-jspm)
[![devDependency Status](https://david-dm.org/topheman/vanilla-es6-jspm/dev-status.svg)](https://david-dm.org/topheman/vanilla-es6-jspm#info=devDependencies)

![video-course-administration 2017-06-02 at 7 48 26 pm](https://cloud.githubusercontent.com/assets/6508354/26754061/43ec7bc8-4828-11e7-9b7f-caab791692f4.png) 
Project source can be downloaded from: https://github.com/rscarlisle/react-redux-video-course-administration.git

**Author & Contribution List**
---------------

Randall Carlisle

All other bugs and fixes can be sent to randy@pd-quick.com

Reported bugs and fixes will be submitted for correction

**File List**
-----------
```
.:

License

README.md

./api

./app

./typings
```

```
./api

./api/products/products.json
```

**How to Run Project**
----------------------
1. Required operating system - OSX

2. Fork/clone project to local system

3. cd into project folder

4. [run] npm start

5. in browser, [enter] http://localhost:8080

6. quick-start login: new-user & password123



**Basic Overview of Project**
----------------------
Basic description of project...



## Technologies
A comprehensive collection of technologies, offering a rich development experience:

| **Tech** | **Description** |**Learn More**|
|----------|-------|---|
|  [React](https://facebook.github.io/react/)  |   Fast, composable client-side components.    | [Pluralsight Course](https://www.pluralsight.com/courses/react-flux-building-applications)  |
|  [Redux](http://redux.js.org) |  Enforces unidirectional data flows and immutable, hot reloadable store. Supports time-travel debugging. Lean alternative to [Facebook's Flux](https://facebook.github.io/flux/docs/overview.html).| [Getting Started with Redux](https://egghead.io/courses/getting-started-with-redux), [Building React Applications with Idiomatic Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux), [Pluralsight Course](http://www.pluralsight.com/courses/react-redux-react-router-es6)|
|  [React Router](https://github.com/reactjs/react-router) | A complete routing library for React | [Pluralsight Course](https://www.pluralsight.com/courses/react-flux-building-applications) |
|  [Babel](http://babeljs.io) |  Compiles ES6 to ES5. Enjoy the new version of JavaScript today.     | [ES6 REPL](https://babeljs.io/repl/), [ES6 vs ES5](http://es6-features.org), [ES6 Katas](http://es6katas.org), [Pluralsight course](https://www.pluralsight.com/courses/javascript-fundamentals-es6)    |
| [Webpack](http://webpack.github.io) | Bundles npm packages and our JS into a single file. Includes hot reloading via [react-transform-hmr](https://www.npmjs.com/package/react-transform-hmr). | [Quick Webpack How-to](https://github.com/petehunt/webpack-howto) [Pluralsight Course](https://www.pluralsight.com/courses/webpack-fundamentals)|
| [Browsersync](https://www.browsersync.io/) | Lightweight development HTTP server that supports synchronized testing and debugging on multiple devices. | [Intro vid](https://www.youtube.com/watch?time_continue=1&v=heNWfzc7ufQ)|
| [Jest](https://facebook.github.io/jest/) | Automated tests with built-in expect assertions and [Enzyme](https://github.com/airbnb/enzyme) for DOM testing without a browser using Node. | [Pluralsight Course](https://www.pluralsight.com/courses/testing-javascript) |
| [TrackJS](https://trackjs.com/) | JavaScript error tracking. | [Free trial](https://my.trackjs.com/signup)|  
| [ESLint](http://eslint.org/)| Lint JS. Reports syntax and style issues. Using [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) for additional React specific linting rules. | |
| [SASS](http://sass-lang.com/) | Compiled CSS styles with variables, functions, and more. | [Pluralsight Course](https://www.pluralsight.com/courses/better-css)|
| [PostCSS](https://github.com/postcss/postcss) | Transform styles with JS plugins. Used to autoprefix CSS |
| [Editor Config](http://editorconfig.org) | Enforce consistent editor settings (spaces vs tabs, etc). | [IDE Plugins](http://editorconfig.org/#download) |
| [npm Scripts](https://docs.npmjs.com/misc/scripts)| Glues all this together in a handy automated build. | [Pluralsight course](https://www.pluralsight.com/courses/npm-build-tool-introduction), [Why not Gulp?](https://medium.com/@housecor/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.vtaziro8n)  | Cory House


### Production Dependencies
| **Dependency** | **Use** |
|----------|-------|
|babel-polyfill | Polyfill for Babel features that cannot be transpiled |
|bootstrap|CSS Framework|
|jquery|Only used to support toastr|
|react|React library |
|react-dom|React library for DOM rendering |
|react-redux|Redux library for connecting React components to Redux |
|react-router|React library for routing |
|react-router-redux|Keep React Router in sync with Redux application state|
|redux|Library for unidirectional data flows |
|redux-thunk|Async redux library|
|toastr|Display messages to the user|

### Development Dependencies
| **Dependency** | **Use** |
|----------|-------|
|babel-cli|Babel Command line interface |
|babel-core|Babel Core for transpiling the new JavaScript to old |
|babel-loader|Adds Babel support to Webpack |
|babel-plugin-react-display-name| Add displayName to React.createClass calls |
|babel-preset-es2015|Babel preset for ES2015|
|babel-preset-react| Add JSX support to Babel |
|babel-preset-react-hmre|Hot reloading preset for Babel|
|babel-register|Register Babel to transpile our Mocha tests|
|cheerio|Supports querying DOM with jQuery like syntax - Useful in testing and build process for HTML manipulation|
|colors|Adds color support to terminal |
|compression|Add gzip support to Express|
|cross-env|Cross-environment friendly way to handle environment variables|
|css-loader|Add CSS support to Webpack|
|enzyme|Simplified JavaScript Testing utilities for React|
|eslint|Lints JavaScript |
|eslint-plugin-import|Advanced linting of ES6 imports|
|eslint-plugin-react|Adds additional React-related rules to ESLint|
|eslint-watch|Add watch functionality to ESLint |
|eventsource-polyfill|Polyfill to support hot reloading in IE|
|expect|Assertion library for use with Mocha|
|express|Serves development and production builds|
|extract-text-webpack-plugin| Extracts CSS into separate file for production build | 
|file-loader| Adds file loading support to Webpack |
|jsdom|In-memory DOM for testing|
|mocha| JavaScript testing library |
|nock| Mock HTTP requests for testing |
|npm-run-all| Display results of multiple commands on single command line |
|open|Open app in default browser|
|react-addons-test-utils| Adds React TestUtils |
|redux-immutable-state-invariant|Warn when Redux state is mutated|
|redux-mock-store|Mock Redux store for testing|
|rimraf|Delete files |
|style-loader| Add Style support to Webpack |
|url-loader| Add url loading support to Webpack |
|webpack| Bundler with plugin system and integrated development server |
|webpack-dev-middleware| Adds middleware support to webpack |
|webpack-hot-middleware| Adds hot reloading to webpack |

**Bugs**
----------------------
1. first bug description

2. second bug description


**Future Enhancements**
----------------------
* https://react.semantic-ui.com/introduction

* to add Redux - Functional State Management

* Web Accessibility – WAI-ARIA

* Database: Mongo, Cassandra, Redis

* Webpack, ESLint, NPM scripts

* Test Driven Development: Mocha, Jasmine
