# npmdoc-materialize-css

#### api documentation for  materialize-css (v0.98.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-materialize-css.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-materialize-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-materialize-css.svg)](https://travis-ci.org/npmdoc/node-npmdoc-materialize-css)

#### Builds Materialize distribution packages

[![NPM](https://nodei.co/npm/materialize-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/materialize-css)

- [https://npmdoc.github.io/node-npmdoc-materialize-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-materialize-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-materialize-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-materialize-css/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-materialize-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-materialize-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "materialize-css",
    "description": "Builds Materialize distribution packages",
    "author": "Alvin Wang, Alan Chang",
    "url": "http://materializecss.com/",
    "version": "0.98.2",
    "main": "bin/materialize.js",
    "license": "MIT",
    "repository": {
        "type": "git",
        "url": "git://github.com/Dogfalo/materialize.git"
    },
    "dependencies": {
        "hammerjs": "^2.0.4",
        "jquery": "^2.1.4",
        "node-archiver": "^0.3.0"
    },
    "engine": "node >= 0.10",
    "devDependencies": {
        "autoprefixer": "^6.1.0",
        "grunt": "^0.4.5",
        "grunt-banner": "^0.6.0",
        "grunt-browser-sync": "^2.2.0",
        "grunt-concurrent": "^2.0.0",
        "grunt-contrib-clean": "^0.7.0",
        "grunt-contrib-compress": "^0.14.0",
        "grunt-contrib-concat": "^0.5.0",
        "grunt-contrib-copy": "^0.8.0",
        "grunt-contrib-cssmin": "^0.14.0",
        "grunt-contrib-jade": "^0.15.0",
        "grunt-contrib-jasmine": "^0.9.2",
        "grunt-contrib-uglify": "^0.11.0",
        "grunt-contrib-watch": "^0.6.0",
        "grunt-notify": "^0.4.1",
        "grunt-postcss": "^0.7.1",
        "grunt-remove-logging": "^0.2.0",
        "grunt-rename": "^0.1.4",
        "grunt-sass": "^1.1.0",
        "grunt-text-replace": "^0.4.0",
        "jasmine": "^2.3.2",
        "jasmine-jquery": "^2.1.1",
        "jquery": "^2.1.4",
        "node-sass": "^3.4.2",
        "phantomjs": "^1.9.18"
    },
    "scripts": {
        "test": "grunt travis --verbose"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
