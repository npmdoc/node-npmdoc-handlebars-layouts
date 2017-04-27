# npmdoc-handlebars-layouts

#### basic api documentation for  [handlebars-layouts (v3.1.4)](https://github.com/shannonmoeller/handlebars-layouts)  [![npm package](https://img.shields.io/npm/v/npmdoc-handlebars-layouts.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-handlebars-layouts) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-handlebars-layouts.svg)](https://travis-ci.org/npmdoc/node-npmdoc-handlebars-layouts)

#### Handlebars helpers which implement layout blocks similar to Jade, Jinja, Nunjucks, Swig, and Twig.

[![NPM](https://nodei.co/npm/handlebars-layouts.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/handlebars-layouts)

- [https://npmdoc.github.io/node-npmdoc-handlebars-layouts/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-handlebars-layouts/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-handlebars-layouts/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-handlebars-layouts/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-handlebars-layouts/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-handlebars-layouts/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Shannon Moeller",
        "url": "http://shannonmoeller.com"
    },
    "bugs": {
        "url": "https://github.com/shannonmoeller/handlebars-layouts/issues"
    },
    "dependencies": {},
    "description": "Handlebars helpers which implement layout blocks similar to Jade, Jinja, Nunjucks, Swig, and Twig.",
    "devDependencies": {
        "babel-eslint": "^4.1.1",
        "browserify": "^10.2.4",
        "consolidate": "^0.13.1",
        "coveralls": "^2.11.2",
        "expect": "^1.6.0",
        "express": "^4.12.4",
        "gulp": "^3.9.0",
        "gulp-eslint": "^0.14.0",
        "gulp-istanbul": "^0.10.0",
        "gulp-mocha": "^2.1.1",
        "gulp-prettify": "^0.3.0",
        "handlebars": "~3.0",
        "jshint-stylish": "^2.0.0",
        "through2": "^2.0.0",
        "vinyl-fs": "^1.0.0",
        "vinyl-source-stream": "^1.1.0",
        "zuul": "^3.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "26b3beb931b4b877dfbf7e6feaf4058ee6228b02",
        "tarball": "https://registry.npmjs.org/handlebars-layouts/-/handlebars-layouts-3.1.4.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "gitHead": "37a74b261a38db18d7f7be4613e5cdf252f95e03",
    "homepage": "https://github.com/shannonmoeller/handlebars-layouts",
    "keywords": [
        "blocks",
        "dust",
        "express",
        "handlebars",
        "hbs",
        "jade",
        "layout",
        "mote",
        "mustache",
        "nunjucks",
        "swig",
        "twig"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "shannonmoeller"
        }
    ],
    "name": "handlebars-layouts",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/shannonmoeller/handlebars-layouts.git"
    },
    "scripts": {
        "gulp": "gulp",
        "prepublish": "gulp build",
        "report": "cat ./coverage/lcov.info | coveralls",
        "test": "gulp test",
        "zuul": "zuul --local -- test/handlebars-layouts.spec.js"
    },
    "version": "3.1.4",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
