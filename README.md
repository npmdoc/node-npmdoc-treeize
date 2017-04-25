# npmdoc-treeize

#### basic api documentation for  [treeize (v2.0.2)](https://github.com/kwhitley/treeize#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-treeize.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-treeize) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-treeize.svg)](https://travis-ci.org/npmdoc/node-npmdoc-treeize)

#### Converts tabular row data (as from SQL joins, flat JSON, etc) to deep object graphs based on simple column naming conventions - without the use of an ORM or models.

[![NPM](https://nodei.co/npm/treeize.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/treeize)

- [https://npmdoc.github.io/node-npmdoc-treeize/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-treeize/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-treeize/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-treeize/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-treeize/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-treeize/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "K. R. Whitley",
        "url": "http://krwhitley.com/"
    },
    "bugs": {
        "url": "https://github.com/kwhitley/treeize/issues"
    },
    "dependencies": {
        "inflection": "~1.2.6",
        "lodash": "~1.3.1",
        "object-merge": "~2.5.1"
    },
    "description": "Converts tabular row data (as from SQL joins, flat JSON, etc) to deep object graphs based on simple column naming conventions - without the use of an ORM or models.",
    "devDependencies": {
        "grunt": "latest",
        "grunt-cli": "latest",
        "grunt-contrib-jshint": "latest",
        "grunt-contrib-nodeunit": "latest",
        "grunt-contrib-watch": "latest",
        "grunt-mocha-test": "~0.12.0",
        "mocha": "latest",
        "should": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "e8f5a0a8275d7c7273770a4ef5d1b13e256f988b",
        "tarball": "https://registry.npmjs.org/treeize/-/treeize-2.0.2.tgz"
    },
    "gitHead": "0d8f89bc0032b7d33805cd4b1581e61c20f53e9a",
    "homepage": "https://github.com/kwhitley/treeize#readme",
    "keywords": [
        "JSON",
        "SQL",
        "CSV",
        "excel",
        "tree",
        "object",
        "graph",
        "hydration",
        "incongrous",
        "multi-source",
        "model",
        "deep",
        "convert",
        "expand",
        "flat",
        "array",
        "ORM"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://en.wikipedia.org/wiki/MIT_License"
        }
    ],
    "main": "./lib/treeize.js",
    "maintainers": [
        {
            "name": "kwhitley"
        }
    ],
    "name": "treeize",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kwhitley/treeize.git"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "2.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
