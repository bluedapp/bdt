# bdt

Blued Developer Tools

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![NPM downloads][downloads-image]][npm-url]
[![Node.js dependencies][david-image]][david-url]


### Installation

Prerequisites: [Node.js](https://nodejs.org/en/) (6.x preferred).

``` bash
$ npm install -g bdt
```

### Usage

``` bash
$ bdt -h // 帮助文档
$ bdt init <template-name> <project-name> // 初始化项目
$ bdt deploy pro // 部署到正式环境
$ bdt deploy dev // 部署到测试环境
```

Example:

``` bash
$ bdt init node my-project
$ bdt deploy dev
```


[npm-image]: https://img.shields.io/npm/v/bdt.svg?style=flat-square
[npm-url]: https://npmjs.org/package/bdt
[travis-image]: https://img.shields.io/travis/bluedapp/bdt/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/bluedapp/bdt
[downloads-image]: https://img.shields.io/npm/dm/bdt.svg?style=flat-square
[david-image]: https://img.shields.io/david/bluedapp/bdt.svg?style=flat-square
[david-url]: https://david-dm.org/bluedapp/bdt
