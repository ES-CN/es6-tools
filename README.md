# <img src="http://i.imgur.com/yy1sACZ.png" width="100px"/> ECMAScript 6 Tools

## 转译器

* [Babel](https://github.com/babel)
  * [Babel](https://github.com/babel/babel) - 进行预编译, 将 ES6+ 的代码转译到普通的 ES5 代码
  * [babelify](https://github.com/babel/babelify) - 包装成 [Browserify transform 模块](https://github.com/substack/node-browserify/wiki/list-of-transforms) 的 Babel 转译器
* [Google](https://github.com/google)
  * [Traceur compiler](https://github.com/google/traceur-compiler) - 将 ES6 的功能转换至 ES5, 包括 classes, generators, promises, destructuring patterns, default parameters 以及更多.
  * [es6ify](https://github.com/thlorenz/es6ify) - 包装成 [Browserify transform 模块](https://github.com/substack/node-browserify/wiki/list-of-transforms) 的 Traceur 转译器
* [Square](https://github.com/square)
  * [ES6-module-transpiler](https://github.com/square/es6-module-transpiler) - ES6 modules to AMD or CJS
  * [esnext](https://github.com/square/esnext) - (已收并到Babel) 下一代与现代 JS 的转换器
* [Facebook](https://github.com/facebook)
  * [Regenerator](https://github.com/facebook/regenerator) - 转换 ES6 的 yield/generator functions 到 ES5
  * [jstransform](https://github.com/facebook/jstransform) - 一个简单的支持可插拔J 语法转换的组件, 附带一个 ES6 -> ES5 转换器小集合
* 其它
  * [es6-transpiler](https://github.com/termi/es6-transpiler) - (已收并到Babel) ES6 > ES5. 包括 classes, destructuring, default parameters
  * [defs](https://github.com/olov/defs) - 转换 ES6 块作用域 const 和 let变量到 ES3 的 var
  * [es6_module_transpiler-rails](https://github.com/dockyard/es6_module_transpiler-rails) - 基于 Rails [Asset Pipeline](guides.ruby-china.org/asset_pipeline.html) 框架的 ES6 模块管理
  * [es6-macros](https://github.com/jlongster/es6-macros) 一些将 ES6 转译到 ES5 的小工具集
  * Bitovi's [transpile](https://github.com/bitovi/transpile) - 将 ES6 转译到 AMD, CJS, 和 StealJS.
  * [regexpu](https://github.com/mathiasbynens/regexpu) — 将 ES6 形式 (Unicode-aware) 的正则表达式转换到 ES5

## 构建时转译

### Grunt 任务
* Babel: [grunt-babel](https://github.com/babel/grunt-babel)
* Traceur: [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) [grunt-traceur-build](https://github.com/tarruda/grunt-traceur-build)
* ES6 Module Transpiler: [grunt-es6-module-transpiler](https://github.com/joefiorini/grunt-es6-module-transpiler)
* Regenerator: [grunt-regenerator](https://github.com/sindresorhus/grunt-regenerator) - ES6 generator functions to ES5
* [grunt-microlib](https://github.com/thomasboyt/grunt-microlib) - 适合库使用的使用了ES6 模块转译器的工具集 (示例 [Gruntfile](https://github.com/jakearchibald/ES6-Promises/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js))
* [grunt-defs](https://github.com/EE/grunt-defs) - 转换 ES6 块作用域 const 和 let变量 到 ES3 的工具
* es6-transpiler: [grunt-es6-transpiler](https://github.com/sindresorhus/grunt-es6-transpiler) - ES6 → ES5
* esnext: [grunt-esnext](https://github.com/shinnn/grunt-esnext)

### Gulp 插件
* Babel: [gulp-babel](https://github.com/babel/gulp-babel)
* Traceur: [gulp-traceur](https://github.com/sindresorhus/gulp-traceur)
* Regenerator: [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator)
* ES6 Module Transpiler: [gulp-es6-module-transpiler](https://github.com/ryanseddon/gulp-es6-module-transpiler)
* es6-transpiler: [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - ES6 → ES5
* es6-jstransform: [gulp-jstransform](https://github.com/hemanth/gulp-jstransform) - ES6 → ES5, 用了 FB 家的 [jstransform](https://github.com/facebook/jstransform)
* esnext: [gulp-esnext](https://github.com/sindresorhus/gulp-esnext)
* regexpu: [gulp-regexpu](https://github.com/mathiasbynens/gulp-regexpu)

### Broccoli 插件
* Babel: [broccoli-babel-transpiler](https://github.com/babel/broccoli-babel-transpiler)
* Traceur: [broccoli-traceur](https://github.com/sindresorhus/broccoli-traceur)
* Regenerator: [broccoli-regenerator](https://github.com/sindresorhus/broccoli-regenerator)
* ES6 Transpiler: [broccoli-transpiler](https://github.com/sindresorhus/broccoli-es6-transpiler)
* ES6 Module Transpiler: [broccoli-es6-module-transpiler](https://github.com/mmun/broccoli-es6-module-transpiler)
* esnext: [broccoli-esnext](https://github.com/shinnn/broccoli-esnext)
* ES6 fat arrow transpiler: [broccoli-es6-arrow](https://github.com/hemanth/broccoli-es6-arrow.git)

### Brunch 插件
* Babel: [babel-brunch](https://github.com/babel/babel-brunch)
* ES6 Module Transpiler: [es6-module-transpiler-brunch](https://github.com/gcollazo/es6-module-transpiler-brunch)

## Webpack 插件
* Babel: [babel-loader](https://github.com/babel/babel-loader)
* Traceur: [traceur-compiler-loader](https://github.com/gdi2290/traceur-compiler-loader)

## Duo 插件
* Babel: [duo-babel](https://github.com/babel/duo-babel)

## Connect 插件
* Babel: [babel-connect](https://github.com/babel/babel-connect)

## Gobble 插件
* Babel: [gobble-babel](https://github.com/babel/gobble-babel)
* Traceur: [gobble-es6-transpiler](https://github.com/gobblejs/gobble-es6-transpiler)

## Jade 插件
* Babel: [jade-babel](https://github.com/babel/jade-babel)
* Traceur: [jade-traceur](https://www.npmjs.org/package/jade-traceur)

## Jest plugins
* Babel: [babel-jest](https://github.com/babel/babel-jest)

## Karma 插件
* Babel: [karma-babel-preprocessor](https://github.com/babel/karma-babel-preprocessor)
* Traceur: [karma-traceur-preprocessor](https://github.com/karma-runner/karma-traceur-preprocessor)

## Sprockets 插件
* Babel: [sprockets-es6](https://github.com/josh/sprockets-es6)
* Traceur: [sprockets-traceur](https://github.com/gunpowderlabs/sprockets-traceur)


## Browser 插件
* [Scratch JS](https://github.com/richgilbank/Scratch-JS) - A Chrome/Opera DevTools extension to run ES6 on a page with either Babel or Traceur

## Mocha 插件
* [Mocha Traceur](https://github.com/domenic/mocha-traceur) - A simple plugin for Mocha to pass JS files through the Traceur compiler

## 模块加载器

* ES6 [Module Loader polyfill](https://github.com/ModuleLoader/es6-module-loader) (兼容最新的规范和Traceur)
* [js-loaders](https://github.com/jorendorff/js-loaders) - Mozilla's 符合规范的加载器原型
* [JSPM](http://jspm.io/) - ES6, AMD, CJS 模块加载/包管理
* [webpack](https://github.com/shama/es6-module-loader) 中使用的模块加载器
* [beck.js](https://github.com/unscriptable/beck) - 为遗留环境([legacy environment](http://en.wikipedia.org/wiki/Legacy_system))打造的 ES6 模块加载器管道 和 shim 工具箱

## Boilerplates
* [es6-boilerplate](https://github.com/davidjnelson/es6-boilerplate) - Tooling to allow the community to use es6 now via traceur in conjunction with amd and browser global modules, with source maps, concatenation, minification, compression, and unit testing in real browsers.

## 代码生成

* [generator-node-esnext](https://github.com/briandipalma/generator-node-esnext) - Yeoman generator for Traceur apps
* [generator-es6-babel](https://github.com/HenriqueLimas/generator-es6-babel) - Yeoman generator for Babel apps
* [grunt-init-es6](https://npmjs.org/package/grunt-init-es6) - scaffold node modules with unit tests, authored in ES6
* [Loom generators with ES6 ember modules](https://github.com/rpflorence/loom-generators-ember)
* Brunch [plugin](https://npmjs.org/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Polyfills

* [core-js](https://github.com/zloirock/core-js) - Modular and compact polyfills for ES6 including Symbols, Map, Set, Iterators, Promises, setImmediate, Array generics, etc. The standard library used by [Babel](https://github.com/babel/babel).
* [es6-shim](http://github.com/paulmillr/es6-shim) - almost all new ES6 methods — from Map, Set, String, Array, Object, Object.is and more.
* [WeakMap, Map, Set, HashMap - ES6 Collections](https://github.com/Benvie/harmony-collections)
* Polymer's [WeakMap shim](https://github.com/Polymer/WeakMap)
* [`String.prototype.startsWith`](https://github.com/mathiasbynens/String.prototype.startsWith)
* [`String.prototype.endsWith`](https://github.com/mathiasbynens/String.prototype.endsWith)
* [`String.prototype.at`](https://github.com/mathiasbynens/String.prototype.at)
* [`String.prototype.repeat`](https://github.com/mathiasbynens/String.prototype.repeat)
* [`String.prototype.includes`](https://github.com/mathiasbynens/String.prototype.includes)
* [`String.prototype.codePointAt`](https://github.com/mathiasbynens/String.prototype.codePointAt)
* [`String.fromCodePoint`](https://github.com/mathiasbynens/String.fromCodePoint)
* [`Array.prototype.find`](https://github.com/paulmillr/Array.prototype.find)
* [`Array.prototype.findIndex`](https://github.com/paulmillr/Array.prototype.findIndex)
* [`Array.from`](https://github.com/mathiasbynens/Array.from)
* [`Array.of`](https://github.com/mathiasbynens/Array.of)
* [`Object.assign`](https://github.com/sindresorhus/object-assign)
* [`Number.isFinite`](https://github.com/sindresorhus/is-finite)
* [`Math.sign`](https://github.com/sindresorhus/math-sign)
* [`RegExp.prototype.match`](https://github.com/mathiasbynens/RegExp.prototype.match)
* [`RegExp.prototype.search`](https://github.com/mathiasbynens/RegExp.prototype.search)
* [es6-promise](https://github.com/jakearchibald/ES6-Promises) - polyfill for Promises matching the ES6 API
* [ES6 Map Shim](https://github.com/eriwen/es6-map-shim) - destructive shim that follows the latest specification as closely as possible.
* [`Function.create`](https://github.com/walling/Function.create.js)
* [ES6 shim](https://github.com/inexorabletash/polyfill/blob/master/es6.md)
* [ES6 Symbol polyfill](https://github.com/medikoo/es6-symbol)
* [ES6 Map, Set, WeakMap](https://github.com/EliSnow/Blitz-Collections)
* [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES6 [reflection module](http://wiki.ecmascript.org/doku.php?id=harmony:reflect_api) (contains the [Proxy API](http://soft.vub.ac.be/~tvcutsem/proxies/))
* [ES5 based shims in pure CJS style](https://gist.github.com/medikoo/102b7d0e697627133788#list-of-ecmascript-6-shims) -  Array, Object, Number, Math and String functions/methods, plus Map, Set, Symbol and WeakMap objects

## 编辑器

* ES6 syntax highlighting for [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage)
* ES6 syntax support in [WebStorm](https://www.jetbrains.com/webstorm/) and [PhpStorm](https://www.jetbrains.com/phpstorm/), compilation to ES5 with [Traceur file watcher](https://www.youtube.com/watch?v=jbfkcmxLLKY)
* DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur

## 语法解析器

* [Esprima Harmony branch](https://github.com/ariya/esprima/tree/harmony) - Experimental branch of the Esprima parser which can parse ES6 features to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
* [Acorn](https://github.com/marijnh/acorn/) - A small, fast, JavaScript-based JavaScript parser with ES6 support, parses to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
* [esparse](https://github.com/zenparsing/esparse) - ES6 parser written in ES6.
* [Traceur compiler](https://github.com/google/traceur-compiler) also has built-in parser available under `traceur.syntax.Parser`.

## 其它

* [ES.next showcase](https://github.com/sindresorhus/esnext-showcase) - real-world usage examples of ES6 features
* [looper](https://github.com/wycats/looper) - static analysis tools for ES6
* [es6-module-packager](https://npmjs.org/package/es6-module-packager)
* [es-dependency-graph](https://github.com/yahoo/es-dependency-graph) and [grunt-es-dependency-graph](https://github.com/yahoo/grunt-es-dependency-graph) - Generate a list of imports and exports from ES6 module files, useful for preloading, bundling, etc.
* [es6-import-validate](https://github.com/sproutsocial/es6-import-validate) and [grunt-es6-import-validate](https://github.com/sproutsocial/grunt-es6-import-validate) - validate matching named/default import statements in ES6 modules.
* [let-er](https://github.com/getify/let-er) - transpiles [let-block block-scoping](http://wiki.ecmascript.org/doku.php?id=proposals:block_expressions#let_statement) (not accepted into ES6) into either ES3 or ES6
* [Recast](https://github.com/benjamn/recast) - Esprima-based JavaScript syntax tree transformer, conservative pretty-printer, and automatic source map generator. Used by several of the transpilers listed above, including [regenerator](https://github.com/facebook/regenerator) and [es6-arrow-function](https://github.com/square/es6-arrow-function).
* [Paws on ES6](https://github.com/hemanth/paws-on-es6) -  Minimalist examples of ES6 functionalities.
* [ES6 on node](http://h3manth.com/new/blog/2013/es6-on-nodejs/) - How to use ES6 features in node.js.
* [es6-translate](https://github.com/calvinmetcalf/es6-translate) - Uses the ES6 loader hooks to load (node flavored) commonjs packages in ES6.
* [Isparta](https://github.com/douglasduteil/isparta)
* [babel-node](http://babeljs.io/docs/usage/cli/#babel-node) - Run node cli with ES6 transpiling using Babel.
* [ES6 Lab setup](https://github.com/hemanth/es6-lab-setup) - A simple setup for transpiling ES6 to ES5 using `6to5` or `traceur` with `gulp` and `jasmine` support.
* [TypeScript](http://www.typescriptlang.org/) - A superset of ECMAScript with strict typing that aims to align with ES6
