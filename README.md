# npmdoc-babel-plugin-rewire

#### basic api documentation for  [babel-plugin-rewire (v1.1.0)](https://github.com/speedskater/babel-plugin-rewire#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-babel-plugin-rewire.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babel-plugin-rewire) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babel-plugin-rewire.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babel-plugin-rewire)

#### A babel plugin adding the ability to rewire module dependencies. This enables to mock modules for testing purposes.

[![NPM](https://nodei.co/npm/babel-plugin-rewire.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/babel-plugin-rewire)

- [https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babel-plugin-rewire/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "r.binna@synedra.com"
    },
    "bugs": {
        "url": "https://github.com/speedskater/babel-plugin-rewire/issues"
    },
    "contributors": [
        {
            "name": "Robert Binna"
        },
        {
            "name": "Peet Goddard"
        },
        {
            "name": "Eli White"
        },
        {
            "name": "Philip Spitzlinger"
        },
        {
            "name": "Gustaf Dalemar"
        }
    ],
    "dependencies": {},
    "description": "A babel plugin adding the ability to rewire module dependencies. This enables to mock modules for testing purposes.",
    "devDependencies": {
        "babel-cli": "^6.10.1",
        "babel-plugin-syntax-async-functions": "^6.8.0",
        "babel-plugin-syntax-flow": "^6.8.0",
        "babel-plugin-syntax-jsx": "^6.8.0 ",
        "babel-plugin-transform-async-to-generator": "^6.8.0",
        "babel-plugin-transform-es2015-block-scoping": "^6.10.1 ",
        "babel-plugin-transform-es2015-template-literals": "^6.8.0",
        "babel-plugin-transform-es2015-typeof-symbol": "^6.8.0",
        "babel-plugin-transform-export-extensions": "^6.8.0",
        "babel-plugin-transform-flow-strip-types": "^6.18.0",
        "babel-plugin-transform-object-rest-spread": "^6.8.0",
        "babel-plugin-transform-react-jsx": "^6.8.0",
        "babel-plugin-transform-regenerator": "^6.9.0",
        "babel-plugin-transform-runtime": "^6.9.0",
        "babel-polyfill": "^6.9.1",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-react": "^6.11.0",
        "babel-preset-stage-0": "^6.16.0",
        "babel-runtime": "^6.11.6",
        "chai": "^3.5.0",
        "core-js": "^1.0.0",
        "expect.js": "^0.3.1",
        "mocha": "^2.2.4",
        "node-hook": "^0.1.0",
        "react": "^15.1.0",
        "react-dom": "^15.1.0",
        "regenerator-runtime": "^0.9.5",
        "should": "^9.0.2",
        "sinon": "^1.17.4"
    },
    "directories": {},
    "dist": {
        "shasum": "a6b966d9d8c06c03d95dcda2eec4e2521519549b",
        "tarball": "https://registry.npmjs.org/babel-plugin-rewire/-/babel-plugin-rewire-1.1.0.tgz"
    },
    "gitHead": "780598112e1a826a648cf21203f02c57bf1a46ce",
    "homepage": "https://github.com/speedskater/babel-plugin-rewire#readme",
    "keywords": [
        "babel",
        "plugin",
        "rewire",
        "es6",
        "modules"
    ],
    "license": "ISC",
    "main": "lib/babel-plugin-rewire.js",
    "maintainers": [
        {
            "name": "speedskater"
        }
    ],
    "name": "babel-plugin-rewire",
    "optionalDependencies": {},
    "peerDependencies": {
        "babel-core": "^6.0.0",
        "babel-template": "^6.2.0",
        "babel-types": "^6.2.0"
    },
    "publishConfig": {
        "registry": "http://registry.npmjs.org/"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/speedskater/babel-plugin-rewire.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "prepublish": "babel src --out-dir lib",
        "test": "mocha && ./node_modules/.bin/mocha usage-tests"
    },
    "version": "1.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
