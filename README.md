<h3 align="center">
	<img width="355" src="https://raw.githubusercontent.com/webpack-contrib/awesome-webpack/master/media/awesome_webpack_branding.png" alt="awesome-webpack">
	<br>
</h3>

**[webpack](https://github.com/webpack/webpack)** is a **module bundler**.

webpack takes modules with dependencies and generates static assets representing those modules.
<br>
## Awesome Webpack [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/webpack-contrib/awesome-webpack.svg?branch=master)](https://travis-ci.org/webpack-contrib/awesome-webpack)

> A curated list of awesome Webpack resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list. Feel free to improve this list by [contributing](https://github.com/webpack-contrib/awesome-webpack/blob/master/contributing.md)!
<!--lint disable list-item-indent-->

### Contents

- [Resources](#webpack-ecosystem)
  - [Documentation](#documentation)
  - [Community](#community)
  - [Twitter Follows](#twitter)
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
  - [Videos](#videos)
  - [Courses](#courses)
  - [Books](#books)
  - [Webpack Examples](#webpack-examples)
  - [Community Examples](#community-examples)
    - [Angular](#angular)
    - [Framework Agnostic](#framework-agnostic)
    - [React](#react)
  - [Other](#other)

<!--lint disable list-item-indent-->

## Webpack Ecosystem

&nbsp; &nbsp; **Remember to** [Cast your vote for upcoming Webpack features!](https://webpack.js.org/vote/)

### Support Webpack

- [Webpack Open Collective](https://opencollective.com/webpack) - Help support the teams ongoing development efforts.

### Documentation

- [Webpack 1.x](http://webpack.github.io/docs/) - Webpack 1.x Documentation
- [Webpack 2.x](https://webpack.js.org//) - Webpack 2.x Documentation

### Community

- [StackOverflow](http://stackoverflow.com/tags/webpack)
- [Medium](https://medium.com/tag/webpack)
- [Gitter Chat](https://gitter.im/webpack/webpack)

### Twitter

*People passionate about Webpack (In no particular order)*

- [Sean T. Larkin - @TheLarkInn](https://twitter.com/TheLarkInn) UX for [Mutual of Omaha](https://github.com/mutualofomaha). Developer Advocate and webpack core team member.
- [Juho Vepsäläinen - @bebraw](https://twitter.com/bebraw) from [SurviveJS](https://twitter.com/survivejs) and webpack core team member.
- [Eric Clemmons - @ericclemmons](https://twitter.com/ericclemmons) VP of Software Development at [HigherEdHQ](https://twitter.com/HigherEdHQ). Webpack member.
- [Patrick Stapleton - @gdi2290](https://twitter.com/gdi2290) from [AngularClass](https://angularclass.com), [AngularAir](https://angularair.com) and [Angular Universal](https://github.com/angular/universal). Webpack member.
- [Kent C. Dodds - @kentcdodds](https://twitter.com/kentcdodds) from [PayPal Engineering](https://twitter.com/PayPalEng) and [JavaScript Air](https://twitter.com/JavaScriptAir). Webpack member.
- [Johannes Ewald - @Jhnnns](https://twitter.com/Jhnnns): Webpack core team member.
- [Joshua Wiens - @d3viant0ne](https://twitter.com/d3viant0ne): Technical Lead for [EasyMetrics](https://easymetrics.com). Webpack member.
- [Jonathan Creamer - @jcreamer898](https://twitter.com/jcreamer898): Microsoft MVP and [Telerik](https://github.com/telerik) Developer Expert.
- [Kees Kluskens - @keeskluskens](https://twitter.com/keeskluskens): - Software Engineer at [Code Yellow](https://codeyellow.nl),  Webpack core team member.

[Back to top](#table-of-contents)


## Libraries

### Loaders

#### File Type

- [File Loader](https://github.com/webpack/file-loader): File loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [URL Loader](https://github.com/webpack/url-loader): URL loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [HTML Loader](https://github.com/webpack/html-loader): HTML loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Raw Loader](https://github.com/webpack/raw-loader): Raw file loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Image Loader](https://github.com/thetalecrafter/img-loader): Image minimizing loader for webpack. -- *Maintainer*: `Andy VanWagoner` [![Github][githubicon]](https://github.com/thetalecrafter) [![Twitter][twittericon]](https://twitter.com/thetalecrafter)
- [SVG Url Loader](https://github.com/bhovhannes/svg-url-loader): Loader which loads SVG file as utf-8 encoded Url. -- *Maintainer*: `Hovhannes Babayan` [![Github][githubicon]](https://github.com/bhovhannes)
- [json5 Loader](https://github.com/webpack/json5-loader): json5 loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [json Loader](https://github.com/webpack/json-loader): json loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [mermaid Loader](https://github.com/popul/mermaid-loader): [mermaid](http://knsv.github.io/mermaid/) loader module (diagrams) for Webpack. -- *Maintainer*: `Paul Musso` [![Github][githubicon]](https://github.com/popul)
- [wasm loader](https://github.com/ballercat/wasm-loader): wasm binary loader module for Webpack. -- *Maintainer*: `Arthur Buldauskas` [![Github][githubicon]](https://github.com/wasm-loader)

#### Component & Template

- [Angular2 Template Loader](https://github.com/TheLarkInn/angular2-template-loader): Inlines html and style's in Angular2 components. -- *Maintainer*: `Sean Larkin` [![Github][githubicon]](https://github.com/TheLarkInn) [![Twitter][twittericon]](https://twitter.com/TheLarkInn)
- [Handlebars Loader](https://github.com/pcardune/handlebars-loader): A handlebars template loader for Webpack. -- *Maintainer*: `Paul Carduner` [![Github][githubicon]](https://github.com/pcardune) [![Twitter][twittericon]](https://twitter.com/pcardune)
- [Vue Loader](https://github.com/vuejs/vue-loader): Webpack loader for Vue.js components. -- *Maintainer*: `Vuejs Team` [![Github][githubicon]](https://github.com/vuejs) [![Twitter][twittericon]](https://twitter.com/vuejs)
- [SVG React Loader](https://github.com/jhamlet/svg-react-loader) - Webpack SVG to React Component Loader.  -- *Maintainer*: `Jerry Hamlet` [![Github][githubicon]](https://github.com/jhamlet) [![Twitter][twittericon]](https://twitter.com/jerryhamlet)
- [Underscore Loader](https://github.com/emaphp/underscore-template-loader) - Underscore and Lodash template loader.  -- *Maintainer*: `Emmanuel Antico` [![Github][githubicon]](https://github.com/emaphp) [![Twitter][twittericon]](https://twitter.com/emaphp)
- [ngTemplate Loader](https://github.com/WearyMonkey/ngtemplate-loader) - Angular1 Template Loader.  -- *Maintainer*: `Toby Rahilly` [![Github][githubicon]](https://github.com/WearyMonkey)
- [ngInlineStylesLoader](https://github.com/seveves/ng-inline-styles-loader): Optimizes inlined css of angular components. -- *Maintainer*: `Severin Friede` [![Github][githubicon]](https://github.com/seveves)

#### Styles

- [Style Loader](https://github.com/webpack/style-loader): Style loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [PostCSS Loader](https://github.com/postcss/postcss-loader): PostCSS loader for Webpack. -- *Maintainer*: `PostCSS Team` [![Github][githubicon]](https://github.com/postcss) [![Twitter][twittericon]](https://twitter.com/PostCSS)
- [CSS Loader](https://github.com/webpack/css-loader): CSS loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SASS Loader](https://github.com/jtangelder/sass-loader): SASS loader for Webpack. -- *Maintainer*: `Jorik Tangelder` [![Github][githubicon]](https://github.com/jtangelder) [![Twitter][twittericon]](https://twitter.com/jorikdelaporik)
- [Less Loader](https://github.com/webpack/less-loader): Less loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Stylus Loader](https://github.com/shama/stylus-loader): A stylus loader for webpack. -- *Maintainer*: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Isomorphic Style Loader](https://github.com/kriasoft/isomorphic-style-loader): Isomorphic CSS style loader for Webpack. -- *Maintainer*: `Kriasoft Team` [![Github][githubicon]](https://github.com/kriasoft) [![Twitter][twittericon]](https://twitter.com/kriasoft)

#### Language & Framework

- [TS Loader](https://github.com/TypeStrong/ts-loader): TypeScript loader for webpack. -- *Maintainer*: `TypeStrong Team` [![Github][githubicon]](https://github.com/TypeStrong)
- [Awesome TypeScript Loader](https://github.com/s-panferov/awesome-typescript-loader): Awesome TS loader for Webpack. -- *Maintainer*: `Stanislav Panferov` [![Github][githubicon]](https://github.com/s-panferov) [![Twitter][twittericon]](https://twitter.com/babel)
- [Coffee Loader](https://github.com/webpack/coffee-loader): Coffee loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Bootstrap Loader](https://github.com/shakacode/bootstrap-loader): Load Bootstrap styles in your Webpack bundle. -- *Maintainer*: `ShakaCode Team` [![Github][githubicon]](https://github.com/shakacode) [![Twitter][twittericon]](https://twitter.com/shakacode)
- [PostHTML Loader](https://github.com/posthtml/posthtml): PostHTML loader for Webpack. -- *Maintainer*: `PostHTML Team` [![Github][githubicon]](https://github.com/posthtml) [![Twitter][twittericon]](https://twitter.com/PostHTML)
- [ELM Loader](https://github.com/rtfeldman/elm-webpack-loader): Webpack loader for the Elm programming language. -- *Maintainer*: `Richard Feldman` [![Github][githubicon]](https://github.com/rtfeldman) [![Twitter][twittericon]](https://twitter.com/rtfeldman)

#### Utility

- [Babel Loader](https://github.com/babel/babel-loader): Webpack plugin for Babel. -- *Maintainer*: `Babel Team` [![Github][githubicon]](https://github.com/babel) [![Twitter][twittericon]](https://twitter.com/babel)
- [ESLint Loader](https://github.com/MoOx/eslint-loader): ESLint loader for Webpack. -- *Maintainer*: `Maxime Thirouin` [![Github][githubicon]](https://github.com/MoOx) [![Twitter][twittericon]](https://twitter.com/MoOx)
- [JSHint Loader](https://github.com/webpack/jshint-loader): JSHint loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [JSCS Loader](https://github.com/unindented/jscs-loader): Run your source through the JSCS style checker. -- *Maintainer*: `Daniel Perez Alvarez` [![Github][githubicon]](https://github.com/unindented)
- [Bundle Loader](https://github.com/webpack/bundle-loader): Bundle loader for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Worker Loader](https://github.com/webpack/worker-loader): Worker loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Resolve URL Loader](https://github.com/bholloway/resolve-url-loader): Resolves relative paths in url() statements. -- *Maintainer*: `Ben Holloway` [![Github][githubicon]](https://github.com/bholloway)
- [Import Loader](https://github.com/webpack/imports-loader): Imports loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SourceMap Loader](https://github.com/webpack/source-map-loader): Extract sourceMappingURL comments from modules. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Combine Loader](https://www.npmjs.com/package/webpack-combine-loaders) - Converts a loaders array into a single loader string.  -- *Maintainer*: `James Friend` [![Github][githubicon]](https://github.com/jsdf)
- [Icon Font Loader](https://www.npmjs.com/package/icons-loader) - Generates an iconfont from SVG dependencies.  -- *Maintainer*: `Mike Vercoelen` [![Github][githubicon]](https://github.com/mikevercoelen)
- [Modernizr Loader](https://www.npmjs.com/package/modernizr-loader) - Get your modernizr build bundled with webpack. -- *Maintainer*: `Peerigon Devs` [![Github][githubicon]](https://github.com/peerigon)
- [ngRouter Loader](https://github.com/shlomiassaf/ng-router-loader) - AOT capable NgModule lazy loading using angular router -- *Maintainer*: `Shlomi Assaf` [![Github][githubicon]](https://github.com/shlomiassaf) [![Twitter][twittericon]](https://twitter.com/shlomiassaf)

#### Testing

- [Mocha Loader](https://github.com/webpack/mocha-loader): Mocha loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Karma Webpack](https://github.com/webpack/karma-webpack): Use Karma with Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Istanbul Webpack plugin](https://github.com/DxCx/webpack-istanbul-plugin): Use Istanbul instrumenter for the whole pack. -- *Maintainer*: `Hagai Cohen` [![Github][githubicon]](https://github.com/DxCx)

[Back to top](#table-of-contents)

### Integration Libraries

- [Terse Webpack](https://github.com/ericclemmons/terse-webpack) - Webpack simplified in a fluent API with presets.  -- *Maintainer*: `Eric Clemmons` [![Github][githubicon]](https://github.com/ericclemmons) [![Twitter][twittericon]](https://twitter.com/ericclemmons)
- [SystemJS Webpack](https://github.com/guybedford/systemjs-webpack-plugin) - Webpack bundling for SystemJS.  -- *Maintainer*: `Guy Bedford` [![Github][githubicon]](https://github.com/guybedford) [![Twitter][twittericon]](https://twitter.com/guybedford)
- [Gulp Webpack Stream](https://github.com/shama/webpack-stream) - Run webpack through a stream interface.  -- *Maintainer*: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Webpack Blocks](https://github.com/andywer/webpack-blocks) - Configure webpack using functional feature blocks.  -- *Maintainer*: `Andy Wermke` [![Github][githubicon]](https://github.com/andywer) [![Twitter][twittericon]](https://twitter.com/andywritescode)
- [Webpacker](https://github.com/rails/webpacker) - Offical webpack gem for integration into ruby on rails projects  -- *Maintainer*: `Rails` [![Github][githubicon]](https://github.com/rails)

[Back to top](#table-of-contents)

### Webpack Plugins

- [Extract Text Plugin](https://github.com/webpack/extract-text-webpack-plugin): Extract text from bundle into a file. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [DefinePlugin](https://webpack.js.org/plugins/define-plugin/): Create global constants which can be configured at compile time. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Compression Plugin](https://github.com/webpack/compression-webpack-plugin): Prepare assets to serve with Content-Encoding. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Offline Plugin](https://github.com/NekR/offline-plugin): Offline plugin (ServiceWorker, AppCache) for Webpack. -- *Maintainer*: `Arthur Stolyar` [![Github][githubicon]](https://github.com/NekR) [![Twitter][twittericon]](https://twitter.com/nekrtemplar)
- [Rewire Plugin](https://github.com/jhnns/rewire-webpack): Dependency injection for Webpack bundles. -- *Maintainer*: `Johannes Ewald` [![Github][githubicon]](https://github.com/jhnns) [![Twitter][twittericon]](https://twitter.com/Jhnnns)
- [HTML Webpack Plugin](https://github.com/ampedandwired/html-webpack-plugin): Simplifies creation of HTML files. -- *Maintainer*: `Jan Nicklas` [![Github][githubicon]](https://github.com/jantimon) [![Twitter][twittericon]](https://twitter.com/jantimon)
- [Copy Webpack Plugin](https://github.com/kevlened/copy-webpack-plugin): Copy files and directories in webpack. -- *Maintainer*: `Len Boyette` [![Github][githubicon]](https://github.com/kevlened) [![Twitter][twittericon]](https://twitter.com/kevlened)
- [Split By Path](https://github.com/BohdanTkachenko/webpack-split-by-path): Split By Path Webpack Plugin. -- *Maintainer*: `Bohdan Tkachenko` [![Github][githubicon]](https://github.com/BohdanTkachenko) [![Twitter][twittericon]](https://twitter.com/bohdantkachenko)
- [SW Precache](https://github.com/goldhand/sw-precache-webpack-plugin) - Generates a service worker to precache bundle. -- *Maintainer*: `Will Farley` [![Github][githubicon]](https://github.com/goldhand)
- [CoreJS Plugin](https://github.com/gdi2290/core-js-webpack-plugin) - Core-JS as a webpack plugin. -- *Maintainer*: `PatrickJS` [![Github][githubicon]](https://github.com/gdi2290)
- [Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer) - Utility that represents bundles as an interactive treemap. -- *Maintainer*: `Yuriy Grunin` [![Github][githubicon]](https://github.com/th0r)
- [Module Mapping](https://github.com/spartez/module-mapping-webpack-plugin) - Maps modules onto different files. -- *Maintainer*: `Spartez Team` [![Github][githubicon]](https://github.com/spartez) [![Twitter][twittericon]](https://twitter.com/thisisspartez)
- [Serverless Webpack](https://github.com/elastic-coders/serverless-webpack) - Serverless plugin to bundle your lambdas. -- *Maintainer*: `Elastic Coders` [![Github][githubicon]](https://github.com/elastic-coders) [![Twitter][twittericon]](https://twitter.com/ElasticCoders)
- [Prerender SPA](https://github.com/chrisvfritz/prerender-spa-plugin) - Framework-agnostic static site generation for SPAs. -- *Maintainer*: `Chris Fritz` [![Github][githubicon]](https://github.com/chrisvfritz) [![Twitter][twittericon]](https://twitter.com/chrisvfritz)
- [SVG Sprite Webpack Plugin](https://github.com/TodayTix/svg-sprite-webpack-plugin) - Plugin for SVG sprites and icons. -- *Maintainer*: `Jeremy Tice` ([`TodayTix`](https://github.com/TodayTix)) [![Github][githubicon]](https://github.com/jetpacmonkey) [![Twitter][twittericon]](https://twitter.com/jetpacmonkey)
- [Imagemin Webpack Plugin](https://github.com/Klathmon/imagemin-webpack-plugin) - Minify images with Imagemin. -- *Maintainer*: `Gregory Benner` [![Github][githubicon]](https://github.com/Klathmon) [![Twitter][twittericon]](https://twitter.com/Klathmon)

[Back to top](#table-of-contents)

### Webpack Tools

- [Webpack Dev Middleware](https://github.com/webpack/webpack-dev-middleware): Middleware which arguments a live bundle. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Webpack Dev Server](https://github.com/webpack/webpack-dev-server): Serves a webpack app. Updates the browser on changes. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Webpack Merge](https://github.com/survivejs/webpack-merge) - Merge designed for Webpack.  -- *Maintainer*: `Juho Vepsäläinen` [![Github][githubicon]](https://github.com/bebraw) [![Twitter][twittericon]](https://twitter.com/bebraw)
- [NPM Install Webpack](https://github.com/ericclemmons/npm-install-webpack-plugin) - Automatically install & save deps with Webpack.  -- *Maintainer*: `Eric Clemmons` [![Github][githubicon]](https://github.com/ericclemmons) [![Twitter][twittericon]](https://twitter.com/ericclemmons)
- [Webpack Validator](https://github.com/js-dxtools/webpack-validator) - Validates your webpack config with Joi.  -- *Maintainer*: `js-dxtools Team` [![Github][githubicon]](https://github.com/js-dxtools)
- [Webpack Config Utils](https://github.com/kentcdodds/webpack-config-utils) - Util. to make your webpack config easier to read.  -- *Maintainer*: `Kent C. Dodds` [![Github][githubicon]](https://github.com/kentcdodds) [![Twitter][twittericon]](https://twitter.com/kentcdodds)
- [Angular2 Webpack Toolkit](https://github.com/AngularClass/webpack-toolkit) - Webpack tools and helpers for Angular 2.  -- *Maintainer*: `AngularClass` [![Github][githubicon]](https://github.com/AngularClass) [![Twitter][twittericon]](https://twitter.com/AngularClass)
- [Webpack Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer) - Represents bundles as an interactive treemap.  -- *Maintainer*: `Yuriy Grunin` [![Github][githubicon]](https://github.com/th0r) [![Twitter][twittericon]](https://twitter.com/grunin_ya)
- [HJS Webpack](https://github.com/HenrikJoreteg/hjs-webpack): Helpers/presets for setting up webpack with hotloading. -- *Maintainer*: `Henrik Joreteg` [![Github][githubicon]](https://github.com/HenrikJoreteg)
- [Webpack Dashboard](https://github.com/FormidableLabs/webpack-dashboard): A CLI dashboard for webpack dev server. -- *Maintainer*: `Formidable Labs` [![Github][githubicon]](https://github.com/FormidableLabs)

[Back to top](#table-of-contents)

## Research & Training

### Articles

- Mark Erikson | 07-Mar-17 - [Declaratively Rendering Earth in 3D, Part 1: Building a Cesium + React App with Webpack](http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-1-cesium-webpack/)
- Joseph Zimmerman | 2-Feb-17 - [A Detailed Introduction To Webpack.](https://www.smashingmagazine.com/2017/02/a-detailed-introduction-to-webpack/)
- Jamund Ferguson | 22-Jul-16 - [Manually Tuning Webpack Builds.](https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44#.lbvkidezh)
- Sean T. Larkin | 21-Jul-16 - [Learn and Debug webpack with Chrome Dev Tools!.](https://medium.com/webpack/webpack-bits-learn-and-debug-webpack-with-chrome-dev-tools-da1c5b19554#.gpoentuxe)
- Raja Rao DV | 10-Apr-16 - [Webpack  —  The Confusing Parts.](https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9#.qmfmplobc)
- Andrew Ray | 09-Apr-16 - [Webpack: When To Use and Why.](http://blog.andrewray.me/webpack-when-to-use-and-why/)
- Jonathan Creamer | 25-Feb-16 - [WebPack Code splitting with ES6 and Babel 6.](http://jonathancreamer.com/webpack-code-splitting-with-es6-and-babel-6/)
- Grgur Grisogono | 15-Feb-16 - [Webpack 2 Tree Shaking Configuration.](https://medium.com/@somebody32/how-to-split-your-apps-by-routes-with-webpack-36b7a8a6231#.iy99i4f7r)
- Ilya Zayats | 07-Feb-16 - [How to split your apps by routes with Webpack.](https://medium.com/modus-create-front-end-development/webpack-2-tree-shaking-configuration-9f1de90f3233#.5pddvz5lz)
- Sebastian De Deyne | 04-Feb-16 - [Adventure Time With Webpack.](https://sebastiandedeyne.com/posts/2016/adventure-time-with-webpack)
- Jonathan Creamer | 10-Jan-16 - [Advanced WebPack Part 2 - Code Splitting.](http://jonathancreamer.com/advanced-webpack-part-2-code-splitting)
- Andy Ccs | 02-Jan-16 - [Webpack and Docker for Development and Deployment.](https://medium.com/@andyccs/webpack-and-docker-for-development-and-deployment-ae0e73243db4#.2yutcm8s4)
- Jonathan Creamer | 08-Jun-16 - [Advanced WebPack Part 3 - Creating a custom notifier plugin.](http://jonathancreamer.com/advanced-webpack-part-3-creating-a-custom-notifier-plugin)
- Nader Dabit | 07-Sept-15 - [Beginner’s guide to Webpack.](https://medium.com/@dabit3/beginner-s-guide-to-webpack-b1f1a3638460#.xb01fcsoq)
- Jonathan Creamer | 02-Sept-15 - [Advanced WebPack Part 1 - The CommonsChunk Plugin.](http://jonathancreamer.com/advanced-webpack-part-1-the-commonschunk-plugin/)
- Maxime Fabre | 16-Oct-15 - [Webpack your bags.](https://blog.madewithlove.be/post/webpack-your-bags/?utm_content=buffer480f4&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

### Videos

- Naomi A. Jacobs via BuzzJS 2.0 2017 | Feb-27-2017 - [Webpack: It's Not Magic](https://www.youtube.com/watch?v=_QEM9kdV-b0)
- Jack Franklin at HalfStack2016 | 18-Nov-16 | [Seamless client side JavaScript w/ Webpack](https://opbeat.com/community/posts/seamless-client-side-javascript-with-webpack-by-jack-franklin)
- Emil Oberg via YouTube |  Nov-4-2016 - [Introduction to Webpack 2, what is it?](https://www.youtube.com/watch?v=C_ZtQClrVYw)
- Emil Oberg via YouTube | Nov-4-2016 - [Webpack 2 - A full tutorial](https://www.youtube.com/watch?v=eWmkBNBTbMM)
- Sean Larkin NEJS Conf | 30-Sep-16 | [Webpack: Core Concepts](https://www.youtube.com/watch?v=AZPYL30ozCY&feature=youtu.be)
- Front End Center Webpack from First Principles | 22-Aug-16 - [Intro to Webpack](https://www.youtube.com/watch?v=WQue1AN93YU)
- Sean Larkin on AngularAir | 03-Aug-16 - [ngAir 75 - Webpack 2 with Sean Larkin.](https://plus.google.com/events/c76mih8qcjj0ffocpdlcbegvejs)
- Eric Clemmons chat with Kent C. Dodds | 01-Jul-16 - [Webpack HMR.](https://www.youtube.com/watch?v=PthDwpgrhmQ)
- Mirko Nasato (5 Part Series) | 07-Jun-16 - [Angular2 with Webpack Project Setup.](https://www.youtube.com/playlist?list=PLgGUMhSgtxJyIQ4vI3BzlCzZLHL79Ew6p)
- Jonathan Creamer at Nodevember | 05-Dec-15 - [Advanced WebPack.](https://www.youtube.com/watch?v=MzVFrIAwwS8)
- Kyle Robinson Young | 08-Jul-15 - [Getting Started with Webpack.](https://www.youtube.com/watch?v=TaWKUpahFZM)
- Tasveer Singh at TorontoJS Tech Talk | 09-Apr-15 - [Webpack.](https://www.youtube.com/watch?v=TaWKUpahFZM)
- Jeremy Lund at Mountain West JS | 28-Mar-15 - [Gift Wrap Your Code with Webpack.](https://www.youtube.com/watch?v=ANMN9M9LhNQ)

### Courses

- [Webpack for Everyone](https://laracasts.com/series/webpack-for-everyone) - Free Laracasts series by [Jeffrey Way](http://twitter.com/jeffrey_way)
- [Intro to webpack (playlist)](https://egghead.io/playlists/intro-to-webpack-4ca2d994) - Egghead.io playlist of a few videos by [Kent C. Dodds](https://twitter.com/kentcdodds) (the first is free).
- [Angular and Webpack for modular applications](https://egghead.io/courses/angular-and-webpack-for-modular-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds)
- [Using Webpack for Production JavaScript Applications](https://egghead.io/courses/using-webpack-for-production-javascript-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds) (advanced)
- [Webpack Fundamentals](https://www.pluralsight.com/courses/webpack-fundamentals) - [Joe Eames](https://twitter.com/josepheames) for Pluralsight (intermediate)

### Books

- [SurviveJS - Webpack](http://survivejs.com/webpack/introduction): Free book guiding from a webpack apprentice to master. Covers development, production, and advanced topics.

### Webpack Examples

- [Webpack Examples](https://github.com/webpack/webpack/tree/master/examples): Examples of common Webpack functionality.

### Community Examples

#### Angular

- [Angular2 Webpack Starter](https://github.com/AngularClass/angular2-webpack-starter) - A Webpack driven Angular 2 Starter kit from [AngularClass](https://github.com/AngularClass).
- [Angular2 Webpack](https://github.com/preboot/angular2-webpack) - A complete, yet simple, starter for Angular 2 using Webpack from [Preboot](https://github.com/preboot).
- [Angular2 Webpack Visual Studio](https://github.com/damienbod/Angular2WebpackVisualStudio) - ASP.NET Core, Angular2 with Webpack and Visual Studio from [Damien Bod](https://github.com/damienbod).
- [Angular2 Starter](https://github.com/schempy/angular2-typescript-webpack) - Angular2 starter kit with Typescript and Webpack from [Brian Schemp](https://github.com/schempy).
- [Angular2 SPA](https://github.com/aspnet/JavaScriptServices/tree/dev/templates/Angular2Spa) - Angular 2 ASP.NET Core Spa from [Steve Sanderson](https://github.com/SteveSandersonMS).
- [Angular2 Seed](https://github.com/angular/angular2-seed/) - A simple starter demonstrating the basic concepts of Angular2 from [Pawel Kozlowski](https://github.com/pkozlowski-opensource).

#### Framework Agnostic

- [ES6 TodoMVC with Webpack](https://github.com/kentcdodds/es6-todomvc) - Repo used to teach webpack. (Check branches).  from [Kent C. Dodds](https://github.com/kentcdodds).

#### React

- [Create React App](https://github.com/facebookincubator/create-react-app) - Create React apps with no build configuration from [Dan Abramov](https://github.com/gaearon).
- [React Starter Kit](https://github.com/kriasoft/react-starter-kit) - Isomorphic web app boilerplate from [Kriasoft Team](https://github.com/kriasoft).
- [React Redux Universal](https://github.com/erikras/react-redux-universal-hot-example) - A starter boilerplate for a universal webapp from [Erik Rasmussen](https://github.com/erikras).
- [Frontend Boilerplate](https://github.com/tj/frontend-boilerplate) - A boilerplate of things that mostly shouldn't exist from [TJ Holowaychuk](https://github.com/tj).
- [ReactGo](https://github.com/reactGo/reactGo) - Your One-Stop solution for a full-stack universal Redux from [Ken Ding](https://github.com/choonkending).
- [React Native Calculator](https://github.com/benoitvallon/react-native-nw-react-calculator) - Mobile, desktop and website Apps with the same code from [Benoit Vallon](https://github.com/benoitvallon).
- [React Cordova Boilerplate](https://github.com/unimonkiez/react-cordova-boilerplate) - TodoMVC example for React with Cordova from [Yuval Saraf](https://github.com/unimonkiez).
- [React Universally](https://github.com/ctrlplusb/react-universally) - A starter kit giving you the minimum for a production ready universal react application.

### Other

- [Juho, Johannes, Tobias & Sean on JavaScript Air](http://jsair.io/webpack) - [JavaScript Air](https://javascriptair.com) podcast

[Back to top](#table-of-contents)

[twittericon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg
[githubicon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg
