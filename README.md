# npmdoc-font-blast

#### api documentation for  [font-blast (v0.6.1)](https://github.com/eugene1g/font-blast)  [![npm package](https://img.shields.io/npm/v/npmdoc-font-blast.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-font-blast) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-font-blast.svg)](https://travis-ci.org/npmdoc/node-npmdoc-font-blast)

#### Converts any icon-font (Font Awesome etc) into individual SVG files for each icon.

[![NPM](https://nodei.co/npm/font-blast.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/font-blast)

- [https://npmdoc.github.io/node-npmdoc-font-blast/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-font-blast/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-font-blast/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-font-blast/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-font-blast/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-font-blast/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "eugene1g"
    },
    "bin": {
        "font-blast": "./bin/font-blast.js"
    },
    "bugs": {
        "url": "https://github.com/eugene1g/font-blast/issues"
    },
    "dependencies": {
        "commander": "2.*",
        "graceful-fs": "4.*",
        "mkdirp": "0.5.*",
        "svg2ttf": "4.*",
        "svgo": "0.7.*",
        "xmldom": "0.1.*"
    },
    "description": "Converts any icon-font (Font Awesome etc) into individual SVG files for each icon.",
    "devDependencies": {
        "babel-cli": "6.*",
        "babel-jest": ">=16",
        "babel-plugin-add-module-exports": ">=0.1",
        "babel-plugin-transform-flow-strip-types": "6.*",
        "babel-preset-es2015": "6.*",
        "jest": ">=16",
        "regenerator-runtime": "0.*",
        "rimraf": "2.*"
    },
    "directories": {},
    "dist": {
        "shasum": "d9b955ec5527a5e856b9a2dba771ca1b11304a71",
        "tarball": "https://registry.npmjs.org/font-blast/-/font-blast-0.6.1.tgz"
    },
    "gitHead": "82ed8cf9a6e475753b3f8498c50e5dc673b81656",
    "homepage": "https://github.com/eugene1g/font-blast",
    "jest": {
        "testPathIgnorePatterns": [
            "/lib/"
        ]
    },
    "keywords": [
        "svg",
        "font",
        "icon",
        "extract"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "eugene1g"
        }
    ],
    "name": "font-blast",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/eugene1g/font-blast.git"
    },
    "scripts": {
        "compile": "rimraf lib/* && babel src -d lib",
        "prepublish": "npm run compile",
        "test": "jest"
    },
    "version": "0.6.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
