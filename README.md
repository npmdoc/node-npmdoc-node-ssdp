# npmdoc-node-ssdp

#### basic api documentation for  [node-ssdp (v3.2.1)](https://github.com/diversario/node-ssdp#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-ssdp.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-ssdp) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-ssdp.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-ssdp)

#### A node.js SSDP client and server library.

[![NPM](https://nodei.co/npm/node-ssdp.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-ssdp)

- [https://npmdoc.github.io/node-npmdoc-node-ssdp/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-ssdp/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-ssdp/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-ssdp/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-ssdp/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-ssdp/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ilya Shaisultanov"
    },
    "bugs": {
        "url": "https://github.com/diversario/node-ssdp/issues"
    },
    "dependencies": {
        "async": "^2.1.4",
        "bluebird": "^3.4.7",
        "debug": "^2.3.3",
        "extend": "^3.0.0",
        "ip": "^1.1.4"
    },
    "description": "A node.js SSDP client and server library.",
    "devDependencies": {
        "chai": "^3.5.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.2",
        "mocha-istanbul": "^0.3.0",
        "sinon": "^1.17.6"
    },
    "directories": {
        "example": "example",
        "test": "test"
    },
    "dist": {
        "shasum": "02fe518e6256b6029a5819bbe73daab278329606",
        "tarball": "https://registry.npmjs.org/node-ssdp/-/node-ssdp-3.2.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "f6557db95190802bec8d3daf598ae23da0472d06",
    "homepage": "https://github.com/diversario/node-ssdp#readme",
    "keywords": [
        "ssdp",
        "multicast",
        "media",
        "device",
        "upnp"
    ],
    "license": "MIT",
    "main": "./index",
    "maintainers": [
        {
            "name": "diversario"
        }
    ],
    "name": "node-ssdp",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/diversario/node-ssdp.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/.bin/_mocha -- test/lib --recursive",
        "test": "mocha --recursive test"
    },
    "version": "3.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
