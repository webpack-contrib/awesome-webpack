<h3 align="center">
	<img width="355" src="https://raw.githubusercontent.com/d3viant0ne/awesome-webpack/master/media/logo-horizontal.png" alt="Webpack">
	<br>
</h3>
## Awesome Webpack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome Webpack resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

### Table of Contents
 - [Resources](#webpack-ecosystem)
  - [Documentation](#documentation)
  - [Community](#community)
 - [Libraries](#libraries)
   - [Loaders](#loaders)
     - [File Type](#file-type)
     - [Component & Template](#component--template)
     - [Styles](#styles)
     - [Language & Framework](#language--framework)
     - [Utility](#utility)
     - [Testing](#testing)
   - [Integrations](#integration-libraries)
   - [Plugins](#webpack-plugins)
   - [Tools](#webpack-tools)
 - [Research & Training](#research--training)
  - [Articles](#articles)
  - [Talks](#talks)
  - [Video Courses](#courses)
  - [Webpack Examples](#webpack-examples)
  - [Community Examples](#community-examples)
  - [Other](#other)

<br>
> <h2>Webpack Ecosystem</h2>

### Documentation

- [Webpack 1.x](http://webpack.github.io/docs/) - Webpack 1.x Documentation
- [Webpack 2.x](https://webpack.github.io/webpack.io/) - Webpack 2.x Documentation ( Under development )

### Community

- [Webpack StackOverflow](http://stackoverflow.com/tags/webpack)

[Back to top](#table-of-contents)

<br>
> <h2> Libraries</h2>

### Loaders
##### File Type
- [File Loader](https://github.com/webpack/file-loader): File loader module for Webpack. -- _Maintained By_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [URL Loader](https://github.com/webpack/file-loader): URL loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [HTML Loader](https://github.com/webpack/html-loader): HTML loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Raw Loader](https://github.com/webpack/raw-loader): Raw file loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Image Loader](https://github.com/thetalecrafter/img-loader): Image minimizing loader for webpack. -- _Maintainer_: `Andy VanWagoner` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/thetalecrafter) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/thetalecrafter)
- [SVG Url Loader](https://github.com/bhovhannes/svg-url-loader): Loader which loads SVG file as utf-8 encoded Url. -- _Maintainer_: `Hovhannes Babayan` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/bhovhannes)
- [json5 Loader](https://github.com/webpack/json5-loader): json5 loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [json Loader](https://github.com/webpack/json-loader): json loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)

##### Component & Template
- [Angular2 Template Loader](https://github.com/TheLarkInn/angular2-template-loader): Inlines html and style's in Angular2 components. -- _Maintainer_: `Sean Larkin` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/TheLarkInn) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/TheLarkInn)
- [Handlebars Loader](https://github.com/pcardune/handlebars-loader): A handlebars template loader for Webpack. -- _Maintainer_: `Paul Carduner` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/pcardune) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/pcardune)
- [Vue Loader](https://github.com/vuejs/vue-loader): Webpack loader for Vue.js components. -- _Maintainer_: `Vuejs Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/vuejs) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/vuejs)
- [SVG React Loader](https://github.com/jhamlet/svg-react-loader) - Webpack SVG to React Component Loader.  -- _Maintainer_: `Jerry Hamlet` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/jhamlet) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/jerryhamlet)
- [Underscore Loader](https://github.com/emaphp/underscore-template-loader) - Underscore and Lodash template loader.  -- _Maintainer_: `Emmanuel Antico` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/emaphp) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/emaphp)

##### Styles
- [Style Loader](https://github.com/webpack/style-loader): Style loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [PostCSS Loader](https://github.com/postcss/postcss-loader): PostCSS loader for Webpack. -- _Maintainer_: `PostCSS Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/postcss) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/PostCSS)
- [CSS Loader](https://github.com/webpack/css-loader): CSS loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [SASS Loader](https://github.com/jtangelder/sass-loader): SASS loader for Webpack. -- _Maintainer_: `Jorik Tangelder` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/jtangelder) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/jorikdelaporik)
- [Less Loader](https://github.com/webpack/less-loader): Less loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Stylus Loader](https://github.com/shama/stylus-loader): A stylus loader for webpack. -- _Maintainer_: `Kyle Robinson Young` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/shama) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/shamakry)
- [Isomorphic Style Loader](https://github.com/kriasoft/isomorphic-style-loader): Isomorphic CSS style loader for Webpack. -- _Maintainer_: `Kriasoft Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/kriasoft) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/kriasoft)

##### Language & Framework
- [TS Loader](https://github.com/TypeStrong/ts-loader): TypeScript loader for webpack. -- _Maintainer_: `TypeStrong Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/TypeStrong)
- [Awesome TypeScript Loader](https://github.com/s-panferov/awesome-typescript-loader): Awesome TS loader for Webpack. -- _Maintainer_: `Stanislav Panferov` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/s-panferov) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/babel)
- [Coffee Loader](https://github.com/webpack/coffee-loader): Coffee loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Bootstrap Loader](https://github.com/shakacode/bootstrap-loader): Load Bootstrap styles in your Webpack bundle. -- _Maintainer_: `ShakaCode Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/shakacode) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/shakacode)
- [PostHTML Loader](https://github.com/posthtml/posthtml): PostHTML loader for Webpack. -- _Maintainer_: `PostHTML Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/posthtml) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/PostHTML)
- [ELM Loader](https://github.com/rtfeldman/elm-webpack-loader): Webpack loader for the Elm programming language. -- _Maintainer_: `Richard Feldman` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/rtfeldman) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/rtfeldman)

##### Utility
- [Babel Loader](https://github.com/babel/babel-loader): Webpack plugin for Babel. -- _Maintainer_: `Babel Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/babel) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/babel)
- [ESLint Loader](https://github.com/MoOx/eslint-loader): ESLint loader for Webpack. -- _Maintainer_: `Maxime Thirouin` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/MoOx) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/MoOx)
- [StyleLint Loader](https://github.com/adrianhall/stylelint-loader): A Webpack Loader for linting SASS, SCSS & CSS. -- _Maintainer_: `Adrian Hall` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/adrianhall) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/FizzyInTheHall)
- [JSHint Loader](https://github.com/webpack/jshint-loader): JSHint loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [JSCS Loader](https://github.com/unindented/jscs-loader): Run your source through the JSCS style checker. -- _Maintainer_: `Daniel Perez Alvarez` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/unindented)
- [JSHint Loader](https://github.com/webpack/jshint-loader): JSHint loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Bundle Loader](https://github.com/webpack/bundle-loader): Bundle loader for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Worker Loader](https://github.com/webpack/worker-loader): Worker loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [JSCS Loader](https://github.com/unindented/jscs-loader): Resolves relative paths in url() statements. -- _Maintainer_: `Ben Holloway` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/bholloway)
- [Import Loader](https://github.com/webpack/imports-loader): Imports loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [SourceMap Loader](https://github.com/webpack/source-map-loader): Extract sourceMappingURL comments from modules. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)

##### Testing
- [Mocha Loader](https://github.com/webpack/mocha-loader): Mocha loader module for Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Karma Webpack](https://github.com/webpack/karma-webpack): Use Karma with Webpack. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)

[Back to top](#table-of-contents)

<br>
### Integration Libraries
- [Terse Webpack](https://github.com/ericclemmons/npm-install-webpack-plugin) - Webpack simplified in a fluent API with presets.  -- _Maintainer_: `Eric Clemmons` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/ericclemmons) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/ericclemmons)
- [SystemJS Webpack](https://github.com/guybedford/systemjs-webpack-plugin) - Webpack bundling for SystemJS.  -- _Maintainer_: `Guy Bedford` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/guybedford) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/guybedford)
- [Gulp Webpack Stream](https://github.com/shama/webpack-stream) - Run webpack through a stream interface.  -- _Maintainer_: `Kyle Robinson Young` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/shama) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/shamakry)

[Back to top](#table-of-contents)

<br>
### Webpack Plugins
- [Exact Text Plugin](https://github.com/webpack/extract-text-webpack-plugin): Extract text from bundle into a file. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Compression Plugin](https://github.com/webpack/compression-webpack-plugin): Prepare assets to serve with Content-Encoding. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Offline Plugin](https://github.com/NekR/offline-plugin): Offline plugin (ServiceWorker, AppCache) for Webpack. -- _Maintainer_: `Arthur Stolyar` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/NekR) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/nekrtemplar)
- [Rewire Plugin](https://github.com/jhnns/rewire-webpack): Dependency injection for Webpack bundles. -- _Maintainer_: `Johannes Ewald` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/jhnns) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/Jhnnns)
- [HTML Webpack Plugin](https://github.com/ampedandwired/html-webpack-plugin): Simplifies creation of HTML files. -- _Maintainer_: `Charles Blaxland` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/ampedandwired) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/ampedandwired)
- [Copy Webpack Plugin](https://github.com/kevlened/copy-webpack-plugin): Copy files and directories in webpack. -- _Maintainer_: `Len Boyette` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/kevlened) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/kevlened)

[Back to top](#table-of-contents)

<br>
### Webpack Tools
- [Webpack Dev Middleware](https://github.com/webpack/webpack-dev-middleware): Middleware which arguments a live bundle. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [Webpack Dev Server](https://github.com/webpack/webpack-dev-server): Serves a webpack app. Updates the browser on changes. -- _Maintainer_: `Webpack Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/webpack)
- [NPM Install Webpack](https://github.com/ericclemmons/npm-install-webpack-plugin) - Automatically install & save deps with Webpack.  -- _Maintainer_: `Eric Clemmons` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/ericclemmons) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/ericclemmons)
- [webpack-validator](https://github.com/js-dxtools/webpack-validator) - Validates your webpack config with Joi.  -- _Maintainer_: `js-dxtools Team` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/js-dxtools)
- [webpack-config-utils](https://github.com/kentcdodds/webpack-config-utils) - Util. to make your webpack config easier to read.  -- _Maintainer_: `Kent C. Dodds` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/kentcdodds) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/kentcdodds)
- [webpack-combine-loaders](https://www.npmjs.com/package/webpack-combine-loaders) - Converts a loaders array into a single loader string.  -- _Maintainer_: `James Friend` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/jsdf)
- [Angular2 Webpack Toolkit](https://github.com/AngularClass/webpack-toolkit) - Webpack tools and helpers for Angular 2.  -- _Maintainer_: `AngularClass` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/AngularClass) [![Twitter](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg)](https://twitter.com/AngularClass)
- [HJS Webpack](https://github.com/HenrikJoreteg/hjs-webpack): Helpers/presets for setting up webpack with hotloading. -- _Maintainer_: `Henrik Joreteg` [![Github](https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg)](https://github.com/HenrikJoreteg)

[Back to top](#table-of-contents)

<br>
> <h2> Research & Training</h2>

### Articles
- [Jamund Ferguson | 22-Jul-16](https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44#.lbvkidezh) - Manually Tuning Webpack Builds.
- [Sean T. Larkin | 21-Jul-16](https://medium.com/webpack/webpack-bits-learn-and-debug-webpack-with-chrome-dev-tools-da1c5b19554#.gpoentuxe) - Learn and Debug webpack with Chrome Dev Tools!.
- [Raja Rao DV | 10-Apr-16](https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9#.qmfmplobc) - Webpack  —  The Confusing Parts.
- [Jonathan Creamer | 25-Feb-16](http://jonathancreamer.com/webpack-code-splitting-with-es6-and-babel-6/) - WebPack Code splitting with ES6 and Babel 6.
- [Grgur Grisogono | 15-Feb-16](https://medium.com/@somebody32/how-to-split-your-apps-by-routes-with-webpack-36b7a8a6231#.iy99i4f7r) - Webpack 2 Tree Shaking Configuration.
- [Ilya Zayats | 07-Feb-16](https://medium.com/modus-create-front-end-development/webpack-2-tree-shaking-configuration-9f1de90f3233#.5pddvz5lz) - How to split your apps by routes with Webpack.
- [Jonathan Creamer | 10-Jan-16](http://jonathancreamer.com/advanced-webpack-part-2-code-splitting/) - Advanced WebPack Part 2 - Code Splitting.
- [Andy Ccs | 02-Jan-16](https://medium.com/@andyccs/webpack-and-docker-for-development-and-deployment-ae0e73243db4#.2yutcm8s4) - Webpack and Docker for Development and Deployment.
- [Jonathan Creamer | 08-Jun-16](http://jonathancreamer.com/advanced-webpack-part-3-creating-a-custom-notifier-plugin/) - Advanced WebPack Part 3 - Creating a custom notifier plugin.
- [Nader Dabit | 07-Sept-15](https://medium.com/@dabit3/beginner-s-guide-to-webpack-b1f1a3638460#.xb01fcsoq) - Beginner’s guide to Webpack.
- [Jonathan Creamer | 02-Sept-15](http://jonathancreamer.com/advanced-webpack-part-1-the-commonschunk-plugin/) - Advanced WebPack Part 1 - The CommonsChunk Plugin.

### Talks

### Courses
- [Intro to webpack (playlist)](https://egghead.io/playlists/intro-to-webpack-4ca2d994) - Egghead.io playlist of a few videos (the first is free).
- [Angular and Webpack for modular applications](https://egghead.io/courses/angular-and-webpack-for-modular-applications) - Egghead.io course
- [Using Webpack for Production JavaScript Applications](https://egghead.io/courses/using-webpack-for-production-javascript-applications) - Egghead.io course (advanced)

### Webpack Examples
- [Webpack Examples](https://github.com/webpack/webpack/tree/master/examples): Examples of common Webpack functionality.

### Community Examples
- [ES6 TodoMVC with Webpack](https://github.com/kentcdodds/es6-todomvc) - Repo used to teach webpack. (Check out the branches).
- [Angular2 Webpack Starter](https://github.com/AngularClass/angular2-webpack-starter) - A Webpack driven Angular 2 Starter kit from [AngularClass](https://github.com/AngularClass).

### Other
- [026 - webpack](http://jsair.io/webpack) - [JavaScript Air](https://javascriptair.com/) podcast

[Back to top](#table-of-contents)
