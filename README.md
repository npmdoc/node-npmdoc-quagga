# npmdoc-quagga

#### basic api documentation for  [quagga (v0.11.6)](https://github.com/serratus/quaggaJS#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-quagga.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-quagga) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-quagga.svg)](https://travis-ci.org/npmdoc/node-npmdoc-quagga)

#### An advanced barcode-scanner written in JavaScript

[![NPM](https://nodei.co/npm/quagga.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/quagga)

- [https://npmdoc.github.io/node-npmdoc-quagga/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-quagga/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-quagga/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-quagga/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-quagga/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-quagga/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Christoph Oberhofer"
    },
    "browser": "dist/quagga.min.js",
    "bugs": {
        "url": "https://github.com/serratus/quaggaJS/issues"
    },
    "dependencies": {
        "get-pixels": "^3.2.3",
        "gl-mat2": "^1.0.0",
        "gl-vec2": "^1.0.0",
        "gl-vec3": "^1.0.3",
        "lodash": "^4.17.4",
        "ndarray": "^1.0.18",
        "ndarray-linear-interpolate": "^1.0.0",
        "webrtc-adapter": "^2.0.2"
    },
    "description": "An advanced barcode-scanner written in JavaScript",
    "devDependencies": {
        "async": "^1.4.2",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.21.0",
        "babel-eslint": "^7.1.1",
        "babel-istanbul": "^0.8.0",
        "babel-istanbul-loader": "^0.1.0",
        "babel-loader": "^6.2.10",
        "babel-plugin-add-module-exports": "^0.2.1",
        "babel-plugin-check-es2015-constants": "^6.3.13",
        "babel-plugin-lodash": "^3.2.11",
        "babel-plugin-transform-es2015-arrow-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoping": "^6.21.0",
        "babel-plugin-transform-es2015-classes": "^6.3.13",
        "babel-plugin-transform-es2015-computed-properties": "^6.3.13",
        "babel-plugin-transform-es2015-destructuring": "^6.3.13",
        "babel-plugin-transform-es2015-for-of": "^6.3.13",
        "babel-plugin-transform-es2015-function-name": "^6.3.13",
        "babel-plugin-transform-es2015-literals": "^6.3.13",
        "babel-plugin-transform-es2015-modules-commonjs": "^6.3.13",
        "babel-plugin-transform-es2015-object-super": "^6.3.13",
        "babel-plugin-transform-es2015-parameters": "^6.21.0",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.3.13",
        "babel-plugin-transform-es2015-spread": "^6.3.13",
        "babel-plugin-transform-es2015-sticky-regex": "^6.3.13",
        "babel-plugin-transform-es2015-template-literals": "^6.3.13",
        "babel-plugin-transform-es2015-typeof-symbol": "^6.3.13",
        "babel-plugin-transform-es2015-unicode-regex": "^6.3.13",
        "babel-plugin-transform-object-rest-spread": "^6.5.0",
        "babel-plugin-transform-regenerator": "^6.21.0",
        "chai": "^3.4.1",
        "core-js": "^2.4.1",
        "cross-env": "^3.1.4",
        "eslint": "^1.10.3",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-nodeunit": "^0.4.1",
        "grunt-karma": "^2.0.0",
        "isparta-loader": "^2.0.0",
        "karma": "^1.3.0",
        "karma-chai": "0.1.0",
        "karma-chrome-launcher": "^2.0.0",
        "karma-coverage": "^1.1.1",
        "karma-firefox-launcher": "^0.1.7",
        "karma-mocha": "~0.2.0",
        "karma-phantomjs-launcher": "^0.2.1",
        "karma-sinon": "^1.0.4",
        "karma-sinon-chai": "^1.1.0",
        "karma-source-map-support": "^1.1.0",
        "karma-webpack": "^1.8.1",
        "lolex": "^1.4.0",
        "mocha": "^2.3.2",
        "phantomjs": "^1.9.18",
        "sinon": "^1.17.7",
        "sinon-chai": "^2.8.0",
        "webpack": "^2.2.0-rc.3",
        "webpack-sources": "^0.1.3"
    },
    "directories": {
        "doc": "doc"
    },
    "dist": {
        "shasum": "a799f9410c93661507c5309d59deef8c3d32c175",
        "tarball": "https://registry.npmjs.org/quagga/-/quagga-0.11.6.tgz"
    },
    "engines": {
        "node": ">= 4.0"
    },
    "gitHead": "b88a7b71a7ef954994b2c11c5dddf3e885e1e6ff",
    "homepage": "https://github.com/serratus/quaggaJS#readme",
    "keywords": [
        "quagga",
        "quaggajs",
        "barcode",
        "ean",
        "code128",
        "code39",
        "codabar",
        "i2of5",
        "upc",
        "getusermedia",
        "imageprocessing"
    ],
    "license": "MIT",
    "main": "lib/quagga.js",
    "maintainers": [
        {
            "name": "serratus"
        }
    ],
    "name": "quagga",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/serratus/quaggaJS.git"
    },
    "scripts": {
        "build": "npm run build:dev && npm run build:prod && npm run build:node",
        "build:dev": "cross-env BUILD_ENV=development webpack",
        "build:node": "cross-env BABEL_ENV=commonjs BUILD_ENV=node webpack --config webpack.node.config.js",
        "build:prod": "cross-env BUILD_ENV=production webpack --config webpack.config.min.js && grunt uglyasm",
        "integrationtest": "grunt integrationtest",
        "lint": "eslint src",
        "test": "cross-env BABEL_ENV=commonjs grunt test",
        "watch": "cross-env BUILD_ENV=development webpack --watch"
    },
    "version": "0.11.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
