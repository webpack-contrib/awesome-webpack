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

- [Webpack 4.x](https://v4.webpack.js.org) - Webpack 4.x Documentation
- [Webpack 5.x](https://webpack.js.org) - Webpack 5.x Documentation

### Community

- [StackOverflow](http://stackoverflow.com/tags/webpack)
- [Medium](https://medium.com/tag/webpack)
- [Gitter Chat](https://gitter.im/webpack/webpack)

### Twitter

*People passionate about Webpack (In no particular order)*

- [Sean T. Larkin - @TheLarkInn](https://twitter.com/TheLarkInn) TPM at [Microsoft](https://twitter.com/MSEdgeDev). Developer Advocate and webpack core team member.
- [Juho Vepsäläinen - @bebraw](https://twitter.com/bebraw) from [SurviveJS](https://twitter.com/survivejs) and webpack core team member.
- [Eric Clemmons - @ericclemmons](https://twitter.com/ericclemmons) VP of Software Development at [HigherEdHQ](https://twitter.com/HigherEdHQ). Webpack member.
- [Patrick Stapleton - @gdi2290](https://twitter.com/gdi2290) from [AngularClass](https://angularclass.com), [AngularAir](https://angularair.com) and [Angular Universal](https://github.com/angular/universal). Webpack member.
- [Kent C. Dodds - @kentcdodds](https://twitter.com/kentcdodds) from [PayPal Engineering](https://twitter.com/PayPalEng) and [JavaScript Air](https://twitter.com/JavaScriptAir). Webpack member.
- [Johannes Ewald - @Jhnnns](https://twitter.com/Jhnnns): Webpack core team member.
- [Joshua Wiens - @d3viant0ne](https://twitter.com/d3viant0ne): Technical Lead for [EasyMetrics](https://easymetrics.com). Webpack member.
- [Jonathan Creamer - @jcreamer898](https://twitter.com/jcreamer898): Microsoft MVP and [Telerik](https://github.com/telerik) Developer Expert.
- [Kees Kluskens - @keeskluskens](https://twitter.com/keeskluskens): - Software Engineer at [Code Yellow](https://codeyellow.nl),  Webpack core team member.

[Back to top](#contents)


## Libraries

### Loaders

#### File Type

- [File Loader](https://github.com/webpack/file-loader): File loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [URL Loader](https://github.com/webpack/url-loader): URL loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [HTML Loader](https://github.com/webpack/html-loader): HTML loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Raw Loader](https://github.com/webpack/raw-loader): Raw file loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Image Loader](https://github.com/thetalecrafter/img-loader): Image minimizing loader for webpack. -- *Maintainer*: `Andy VanWagoner` [![Github][githubicon]](https://github.com/thetalecrafter) [![Twitter][twittericon]](https://twitter.com/thetalecrafter)
- [Responsive Loader](https://github.com/herrstucki/responsive-loader): Loader for responsive images. -- *Maintainer*: `Jeremy Stucki` [![Github][githubicon]](https://github.com/herrstucki)
- [SVG Url Loader](https://github.com/bhovhannes/svg-url-loader): Loader which loads SVG file as utf-8 encoded Url. -- *Maintainer*: `Hovhannes Babayan` [![Github][githubicon]](https://github.com/bhovhannes)
- [json5 Loader](https://github.com/webpack/json5-loader): json5 loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [json Loader](https://github.com/webpack/json-loader): json loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [mermaid Loader](https://github.com/popul/mermaid-loader): [mermaid](https://github.com/mermaid-js/mermaid) loader module (diagrams) for Webpack. -- *Maintainer*: `Paul Musso` [![Github][githubicon]](https://github.com/popul)
- [wasm loader](https://github.com/ballercat/wasm-loader): wasm binary loader module for Webpack. -- *Maintainer*: `Arthur Buldauskas` [![Github][githubicon]](https://github.com/wasm-loader)
- [Imagemin Loader/Plugin](https://github.com/itgalaxy/imagemin-webpack): Image minimizing loader + plugin for webpack. -- *Maintainer*: `itgalaxy inc.` [![Github][githubicon]](https://github.com/itgalaxy)
- [Bin Exec Loader](https://github.com/milewski/bin-exec-loader): Pipe any file through any binary. -- *Maintainer*: `Rafael Milewski` [![Github][githubicon]](https://github.com/milewski)
- [GraphQL Loader](https://github.com/stephen/graphql-loader): `.graphql` document loader. -- *Maintainer*: `Stephen Wan` [![Github][githubicon]](https://github.com/stephen)
- [C/C++ Loader](https://github.com/ClickSimply/cpp-wasm-loader): Load native C/C++ files with minimal bundle bloat. -- *Maintainer*: `Scott Lott` [![Github][githubicon]](https://github.com/ClickSimply)

#### Component & Template

- [Angular2 Template Loader](https://github.com/TheLarkInn/angular2-template-loader): Inlines html and style's in Angular2 components. -- *Maintainer*: `Sean Larkin` [![Github][githubicon]](https://github.com/TheLarkInn) [![Twitter][twittericon]](https://twitter.com/TheLarkInn)
- [Handlebars Loader](https://github.com/pcardune/handlebars-loader): A handlebars template loader for Webpack. -- *Maintainer*: `Paul Carduner` [![Github][githubicon]](https://github.com/pcardune) [![Twitter][twittericon]](https://twitter.com/pcardune)
- [Vue Loader](https://github.com/vuejs/vue-loader): Webpack loader for Vue.js components. -- *Maintainer*: `Vuejs Team` [![Github][githubicon]](https://github.com/vuejs) [![Twitter][twittericon]](https://twitter.com/vuejs)
- [SVG React Loader](https://github.com/jhamlet/svg-react-loader) - Webpack SVG to React Component Loader.  -- *Maintainer*: `Jerry Hamlet` [![Github][githubicon]](https://github.com/jhamlet) [![Twitter][twittericon]](https://twitter.com/jerryhamlet)
- [Underscore Loader](https://github.com/emaphp/underscore-template-loader) - Underscore and Lodash template loader.  -- *Maintainer*: `Emmanuel Antico` [![Github][githubicon]](https://github.com/emaphp) [![Twitter][twittericon]](https://twitter.com/emaphp)
- [ngTemplate Loader](https://github.com/WearyMonkey/ngtemplate-loader) - Angular1 Template Loader.  -- *Maintainer*: `Toby Rahilly` [![Github][githubicon]](https://github.com/WearyMonkey)
- [ngInlineStylesLoader](https://github.com/seveves/ng-inline-styles-loader): Optimizes inlined css of angular components. -- *Maintainer*: `Severin Friede` [![Github][githubicon]](https://github.com/seveves)
- [Markup-inline Loader](https://github.com/asnowwolf/markup-inline-loader) Inline SVGs to HTML -- *Maintainer*: `Zhicheng Wang` [![Github][githubicon]](https://github.com/asnowwolf)
- [Polymer Loader](https://github.com/webpack-contrib/polymer-webpack-loader) - Loader for Polymer elements. -- *Maintainers*: `Rob Dodson` [![Github][githubicon]](https://github.com/robdodson) - `Chad Killingsworth` [![Github][githubicon]](https://github.com/ChadKillingsworth) - `Bryan Coulter` [![Github][githubicon]](https://github.com/bryandcoulter)
- [Tag Loader](https://github.com/riot/tag-loader) - Loader for Riot tag files. -- *Maintainer*: `Riot Team` [![Github][githubicon]](https://github.com/riot) [![Twitter][twittericon]](https://twitter.com/riotjs_)
- [Twig Loader](https://github.com/zimmo-be/twig-loader) - Twig template loader. -- *Maintainer*: `Zimmo.be Team` [![Github][githubicon]](https://github.com/zimmo-be)
- [Auto ngTemplate Loader](https://github.com/YashdalfTheGray/auto-ngtemplate-loader): Autodetect Angular 1 templates and load them. -- *Maintainer*: `Yash Kulshrestha` [![Github][githubicon]](https://github.com/YashdalfTheGray)
- [Pug Loader](https://github.com/pugjs/pug-loader) - Pug template loader (formerly Jade). -- *Maintainer*: `Pug Team` [![Github][githubicon]](https://github.com/pugjs)
- [Simple Nunjucks Loader](https://github.com/ogonkov/nunjucks-loader) - Nunjucks template loader. -- *Maintainer*: `ogonkov` [![Github][githubicon]](https://github.com/ogonkov)

#### Styles

- [Style Loader](https://github.com/webpack/style-loader): Style loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [PostCSS Loader](https://github.com/postcss/postcss-loader): PostCSS loader for Webpack. -- *Maintainer*: `PostCSS Team` [![Github][githubicon]](https://github.com/postcss) [![Twitter][twittericon]](https://twitter.com/PostCSS)
- [CSS Loader](https://github.com/webpack/css-loader): CSS loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SASS Loader](https://github.com/jtangelder/sass-loader): SASS loader for Webpack. -- *Maintainer*: `Jorik Tangelder` [![Github][githubicon]](https://github.com/jtangelder) [![Twitter][twittericon]](https://twitter.com/jorikdelaporik)
- [Less Loader](https://github.com/webpack/less-loader): Less loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Stylus Loader](https://github.com/shama/stylus-loader): A stylus loader for webpack. -- *Maintainer*: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Isomorphic Style Loader](https://github.com/kriasoft/isomorphic-style-loader): Isomorphic CSS style loader for Webpack. -- *Maintainer*: `Kriasoft Team` [![Github][githubicon]](https://github.com/kriasoft) [![Twitter][twittericon]](https://twitter.com/kriasoft)
- [Minify CSS-in-JS Loader](https://github.com/zaaack/minify-cssinjs-loader): RegExp-based minify CSS-in-JS loader for Webpack, don't need babel. -- *Maintainer*: `Zack Young` [![Github][githubicon]](https://github.com/zaaack) [![Twitter][twittericon]](https://twitter.com/ZaaackYoung)
- [SASS Resources Loader](https://github.com/shakacode/sass-resources-loader): Globally import SASS resources (variables, mixins, etc.). -- *Maintainer*: `ShakaCode` [![Github][githubicon]](https://github.com/shakacode) [![Twitter][twittericon]](https://twitter.com/shakacode)

#### Language & Framework

- [TS Loader](https://github.com/TypeStrong/ts-loader): TypeScript loader for webpack. -- *Maintainer*: `TypeStrong Team` [![Github][githubicon]](https://github.com/TypeStrong)
- [Awesome TypeScript Loader](https://github.com/s-panferov/awesome-typescript-loader): Awesome TS loader for Webpack. -- *Maintainer*: `Stanislav Panferov` [![Github][githubicon]](https://github.com/s-panferov) [![Twitter][twittericon]](https://twitter.com/babel)
- [Coffee Loader](https://github.com/webpack/coffee-loader): Coffee loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Bootstrap Loader](https://github.com/shakacode/bootstrap-loader): Load Bootstrap styles in your Webpack bundle. -- *Maintainer*: `ShakaCode Team` [![Github][githubicon]](https://github.com/shakacode) [![Twitter][twittericon]](https://twitter.com/shakacode)
- [PostHTML Loader](https://github.com/posthtml/posthtml-loader): PostHTML loader for Webpack. -- *Maintainer*: `PostHTML Team` [![Github][githubicon]](https://github.com/posthtml) [![Twitter][twittericon]](https://twitter.com/PostHTML)
- [ELM Loader](https://github.com/rtfeldman/elm-webpack-loader): Webpack loader for the Elm programming language. -- *Maintainer*: `Richard Feldman` [![Github][githubicon]](https://github.com/rtfeldman) [![Twitter][twittericon]](https://twitter.com/rtfeldman)
- [Fengari Loader](https://github.com/fengari-lua/fengari-loader/): Run Lua code using [Fengari](https://fengari.io). -- *Maintainer*: `Daurnimator` [![Github][githubicon]](https://github.com/daurnimator) [![Twitter][twittericon]](https://twitter.com/daurnimator)

#### Utility

- [Babel Loader](https://github.com/babel/babel-loader): Webpack plugin for Babel. -- *Maintainer*: `Babel Team` [![Github][githubicon]](https://github.com/babel) [![Twitter][twittericon]](https://twitter.com/babel)
- [ESLint Loader](https://github.com/webpack/eslint-loader): A ESlint loader for webpack. -- *Maintainer*: `Ricardo Gobbo de Souza` [![Github][githubicon]](https://github.com/ricardogobbosouza)
- [JSHint Loader](https://github.com/webpack/jshint-loader): JSHint loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [JSCS Loader](https://github.com/unindented/jscs-loader): Run your source through the JSCS style checker. -- *Maintainer*: `Daniel Perez Alvarez` [![Github][githubicon]](https://github.com/unindented)
- [Bundle Loader](https://github.com/webpack/bundle-loader): Bundle loader for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Worker Loader](https://github.com/webpack/worker-loader): Worker loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Resolve URL Loader](https://github.com/bholloway/resolve-url-loader): Resolves relative paths in url() statements. -- *Maintainer*: `Ben Holloway` [![Github][githubicon]](https://github.com/bholloway)
- [Import Loader](https://github.com/webpack/imports-loader): Imports loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [SourceMap Loader](https://github.com/webpack/source-map-loader): Extract sourceMappingURL comments from modules. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Combine Loader](https://www.npmjs.com/package/webpack-combine-loaders) - Converts a loaders array into a single loader string.  -- *Maintainer*: `James Friend` [![Github][githubicon]](https://github.com/jsdf)
- [Icon Font Loader](https://github.com/vusion/icon-font-loader) - Converts svgs into font icons in CSS.  -- *Maintainer*: `Forrest R. Zhao` [![Github][githubicon]](https://github.com/rainfore)
- [Icons Loader](https://www.npmjs.com/package/icons-loader) - Generates an iconfont from SVG dependencies.  -- *Maintainer*: `Mike Vercoelen` [![Github][githubicon]](https://github.com/mikevercoelen)
- [Modernizr Loader](https://www.npmjs.com/package/modernizr-loader) - Get your modernizr build bundled with webpack. -- *Maintainer*: `Peerigon Devs` [![Github][githubicon]](https://github.com/peerigon)
- [ngRouter Loader](https://github.com/shlomiassaf/ng-router-loader) - AOT capable NgModule lazy loading using angular router -- *Maintainer*: `Shlomi Assaf` [![Github][githubicon]](https://github.com/shlomiassaf) [![Twitter][twittericon]](https://twitter.com/shlomiassaf)
- [Lingui Loader](https://github.com/lingui/js-lingui/tree/master/packages/loader) - Compile message catalogs on the fly for jsLingui, i18n library -- *Maintainer*: `Tomáš Ehrlich` [![Github][githubicon]](https://github.com/tricoder42) [![Twitter][twittericon]](https://twitter.com/tomas_ehrlich)
- [Shell Loader](https://github.com/localjo/shell-loader) -  Run an arbitrary shell script on source files. -- *Maintainer*: `Jo Sprague` [![Github][githubicon]](https://github.com/localjo)
- [EXIF Loader](https://github.com/herschel666/exif-loader) - Extract EXIF- & IPTC-data from your JPGs during build-time. -- *Maintainer*: `Emanuel Kluge` [![Github][githubicon]](https://github.com/herschel666/exif-loader) [![Twitter][twittericon]](https://twitter.com/herschel_r)
- [esbuild Loader](https://github.com/privatenumber/esbuild-loader) - Blazing fast alternative to babel-loader, ts-loader, and Terser powered by [esbuild](https://github.com/evanw/esbuild). -- *Maintainer*: `Hiroki Osame` [![Github][githubicon]](https://github.com/privatenumber/esbuild-loader) [![Twitter][twittericon]](https://twitter.com/privatenumbr)

#### Testing

- [Mocha Loader](https://github.com/webpack/mocha-loader): Mocha loader module for Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Karma Webpack](https://github.com/webpack/karma-webpack): Use Karma with Webpack. -- *Maintainer*: `Webpack Team` [![Github][githubicon]](https://github.com/webpack)
- [Istanbul Webpack plugin](https://github.com/DxCx/webpack-istanbul-plugin): Use Istanbul instrumenter for the whole pack. -- *Maintainer*: `Hagai Cohen` [![Github][githubicon]](https://github.com/DxCx)

[Back to top](#contents)

### Integration Libraries

- [Dotenv Webpack](https://github.com/mrsteele/dotenv-webpack): Compiles environment variables into your bundle via dotenv. -- *Maintainer*: `Matthew Steele` [![Github][githubicon]](https://github.com/mrsteele) [![Twitter][twittericon]](https://twitter.com/Matt_R_Steele)
- [Terse Webpack](https://github.com/ericclemmons/terse-webpack) - Webpack simplified in a fluent API with presets.  -- *Maintainer*: `Eric Clemmons` [![Github][githubicon]](https://github.com/ericclemmons) [![Twitter][twittericon]](https://twitter.com/ericclemmons)
- [SystemJS Webpack](https://github.com/guybedford/systemjs-webpack-plugin) - Webpack bundling for SystemJS.  -- *Maintainer*: `Guy Bedford` [![Github][githubicon]](https://github.com/guybedford) [![Twitter][twittericon]](https://twitter.com/guybedford)
- [Gulp Webpack Stream](https://github.com/shama/webpack-stream) - Run webpack through a stream interface.  -- *Maintainer*: `Kyle Robinson Young` [![Github][githubicon]](https://github.com/shama) [![Twitter][twittericon]](https://twitter.com/shamakry)
- [Webpack Blocks](https://github.com/andywer/webpack-blocks) - Configure webpack using functional feature blocks.  -- *Maintainer*: `Andy Wermke` [![Github][githubicon]](https://github.com/andywer) [![Twitter][twittericon]](https://twitter.com/andywritescode)
- [Webpacker](https://github.com/rails/webpacker) - Offical webpack gem for integration into ruby on rails projects.  -- *Maintainer*: `Rails` [![Github][githubicon]](https://github.com/rails)
- [WebpackAspnetMiddleware](https://github.com/frankwallis/WebpackAspnetMiddleware) - Development middleware for ASP.NET 5.  -- *Maintainer*: `Frank Wallis` [![Github][githubicon]](https://github.com/frankwallis)
- [Consul Key/Value Webpack](https://github.com/marlonmleite/consul-env-webpack-plugin): Compiles environment variables into your bundle via [Consul KV-store](https://www.consul.io/api/kv.html). -- *Maintainer*: `Marlon Maxwel` [![Github][githubicon]](https://github.com/marlonmleite)

[Back to top](#contents)

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
- [Static Site Generator Plugin](https://github.com/markdalgleish/static-site-generator-webpack-plugin) - Minimal, unopinionated static site generator. -- *Maintainer*: `Mark Dalgleish` [![Github][githubicon]](https://github.com/markdalgleish)
- [SVG Sprite Plugin](https://github.com/TodayTix/svg-sprite-webpack-plugin) - Plugin for SVG sprites and icons. -- *Maintainer*: `Jeremy Tice` ([`TodayTix`](https://github.com/TodayTix)) [![Github][githubicon]](https://github.com/jetpacmonkey) [![Twitter][twittericon]](https://twitter.com/jetpacmonkey)
- [Imagemin Webpack Plugin](https://github.com/Klathmon/imagemin-webpack-plugin) - Minify images with Imagemin. -- *Maintainer*: `Gregory Benner` [![Github][githubicon]](https://github.com/Klathmon) [![Twitter][twittericon]](https://twitter.com/Klathmon)
- [Prepack Webpack Plugin](https://github.com/gajus/prepack-webpack-plugin) - A webpack plugin for prepack. -- *Maintainer*: `Gajus Kuizinas` [![Github][githubicon]](https://github.com/gajus)
- [Modules CDN Webpack Plugin](https://github.com/mastilver/modules-cdn-webpack-plugin) - Dynamically load your modules from a CDN. -- *Maintainer*: `Thomas Sileghem` [![Github][githubicon]](https://github.com/mastilver)
- [Generate package.json Plugin](https://github.com/lostpebble/generate-package-json-webpack-plugin) - Limit dependencies in a deployment `package.json` to only those that are actually being used by your bundle. -- *Maintainer*: `Paul Myburgh` [![Github][githubicon]](https://github.com/lostpebble)
- [Progressive Web App Manifest](https://github.com/arthurbergmz/webpack-pwa-manifest) - PWA manifest manager and generator. -- *Maintainer*: `Arthur A. Bergamaschi` [![Github][githubicon]](https://github.com/arthurbergmz)
- [Friendly errors](https://github.com/geowarin/friendly-errors-webpack-plugin) - Recognizes certain classes of webpack errors and cleans, aggregates and prioritizes them. -- *Maintainer*: `Geoffroy Warin` [![Github][githubicon]](https://github.com/geowarin)
- [FileManager Webpack Plugin](https://github.com/gregnb/filemanager-webpack-plugin) - Copy, move, delete files and directories before and after Webpack builds -- *Maintainer*: `Gregory Nowakowski` [![Github][githubicon]](https://github.com/gregnb)
- [Fork TS Checker Webpack Plugin](https://github.com/TypeStrong/fork-ts-checker-webpack-plugin) - Webpack plugin that runs typescript type checker on a separate process. -- *Maintainer*: `TypeStrong Team` [![Github][githubicon]](https://github.com/TypeStrong) 
- [Duplicate Package Checker Webpack Plugin](https://github.com/darrenscerri/duplicate-package-checker-webpack-plugin) - Warns you when multiple versions of the same package exist in your bundle -- *Maintainer*: `Darren Scerri` [![Github][githubicon]](https://github.com/darrenscerri)
- [PurgeCSS Webpack Plugin](https://github.com/FullHuman/purgecss-webpack-plugin) - A plugin to remove unused css with purgecss -- *Maintainer*: `Floriel Fedry` [![Github][githubicon]](https://github.com/Ffloriel)
- [Circular Dependency Plugin](https://github.com/aackerman/circular-dependency-plugin) - Detect modules with circular dependencies when bundling -- *Maintainer*: `Aaron Ackerman` [![Github][githubicon]](https://github.com/aackerman)
- [webpack-inject-plugin](https://github.com/adierkens/webpack-inject-plugin) - A webpack plugin to dynamically inject code into the bundle. -- *Maintainer*: `Adam Dierkens` [![Github][githubicon]](https://github.com/adierkens)
- [Public Path Manipulation Plugin](https://github.com/agoldis/webpack-require-from) - control `publicPath` of dynamically loaded resources at runtime  -- *Maintainer*: `Andrew Goldis` [![Github][githubicon]](https://github.com/agoldis)
- [Build Notifier Plugin](https://github.com/roccoc/webpack-build-notifier) - Display OS-level notifications for build errors and warnings. -- *Maintainer*: `Rocco Cataldo` [![Github][githubicon]](https://github.com/roccoc)
- [CSS Cleanup Webpack Plugin](https://github.com/do-web/css-cleanup-webpack-plugin) - A plugin to remove duplicated and unused css rules -- *Maintainer*: `Dominik Weber` [![Github][githubicon]](https://github.com/do-web)
- [Extension Reloader](https://github.com/rubenspgcavalcante/webpack-extension-reloader) - Hot reloading while developing browser extensions -- *Maintainer*: `Rubens P. G. Cavalcante` [![Github][githubicon]](https://github.com/rubenspgcavalcante) [![Twitter][twittericon]](https://twitter.com/rubenspgc)
- [Htmls Webpack Plugin](https://github.com/zaaack/htmls-webpack-plugin): Simple and fast multiple-htmls-generating plugin for webpack. -- *Maintainer*: `Zack Young` [![Github][githubicon]](https://github.com/zaaack) [![Twitter][twittericon]](https://twitter.com/ZaaackYoung)
- [Mini css extract plugin](https://github.com/webpack-contrib/mini-css-extract-plugin):
Lightweight CSS extraction plugin -- *Maintainer*: `Webpack Contrib` [![Github][githubicon]](https://github.com/webpack-contrib)
- [build-hash-webpack-plugin](https://github.com/Cosium/build-hash-webpack-plugin) For each build, Webpack generates an in-memory hash allowing to know if two build outputs are the same or not. This plugin writes the described build hash in a separate json file. -- *Maintainer*: `Réda Housni Alaoui` [![Github][githubicon]](https://github.com/reda-alaoui) [![Twitter][twittericon]](https://twitter.com/alaouirda)
- [webpack-hook-plugin](https://github.com/tienne/webpack-hook-plugin) - run any shell commands before or after webpack builds -- *Maintainer*: `David Kwon` [![Github][githubicon]](https://github.com/tienne)
- [Dynamic Vendor Webpack Plugin](https://github.com/bios21/dynamic-vendor-webpack-plugin) - Gives you a way to import vendors with dynamic variable and specific code splitting. -- *Maintainer* `Lilian Saget-Lethias` [![Github][githubicon]](https://github.com/bios21) [![Twitter][twittericon]](https://twitter.com/lsagetlethias)
- [Define Variable Webpack Plugin](https://github.com/bios21/define-variable-webpack-plugin) - Enhancement of DefinePlugin to store defined things in actual variables. -- *Maintainer* `Lilian Saget-Lethias` [![Github][githubicon]](https://github.com/bios21) [![Twitter][twittericon]](https://twitter.com/lsagetlethias)
- [Shell Script Webpack Plugin](https://github.com/drewloomer/hook-shell-script-webpack-plugin) - A plugin for running arbitrary shell scripts when [compiler hooks](https://webpack.js.org/api/compiler-hooks/) are triggered. -- *Maintainer* `Drew Loomer` [![Github][githubicon]](https://github.com/drewloomer) [![Twitter][twittericon]](https://twitter.com/drewloomer)
- [Stylelint Webpack Plugin](https://github.com/webpack-contrib/stylelint-webpack-plugin): A Stylelint plugin for webpack. -- *Maintainer*: `Ricardo Gobbo de Souza` [![Github][githubicon]](https://github.com/ricardogobbosouza)
- [ESLint Webpack Plugin](https://github.com/webpack-contrib/eslint-webpack-plugin): A ESLint plugin for webpack
. -- *Maintainer*: `Ricardo Gobbo de Souza` [![Github][githubicon]](https://github.com/ricardogobbosouza)
- [Exclude Assets Webpack Plugin](https://github.com/klaytonfaria/webpack-exclude-assets-plugin): A plugin to exclude assets from webpack output based on a path RegExp pattern. -- *Maintainer*: `Klayton Faria` [![Github][githubicon]](https://github.com/klaytonfaria)
- [Webpack Shell Plugin Next](https://github.com/s00d/webpack-shell-plugin-next): A plugin allows you to run any shell commands before or after webpack builds. -- *Maintainer*: `Kuzmin Pavel` [![Github][githubicon]](https://github.com/s00d)
- [Gettext Webpack Plugin](https://github.com/juanluispaz/gettext-webpack-plugin): Embed localization into your bundle using gettext. -- *Maintainer*: `Juan Luis Paz` [![Github][githubicon]](https://github.com/juanluispaz)
- [Node Polyfill Plugin](https://github.com/Richienb/node-polyfill-webpack-plugin): Polyfill Node.js core modules. -- *Maintainer*: `Richie Bendall` [![Github][githubicon]](https://github.com/Richienb) [![Twitter][twittericon]](https://twitter.com/Richienb2)
- [Bytenode Plugin](https://github.com/herberttn/bytenode-webpack-plugin): Compile JavaScript into bytecode using bytenode. -- *Maintainer*: `Herbert Treis Neto` [![Github][githubicon]](https://github.com/herberttn)

[Back to top](#contents)

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
- [Neutrino](https://github.com/mozilla-neutrino/neutrino-dev): Combines the power of Webpack with the simplicity of presets. -- *Maintainer*: `Eli Perelman` [![Github][githubicon]](https://github.com/eliperelman)
- [Webpack Chain](https://github.com/mozilla-neutrino/webpack-chain): A chaining API to generate and simplify the mod. of Webpack 2 configurations. -- *Maintainer*: `Eli Perelman` [![Github][githubicon]](https://github.com/eliperelman)
- [Speed Measure Plugin](https://github.com/stephencookdev/speed-measure-webpack-plugin) - Measures the speed of your webpack plugins and loaders.  -- *Maintainer*: `Stephen Cook` [![Github][githubicon]](https://github.com/stephencookdev)
- [packtracker.io](https://packtracker.io/?utm_source=github&utm_medium=awesome-webpack&utm_campaign=social) - Webpack bundle analysis on every commit, report webpack stats to every pull request.
- [BundleStats](https://github.com/bundle-stats/bundle-stats) - Generates bundle report(sizes, assets, modules) and compares the results between different builds. -- *Maintainer*: `Vio` [![Github][githubicon]](https://github.com/vio) [![Twitter][twittericon]](https://twitter.com/vio)  
- [Webpack Landing Generator](https://github.com/kuncevic/webpack-landing-generator): Easy way to create landing page that converts. -- *Maintainer*: `Aliaksei Kuncevic` [![Github][githubicon]](https://github.com/kuncevic) [![Twitter][twittericon]](https://twitter.com/kuncevic)
- [Webpack Dev Server Firewall](https://github.com/funbox/webpack-dev-server-firewall): Prevents access to dev server from unknown IPs. -- *Maintainer*: `Igor Adamenko` [![Github][githubicon]](https://github.com/igoradamenko) [![Twitter][twittericon]](https://twitter.com/igoradamenko)

[Back to top](#contents)

## Research & Training

### Articles

- Aniketh Saha | 16-Oct-19 - [Creating a Custom webpack Plugin](https://alligator.io/js/create-custom-webpack-plugin/)
- Antoine Caron | 18-Jan-19 - [Webpack : an unexpected journey](https://medium.zenika.com/webpack-an-unexpected-journey-26f987efd1c5)
- Andrew Welch | 23-Oct-18 - [An Annotated webpack 4 Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-webpack-4-config-for-frontend-web-development)
- Gábor Soós | 24-Apr-17 - [How to do proper tree-shaking in Webpack 2](https://blog.craftlab.hu/how-to-do-proper-tree-shaking-in-webpack-2-e27852af8b21)
- Mark Erikson | 07-Mar-17 - [Declaratively Rendering Earth in 3D, Building a Cesium + React App with Webpack](http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-1-cesium-webpack/)
- Joseph Zimmerman | 2-Feb-17 - [A Detailed Introduction To Webpack.](https://www.smashingmagazine.com/2017/02/a-detailed-introduction-to-webpack/)
- Jamund Ferguson | 22-Jul-16 - [Manually Tuning Webpack Builds.](https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44#.lbvkidezh)
- Sean T. Larkin | 21-Jul-16 - [Learn and Debug webpack with Chrome Dev Tools!.](https://medium.com/webpack/webpack-bits-learn-and-debug-webpack-with-chrome-dev-tools-da1c5b19554#.gpoentuxe)
- Raja Rao DV | 10-Apr-16 - [Webpack  —  The Confusing Parts.](https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9#.qmfmplobc)
- Andrew Ray | 09-Apr-16 - [Webpack: When To Use and Why.](http://blog.andrewray.me/webpack-when-to-use-and-why/)
- Jonathan Creamer | 25-Feb-16 - [WebPack Code splitting with ES6 and Babel 6.](http://jonathancreamer.com/webpack-code-splitting-with-es6-and-babel-6/)
- Grgur Grisogono | 15-Feb-16 - [Webpack 2 Tree Shaking Configuration.](https://medium.com/modus-create-front-end-development/webpack-2-tree-shaking-configuration-9f1de90f3233#.5pddvz5lz)
- Ilya Zayats | 07-Feb-16 - [How to split your apps by routes with Webpack.](https://medium.com/@somebody32/how-to-split-your-apps-by-routes-with-webpack-36b7a8a6231#.iy99i4f7r)
- Sebastian De Deyne | 04-Feb-16 - [Adventure Time With Webpack.](https://sebastiandedeyne.com/posts/2016/adventure-time-with-webpack)
- Jonathan Creamer | 10-Jan-16 - [Advanced WebPack Part 2 - Code Splitting.](http://jonathancreamer.com/advanced-webpack-part-2-code-splitting)
- Andy Ccs | 02-Jan-16 - [Webpack and Docker for Development and Deployment.](https://medium.com/@andyccs/webpack-and-docker-for-development-and-deployment-ae0e73243db4#.2yutcm8s4)
- Jonathan Creamer | 08-Jun-16 - [Advanced WebPack Part 3 - Creating a custom notifier plugin.](http://jonathancreamer.com/advanced-webpack-part-3-creating-a-custom-notifier-plugin)
- Nader Dabit | 07-Sept-15 - [Beginner’s guide to Webpack.](https://medium.com/@dabit3/beginner-s-guide-to-webpack-b1f1a3638460#.xb01fcsoq)
- Jonathan Creamer | 02-Sept-15 - [Advanced WebPack Part 1 - The CommonsChunk Plugin.](http://jonathancreamer.com/advanced-webpack-part-1-the-commonschunk-plugin/)
- Maxime Fabre | 16-Oct-15 - [Webpack your bags.](https://blog.madewithlove.be/post/webpack-your-bags/?utm_content=buffer480f4&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
- Hridayesh Sharma | 18-Aug-20 - [Webpack Setup for a JavaScript Library](https://www.loginradius.com/engineering/blog/write-a-javascript-library-using-webpack-and-babel/)

### Videos

- Sean Larkin JS Kongress | Apr-2-2019 - [Everything’s a plugin: Understanding webpack from the inside out](https://youtu.be/H3g0BdyVVxA)
- Colt Steele via Youtube| Mar-7-2019 - [Learn Webpack Course](https://www.youtube.com/playlist?list=PLblA84xge2_zwxh3XJqy6UVxS60YdusY8)
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
- [Webpack 4 Fundamentals](https://frontendmasters.com/courses/webpack-fundamentals/) - Brief introduction about Webpack fundamentals by [Sean Larkin](https://twitter.com/thelarkinn)
- [Web Performance with Webpack](https://frontendmasters.com/courses/performance-webpack/) - Solving common web performance problems using Webpack by [Sean Larkin](https://twitter.com/thelarkinn)
- [Intro to webpack (playlist)](https://egghead.io/playlists/intro-to-webpack-4ca2d994) - Egghead.io playlist of a few videos by [Kent C. Dodds](https://twitter.com/kentcdodds) (the first is free).
- [Angular and Webpack for modular applications](https://egghead.io/courses/angular-and-webpack-for-modular-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds)
- [Using Webpack for Production JavaScript Applications](https://egghead.io/courses/using-webpack-for-production-javascript-applications) - Egghead.io course by [Kent C. Dodds](https://twitter.com/kentcdodds) (advanced)
- [Webpack Fundamentals](https://www.pluralsight.com/courses/webpack-fundamentals) - [Joe Eames](https://twitter.com/josepheames) for Pluralsight (intermediate)
- [Webpack Academy](https://webpack.academy) - A comprehensive webpack learning resource.
- [Webpack workshops](https://slashgear.github.io/webpack-workshop/) - Collection of courses to learn webpack from novice to advanced levels by Antoine Caron
- [Webpack from scratch series](https://www.youtube.com/playlist?list=PLLhEJK7fQIxB2gZBIzYI50NPsAQERD9rL) on YouTube by Paris Nakita Kejser

### Books

- [SurviveJS - Webpack](http://survivejs.com/webpack/introduction): Free book guiding from a webpack apprentice to master. Covers dev, prod, and advanced topics.

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

- [Annotated webpack 4 Config](https://github.com/nystudio107/annotated-webpack-4-config) - This is the companion github repo for the [An Annotated webpack 4 Config for Frontend Web Development](https://nystudio107.com/blog/an-annotated-webpack-4-config-for-frontend-web-development) article.
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
- [Budgeting Application](https://github.com/ModusCreateOrg/budgeting-sample-app-webpack2) - A fully functional boilerplate application optimized for dev and prod, including PRPL from [Modus Create](https://github.com/ModusCreateOrg).
- [Razzle Material-UI Styled Example](https://github.com/kireerik/razzle-material-ui-styled-example) - With Styled Components using Express with compression from [Erik Engi](https://github.com/kireerik).
- [React Typescript Starter](https://github.com/shortgiraffe4/react-typescript-starter) - A React + TypeScript + Webpack 4 + React-Router 4 + Redux + React-Redux + Redux-Thunk + PostCSS + Bootstrap 4 boilerplate.
- [Read](https://github.com/logustra/read) - A highly scalable react boilerplate from [logustra](https://github.com/logustra)

#### Vue
- [Vuad](https://github.com/logustra/vuad) - A highly scalable vue boilerplate from [logustra](https://github.com/logustra)

## Webpack Advanced Techniques

#### Build Optimization

- [Webpack: Build Performance](https://github.com/webpack/docs/wiki/build-performance) - Webpack docs on ways to speed up builds.

- [How to make your webpack builds 10x faster](http://www.slideshare.net/trueter/how-to-make-your-webpack-builds-10x-faster) - Slideshow that lists a number of approaches for making Webpack builds faster, such as narrowing scope, using the DllPlugin, using HappyPack for parallel builds, and more.

- [Advanced Frontend Optimization with Webpack](http://sokra.github.io/slides/frontend-optimize) - Slides by Webpack's original author, describing ways to improve Webpack builds.

- [Fixing annoying imports in React Projects](https://medium.com/datawallet-tech/fixing-annoying-imports-in-react-projects-895a6ad24c24) - A quick example of using Webpack's module aliasing to simplify import paths, with further discussion in the comments.

- [Webpack Plugins we been keeping on the DLL](https://medium.com/@soederpop/webpack-plugins-been-we-been-keepin-on-the-dll-cdfdd6cb8cd7) - An overview of Webpack's DllPlugin, and how it can be used for faster dev builds.

- [DllPlugin usage summary](https://github.com/erikras/react-redux-universal-hot-example/issues/616#issuecomment-228956242) - Notes from a user who wants to document his findings on usage of DllPlugin.  Pretty thorough.

- [Implement Webpack DLL Plugin for React-Boilerplate](https://github.com/mxstbr/react-boilerplate/pull/495) - A PR adding usage of DllPlugin to React-Boilerplate.  Thorough and well-commented - should be a very useful reference to anyone trying to set it up in their own project.

- [Optimizing Webpack](http://engineering.invisionapp.com/post/optimizing-webpack/) - Explains how to use DllPlugin to pre-bundle vendor libraries for faster build times.

- [Manually Tuning Webpack Builds](https://medium.com/@xjamundx/manually-tuning-webpack-builds-284923f47f44) - Tips for cutting down bundle sizes by removing duplicate library instances and fine-tuning usage of various libraries.

- [Tips for faster Webpack builds](https://www.reddit.com/r/javascript/comments/4xuknm/webpack_dashboard/d6jdl8z) - A Reddit comment with several useful tips to follow when trying to speed up builds

- [Formidable Playbook](https://formidable.com/open-source/playbook/) - Formidable Labs describes their preferred approaches for configuring Webpack, including optimization approaches.

- [Webpack Performance: The Comprehensive Guide](https://github.com/lcxfs1991/blog/issues/15) - An in-depth look at the parts that go into a Webpack build, and how each piece can be optimized for a faster build.

- [Speeding up Webpack performance with parallel builds](http://tech.trivago.com/2015/12/15/parallel-webpack/) - Describes a tool called `parallel-webpack`, which can build multiple entry points in multiple formats in parallel.

- [A React + Webpack Optimization Case](https://medium.com/@kudochien/a-react-webpack-optimization-case-27da392fb3ec) - Several useful examples of how to profile and optimize a Webpack-based project, including checking bundle contents, specific imports from libraries, ignoring Moment locales, and more.

- [Optimizing Wepback build times and improving caching with DLL bundles](https://robertknight.github.io/posts/webpack-dll-plugins/) - Explains the benefits of using DllPlugin for generating library bundles, shows how to configure it, and compares with other chunking methods.

- [Tree-shaking ES6 Modules in Webpack 2](https://medium.freecodecamp.com/tree-shaking-es6-modules-in-webpack-2-1add6672f31b) - A look at the concept of tree-shaking to reduce output size, how it relates to module formats, and how to configure Webpack to properly allow for tree-shaking

- [Webpack tree-shaking](https://medium.com/@johnstew/webpack-tree-shaking-20914b7a9ca5) - An explanation of what tree-shaking is, how to configure Webpack to apply it, and how it works.

- [How to optimize Moment.js with Webpack](https://github.com/jmblog/how-to-optimize-momentjs-with-webpack) - Tips on using IgnorePlugin and ContextReplacementPlugin to strip out uneeded locales from Moment

- [Declaratively Rendering Earth in 3D, Part 1: Building a Cesium + React App with Webpack](http://blog.isquaredsoftware.com/2017/03/declarative-earth-part-1-cesium-webpack/) - Shows how to configure Webpack to load the Cesium 3D globe library, and how to set up a Webpack config that uses DllPlugin to build a separate bundle for Cesium.

- [Tree shake Lodash with Webpack, Jest, and Typescript](https://medium.com/@martin_hotell/tree-shake-lodash-with-webpack-jest-and-typescript-2734fa13b5cd) - Walks through ways to configure Webpack and Babel to properly tree shake Lodash so that it only includes used functions.

- [Webpack for real tasks: decreasing front-end size and improving caching](https://iamakulov.com/notes/webpack-front-end-size-caching/) - Covers a variety of ways to improve bundle sizes, including minification with Uglify, tree shaking imports, referencing external libraries, and more.

- [Webpack 3 + React - Production Build Tips](https://medium.com/netscape/webpack-3-react-production-build-tips-d20507dba99a) - General advice for improving Webpack builds, including code splitting, minification, and several more.  Includes a complete Webpack config file at the end with the proper settings.

- [d-l-l: Easy, automatic, optimized DLL config handler for Webpack](https://survivejs.com/blog/dll-interview/) - An interview with the author of a tool for automatically generating DLL bundles, discussing how to use it and how it works.

- [High-performance webpack config for front-end delivery](https://www.codementor.io/drewpowers/high-performance-webpack-config-for-front-end-delivery-90sqic1qa) - Covers 7 optimizations you can add to a Webpack setup to build bundles faster and make them smaller.

- [Unpacking the Mysteries of Webpack](https://www.viget.com/articles/unpacking-the-mysteries-of-webpack-a-novices-journey) - Recaps some high-level Webpack terms and concepts, and walks through several changes to speed up compilation and improve bundle size.

- [How to Improve Webpack Performance in Large Projects](https://redfin.engineering/tech-talk-recap-how-to-improve-webpack-performance-in-large-projects-5435bb18dd18) - Slides, audio, and summary of a talk on various ways to improve Webpack build performance, including disabling sourcemaps for dev builds, parallelizing work, and using DllPlugin.

- [How we improved Webpack build performance by 95%](https://blog.box.com/blog/how-we-improved-webpack-build-performance-95/) - Tips for speeding up builds by using Babel caching, not exporting arrays of configs, and doing work in parallel.

- [Keep Webpack Fast: A Field Guide for Better Build Performance](https://slack.engineering/keep-webpack-fast-a-field-guide-for-better-build-performance-f56a5995e8f1) - An excellent article from Slack's frontend team, listing ways to improve Webpack build speed.  Gives overviews of profiling, parallelization tools, reducing workloads, and caching, with plenty of mentions for specific tools and techniques.



#### Code Splitting and Chunking

- [React-Router and Webpack in Production](https://reactjsnews.com/webpack-in-production) - Tips on dynamically loading route views and optimizing chunk sizes

- [Webpack Async Bundle Loading](http://jilles.me/webpack-async-bundle-loading/) - A quick look at how to delay-load some portion of your app's code.

- [Code Chunking with Webpack](https://medium.com/react-weekly/code-chunking-with-webpack-a-pragmatic-approach-e17e8bcc6453) - Covers how to configure chunked bundles and dynamic bundle loading with Webpack and React-Router.

- [Dynamic Vendor Bundling in Webpack](https://medium.com/jeremy-gayed/dynamic-vendor-bundling-in-webpack-528993e48aab) - An approach to dynamically adding anything from `node_modules` to a "vendor" bundle

- [Webpack Config: Commons Chunk Plugin part 1](https://www.youtube.com/watch?v=-xzWMKuiS2o) - An intro to what the Webpack Commons Chunk Plugin does and how it works

- [A beginner's step-by-step guide to Code Splitting with Webpack 2 and React Router](http://brotzky.co/blog/a-beginners-step-by-step-guide-to-code-splitting-with-webpack-2-and-react-router/) - An excellent guide to concepts and configuration needed for code splitting.

- [Lazily Load Code Declaratively in React and Webpack](https://gist.github.com/iammerrick/f3f9edfbf5dc279af775f73020193dcc) - Demonstrates one way to request and render components on demand, using Webpack's bundle-loader

- [Building Vendor and Feature Bundles with Webpack](http://odetocode.com/blogs/scott/archive/2016/12/01/building-vendor-and-feature-bundles-with-webpack.aspx) - Demonstrates using DllPlugin to build a vendor bundle, and generating multiple bundles for different features by dynamically building up multiple entry points.

- [Components a la carte](http://darrennewton.com/2016/12/21/components-a-la-carte/) - Describes a technique for dynamically loading only certain features that a user should see

- [Dynamic Imports with Webpack 2](https://dev.to/kayis/dynamic-imports-with-webpack-2) - A quick example of how to use dynamic imports to load pages or components at runtime

- [Lazy Loaded React Components with Webpack 2](https://dev.to/kayis/lazy-loaded-react-components-with-webpack-2) - A follow-on to the previous article, showing how to extend the dynamic imports approach to lazily load and render components

- [Vendor and code splitting in Webpack 2](https://medium.com/@adamrackis/vendor-and-code-splitting-in-webpack-2-6376358f1923) - An excellent dive into multiple aspects of code splitting, including basic setup, advanced config, and some Webpack gotchas/tips.

- [How to use Webpack's new "magic comment" feature with React Universal Component + SSR](https://medium.com/webpack/how-to-use-webpacks-new-magic-comment-feature-with-react-universal-component-ssr-a38fd3e296a) - Introduces Webpack's new "magic comments" feature for defining chunk names, and shows how to use that in association with a couple of libraries for optimized server-side rendering approaches

- [React Universal Component 2.0 & babel-plugin-universal-import](https://medium.com/faceyspacey/announcing-react-universal-component-2-0-babel-plugin-universal-import-5702d59ec1f4) - Introduces some new Webpack addons and changes that enable dynamic import expressions, including use with SSR.

- [Using Redux Saga and code splitting to async load React components](https://gist.github.com/jballands/accc2ff19a3702685d469c612d6f0776) - A gist that demonstrates using sagas to drive the loading of React components as needed, with some discussion in the comments of the best way to handle those components once they're received by the app.

- [Impress Your Friends with Code Splitting in React](https://hackernoon.com/impress-your-friends-with-code-splitting-in-react-9f9a3ca2ae6e) - Examples of using `async/await` and dynamic `import()` to lazy-load React components and display them after they're loaded.

- [ECMAScript Asychronicity - dynamic import](https://blog.eleven-labs.com/en/ecmascript-asynchronicity-dynamic-import/) - Recaps ES6 module behavior and use of Webpack's CommonsChunkPlugin, and describes how to lazy load code using `require.ensure` and the new dynamic `import()` capability.

- [Component Level Isomorphic Webpack Code-Splitting](https://medium.com/discovery-engineering/component-level-isomorphic-webpack-code-splitting-b98922382cc1) - Looks at the use cases for code splitting, the different ways Webpack can be used to do code splitting, problems with synchronous loading on the server vs async loading on the client, and how the React Universal Component toolkit can help  solve those issues.

- Lazy Loading with React, Redux, and Webpack 2+ - An excellent pair of posts that cover ways to structure components in terms of features, load them at runtime using Webpack's dynamic importing, and apply the same principles to loading Redux feature logic.
  - [Part 1](https://medium.com/front-end-hacking/lazy-loading-with-react-and-webpack-2-8e9e586cf442)
  - [Part 2](https://medium.com/front-end-hacking/lazy-loading-with-react-redux-and-webpack-2-35ad6fc1b640)

- [How to reduce your bundle size by automatically getting your dependencies from a CDN](https://medium.com/comparethemarket/how-to-reduce-your-bundle-size-by-automatically-getting-your-dependencies-from-a-cdn-96b25d1e228) - A quick example of using the `dynamic-cdn-webpack-plugin` to have your bundle reference libraries from the Unpkg CDN, rather than including them in the main bundle.

- [Webpack 3, Dynamic Imports, Code Splitting, and Long Term Caching Made Easy](https://blog.cloudboost.io/webpack-3-dynamic-imports-code-splitting-and-long-term-caching-made-easy-1892981e0ae7) - Describes how to configure Webpack and use React-Loadable to set up code-splitting, as well as set up consistent module hash IDs.

- [Two Tips to Improve Performance by 30% with React and Webpack](http://engineering.teacherspayteachers.com/2017/08/16/two-tips-to-improve-performance-by-30-with-react-and-webpack.html) - Looks at ways the Teachers Pay Teachers team used async bundle loading and bundle size optimization to improve their load time.


#### Bundle Sizes and Visualization

- [Building Better Bundles](http://blog.isquaredsoftware.com/2016/11/posts-on-packtpub-generic-redux-modals-and-building-better-bundles/) - An article describing what `process.env.NODE_ENV` means, and how it is used as part of a production build process to optimize build sizes

- [Chat discussion - summary of process.env.NODE_ENV and its use with Webpack](https://gist.github.com/markerikson/6776848172c33aaa4db882627c689e18) - An overview of how the `process.env.NODE_ENV` variable is often used to define optimizations for Webpack production builds

- [Webpack Bloat](http://www.jamesonnetworks.com/entry/webpack-bloat) - Discussion of how to improve production configurations for smaller bundle sizes

- ["Vector.im bundle is too big - analysis"](https://github.com/vector-im/vector-web/issues/2498) - Web perf expert Nolan Lawson analyzes why the JS bundle for the Vector.im web app is too big, and ways it could potentially be improved using code splitting and app structure changes.  A good example of ways to improve bundle sizes.

- [Unlocking a Mystery: Visualizing the Common Webpack Bundles](https://www.redfin.com/blog/2016/12/unlocking-a-mystery-visualizing-the-common-webpack-bundles.html) - A recap of some previous tools used to analyze Webpack bundle sizes, and description of a new tool they built to provide better bundle visualization

- [Analysing and minimising the size of client side bundle with Webpack and source-map-explorer](https://medium.com/@nimgrg/analysing-and-minimising-the-size-of-client-side-bundle-with-webpack-and-source-map-explorer-41096559beca) - Tips on using source-map-explorer to check the size of code included in a minified bundle, and removing unneeded polyfills

- [How to use source-map-explorer with Webpack](https://www.sivadass.in/using-source-map-explorer-with-webpack/) - Examples of using the source-map-explorer tool to visualize the contents of a bundle

- [Analyzing and optimizing your Webpack bundle](https://medium.com/@ahmedelgabri/analyzing-optimizing-your-webpack-bundle-8590818af4df) - Some quick suggestions for using CLI flags to show sizes of bundled chunks, and using webpack-bundle-analyzer and IgnorePlugin to exclude unneeded files.

- [Avoid Webpack bloat: Optimize your dependencies](https://www.zillow.com/engineering/webpack-optimize-dependencies/) - Tips for tracking bundle sizes and managing dependency handling

- [Webpack bits: getting the most out of the CommonsChunkPlugin](https://medium.com/webpack/webpack-bits-getting-the-most-out-of-the-commonschunkplugin-ab389e5f318) - Sean Larkin of the core Webpack team shares examples of common bundle size problems, and how to use the CommonsChunkPlugin to extract heavily used libraries into a separate bundle.

- [Weeding Out Your ES6 Webpack Bundle Sizes](https://medium.com/lendingtree-engineering/weeding-out-your-es6-webpack-bundle-sizes-62cbc5a62a30) - A recap of how adding a couple libraries to a production app resulted in much larger bundles, and some practical steps that can be taken to investigate and improve bundle sizes

- [How Webpack's ContextReplacementPlugin works](https://iamakulov.com/notes/all/webpack-contextreplacementplugin/) - An explanation of how ContextReplacementPlugin can be used to alter what files Webpack loads into a bundle.

- [How to do proper tree-shaking in Webpack 2](https://blog.craftlab.hu/how-to-do-proper-tree-shaking-in-webpack-2-e27852af8b21) - Explains several important concepts related to tree shaking, and how to configure Webpack and other tools to ensure it happens correctly.

- [3 ways to reduce Webpack bundle size](http://blog.jakoblind.no/2017/05/18/3-ways-to-reduce-webpack-bundle-size/) - A quick summary of some possible approaches to optimize bundle sizes, with links to more information

- [Introducing Bonsai: an open source Webpack analyzer](https://medium.com/@Pinterest_Engineering/introducing-bonsai-an-open-source-webpack-analyzer-6bdfe22f8984) - The Pinterest team describes the problems they'd encountered optimizing their Webpack bundles, and introduces a new tool to help analyze bundles and dependency trees.

- [Size Limit: Make the Web Lighter](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter) - Demonstrates writing a tiny library that results in a 100KB Webpack bundle, and then walks through improving the Webpack settings to improve bundle size to only 17B.

- Put Your Webpack Bundle On A Diet - A multi-part series that covers approaches for shrinking bundle size, ranging from simply using Webpack's -p flag up to advanced optimizations.
  - [Part 1](https://www.contentful.com/blog/2017/10/10/put-your-webpack-on-a-diet-part-1/)
  - [Part 2](https://www.contentful.com/blog/2017/10/19/put-your-webpack-bundle-on-a-diet-part-2/)
  - [Part 3](https://www.contentful.com/blog/2017/10/27/put-your-webpack-bundle-on-a-diet-part-3/)

- [What Lurks Within: Reducing Bundle Sizes with Webpack Bundle Analyzer](http://engineering.teacherspayteachers.com/2017/12/20/reducing-bundle-sizes-with-webpack-bundle-analyzer.html) - Tips for using the Webpack Bundle Analyzer tool to track down large dependencies.

- [Webpack Bundle Analysis - A necessary step for all React / Angular / Vue developers!](https://hackernoon.com/webpack-bundle-analysis-a-necessary-step-for-all-react-angular-vue-application-developers-fe6564fa62ca) - Walks through the process of analyzing an Angular bundle and improving build steps to cut down on bundle size.


#### Hot Module Replacement

- [Webpack and Hot Module Replacement](https://medium.com/@rajaraodv/webpack-hot-module-replacement-hmr-e756a726a07) - A great in-depth walkthrough of how HMR works

- [Webpack's HMR and React Hot-Loader - The Missing Manual](https://medium.com/@rajaraodv/webpacks-hmr-react-hot-loader-the-missing-manual-232336dc0d96) - Demonstrates three ways to enable HMR, and usage with three different React application scenarios

- [Hot Reloading in React](https://medium.com/@dan_abramov/hot-reloading-in-react-1140438583bf) - Dan Abramov walks through the history of his React Hot Loader and React Transform tools, describes their implementation, flaws, and weaknesses, and looks at a potential solution (later implemented in React Hot Loader 3.0).

- HMR Tutorial Series - A very readable and informative series of articles on using HMR.
  - [Part 1](http://andrewhfarmer.com/why-use-hmr/)
  - [Part 2](http://andrewhfarmer.com/understanding-hmr/)
  - [Part 3](http://andrewhfarmer.com/3-ways-webpack-hmr/)
  - [Part 4](http://andrewhfarmer.com/webpack-hmr-tutorial/)

- [Blogged Answers: Webpack HMR vs React-Hot-Loader](http://blog.isquaredsoftware.com/2017/08/blogged-answers-webpack-hmr-vs-rhl/) - A description of the differences between the HMR API offered by Webpack and how the React-Hot-Loader tool works, and advice on using "plain HMR".

 - [SurviveJS: Hot Module Replacement](https://survivejs.com/webpack/appendices/hmr/) - A guide to HMR concepts and usage, written by a Webpack core team member

- [Live Editing Javascript with Webpack](http://jlongster.com/Backend-Apps-with-Webpack--Part-III) - Some interesting and advanced tricks for ways HMR could be used.

- [Using React with "plain" Webpack HMR](https://github.com/reactjs/redux/pull/1455) - Dan Abramov removes use of the React-Transform plugin from Redux's examples, and demonstrates how to use the "plain" Webpack HMR API to do reloading of updated components, reducers, and other code.

- [Basic HMR Usage Example](https://gist.github.com/markerikson/dc6cee36b5b6f8d718f2e24a249e0491) - An extracted example demonstrating using "plain" HMR to reload components, reducers, and even sagas.

- [React - Hot Module Reload](https://medium.com/@baphemot/react-hot-module-reload-f6b3d34b9b86) - An explanation of how to set up HMR using React-Hot-Loader 3.0

- [Adding HMR to Create-React-App](http://chrisshepherd.me/posts/adding-hot-module-reloading-to-create-react-app) - A quick example of the basic pattern for using plain HMR with Webpack

- [Webpack Hot Reloading and React](https://ctheu.com/2015/12/29/webpack-hot-reloading-and-react-how/) - An explanation of how Hot Reloading works, and how the various pieces fit together.

- [ReactCasts #7: Hot Module Replacement in Create-React-App](https://www.youtube.com/watch?v=hcl3lNjgj-E) - A screencast talking about what HMR is, and two ways to add it to projects created with Create-React-App

- ["Difference between Webpack HMR and React-Hot-Loader?"](https://github.com/facebookincubator/create-react-app/issues/1063#issuecomment-261788083) - Dan Abramov clarifies that HMR is the API and capability that Webpack gives you, while React-Hot-Loader is a specialized tool that uses the HMR API to automatically add HMR handling to React code.

- [Hot reload all the things!](https://hackernoon.com/hot-reload-all-the-things-ec0fed8ab0) - A tutorial that shows how to use Webpack and HMR to hot-reload both front-end and back-end code for faster development.

- How to Hot-Load React Components in 7 Days - A 2-part article that discusses how to set up plain HMR and add React-Hot-Loader, as well as many of the complexities of using RHL.
  - [Part 1](https://medium.com/@antonkorzunov/how-to-hot-load-react-component-in-7-days-part-1-webpack-d8b77eea61eb)
  - [Part 2](https://codeburst.io/how-to-hot-load-react-component-in-7-days-part-2-react-28ce2b61d0c7)

- [Hot reloading in React apps with code splitting](https://medium.com/zoover-engineering/hot-reloading-in-react-apps-with-code-splitting-17e6793fc80d) - Looks at complexities in using RHL and React-Loadable together, and shows a Babel plugin that can help turn off code-splitting in development mode.xwxw

#### Other Tips and Examples

- [Course: Using Webpack for Production Javascript Apps](https://egghead.io/courses/using-webpack-for-production-javascript-applications) - A video course by Kent C. Dodds, covering a number of very useful Webpack techniques for real-world apps.  Requires an Egghead subscription, but solid and useful info.

- [Javascript at Tumblr - Switching to Webpack](https://javascript.tumblr.com/post/143583264647/here-at-tumblr-we-use-a-js-bundler-to-compile-our) - Tumblr's dev team talks about switching from Browserify to Webpack, their migration steps, and some useful tips learned about pieces like CommonsChunkPlugin.

- [Webpack HTML plugin in a Nutshell](http://www.jonathan-petitcolas.com/2016/01/23/webpack-html-plugin-in-a-nutshell.html) - Looks at what the HTML Webpack plugin can do and how to use it.

- [Truly Multiple Entries with Webpack](https://kuzzmi.com/blog/truly-multiple-entries-with-webpack) - Instructions on how to configure multiple entry points properly

- [Long-term caching of static assets with Webpack](https://medium.com/@okonetchnikov/long-term-caching-of-static-assets-with-webpack-1ecb139adb95) - Gathers documentation on proper use of asset caching into one article to act as a complete guide.

- [Goodbye "../../../"](http://davidboyne.co.uk/2016/04/29/react-webpack-gem.html) - Tips and discussion on removing relative paths when importing

- [Using the HTML Webpack Plugin for generating HTML files](http://javascriptplayground.com/blog/2016/07/webpack-html-plugin/) - Basic instructions for setting up the HTML Webpack plugin

- [Setting up CSS Modules with React and Webpack](http://javascriptplayground.com/blog/2016/07/css-modules-webpack-react/) - Covers setting up and configuring Webpack to use CSS Modules for styling

- [Webpack Map Entity Loader](http://drhayes.io/secret-game/map-entity-loader.html) - A small example of writing a custom Webpack loader for game data

- [Webpack Tricks](https://github.com/rstacruz/webpack-tricks) - A useful list of tips for improving Webpack usage

- [Useful Webpack DefinePlugin Usage](http://tomasalabes.me/blog/_site/web-development/2017/01/03/Useful-Webpack-Define-Plugin-Usages.html) - Several useful tips and use cases for using the Webpack DefinePlugin, including logging, feature flags, and handling multiple environments

- [Artsy Webpack Tour](https://github.com/TheLarkInn/artsy-webpack-tour) - Sean Larkin of the Webpack core team gives a visually annotated tour of the Webpack 2 source code

- [Squeezing Webpack into backend frameworks](https://infinum.co/the-capsized-eight/squeezing-webpack-into-backend-frameworks) - Covers how to use Webpack to replace the Rails asset pipeline

- [Easy Offline First Apps with Webpack's Offline Plugin](https://dev.to/kayis/easy-offline-first-apps-with-webpacks-offline-plugin) - A look at how to use the OfflinePlugin to cache Webpack-generated assets for offline use.

- [Working with Fonts with Webpack](https://shellmonger.com/2016/01/22/working-with-fonts-with-webpack/) - Explains how to configure Webpack to use external font files.

- [Working on OkCupid "in production" with Webpack and localhost](https://tech.okcupid.com/working-on-okcupid-in-production-with-webpack-and-localhost/) - Describes setting up Webpack-Dev-Server to serve local files during development in a distributed build system.

- [Predictable long term caching with Webpack](https://medium.com/@schnibl/predictable-long-term-caching-with-webpack-d3eee1d3fa31) - A detailed look at issues that cause caching problems, and how to configure Webpack to get consistent chunk definitions for good caching results

- [Environment based application configuration using Webpack](https://kostasbariotis.com/environment-based-application-configuration-using-webpack/) - An explanation of how environment-based configuration is useful, and a couple examples of ways to handle config files for varying environments.

- [From Grunt and Bower to Webpack, Babel, and Yarn - Migrating a legacy front-end build system](https://medium.com/appifycanada/migrate-to-webpack-from-grunt-bower-legacy-build-system-344526f47873) - A recap of the steps needed to migrate an Angular app's build system to Webpack, including managing imports, handling global variables, and code splitting.

- [Case study: improving the Polished size for Webpack users](https://iamakulov.com/notes/polished-webpack/) - A detailed investigation of bundle size issues for the Polished library, and steps taken to improve the sizes for distribution.

- [Unambiguous Webpack Config with Typescript](https://medium.com/webpack/unambiguous-webpack-config-with-typescript-8519def2cac7) - Shows how to use Typescript and type definitions to ensure correct setup of Webpack configs.

- [Webpack 2 & Semantic-UI Theming](https://medium.com/webmonkeys/webpack-2-semantic-ui-theming-a216ddf60daf) - Discusses how to configure Webpack to load Semantic-UI's LESS files to allow use of a custom theme.

- [Webpack: Creating dynamically named outputs for wildcarded entry files](https://medium.com/@sanjsanj/webpack-creating-dynamically-named-outputs-for-wildcarded-entry-files-9241f596b065) - Demonstrates a useful technique for collecting files based on globbing, and generating Webpack entry definitions from those files.

- [To ship less code, write transpiler-aware Javascript](https://medium.com/@jbartos/to-ship-less-code-write-transpiler-aware-javascript-a56250296760) - Tips for improving bundle size by using syntax supported natively by browsers, as well as other techniques for improving bundle output.

- [Deploying ES2015+ Code in Production Today](https://philipwalton.com/articles/deploying-es2015-code-in-production-today/) - Discusses a way to use `script type="module"` loading as a way to determine if a browser supports most modern syntax, and how to configure Babel to target modern browsers.  Not Webpack specific, but useful.

- [Long term caching using Webpack records](https://medium.com/@songawee/long-term-caching-using-webpack-records-9ed9737d96f2) - Looks at how to use the RecordsPlugin to ensure consistent filenames between builds, allowing for more predictable bundle output for long-term caching of files.

- The Contributor's Guide to Webpack - A series by Webpack maintainer Sean Larkin that dives into the internals of Webpack. Topics include packages that are maintained by the Webpack core team, the Tapable plugin base class, and how Webpack builds its dependency graph.
  - [Part 1](https://medium.com/webpack/the-contributors-guide-to-webpack-part-1-a0410cc82ca4)
  - [Part 2](https://medium.com/webpack/the-contributors-guide-to-webpack-part-2-9fd5e658e08c)
  - [Part 3](https://medium.com/webpack/the-contributors-guide-to-webpack-part-3-44cc149af02c)

#### Webpack Tools

- [Webpack Dashboard](https://github.com/FormidableLabs/webpack-dashboard)
  A CLI dashboard for your webpack dev server

- [Webpack Visualizer](https://chrisbateman.github.io/webpack-visualizer/)
  A tool and plugin to visualize the (pre-minified) sizes of files in a Webpack bundle

- [Webpack Bundle Analyzer](https://github.com/th0r/webpack-bundle-analyzer)
  Webpack plugin and CLI utility that represents bundle content as convenient interactive zoomable treemap, and can parse minified bundles to show true minified (and gzipped) sizes

- [source-map-explorer](https://github.com/danvk/source-map-explorer)
  Analyze and debug JavaScript (or Sass or LESS) code bloat through source maps.  Help determine which file each byte in your minified code came from.

- [bundle-buddy](https://github.com/samccone/bundle-buddy)
  Bundle Buddy is a tool to help you find source code duplication across your javascript chunks/splits. This enables you to fine tune code splitting parameters to reduce bundle invalidation rates as well as improve repeat page load performance.


### Other

- [Juho, Johannes, Tobias & Sean on JavaScript Air](http://jsair.io/webpack) - [JavaScript Air](https://javascriptair.com) podcast
- [Webpack interview questions](https://github.com/styopdev/webpack-interview-questions) - Interview questions with answers.
- [Visual config tool for webpack](https://webpack.jakoblind.no) - A visual tool for creating webpack configs in your browser

[Back to top](#contents)

[twittericon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/twitter-square.svg
[githubicon]: https://rawgit.com/d3viant0ne/awesome-webpack/master/media/github-square.svg
