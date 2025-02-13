# git-contributor

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][coveralls-image]][coveralls-url]
[![node version][node-image]][node-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/git-contributor.svg
[npm-url]: https://npmjs.org/package/git-contributor
[travis-image]: https://img.shields.io/travis/xudafeng/git-contributor.svg
[travis-url]: https://travis-ci.org/xudafeng/git-contributor
[coveralls-image]: https://img.shields.io/coveralls/xudafeng/git-contributor.svg
[coveralls-url]: https://coveralls.io/r/xudafeng/git-contributor?branch=master
[node-image]: https://img.shields.io/badge/node.js-%3E=_8-green.svg
[node-url]: http://nodejs.org/download/
[download-image]: https://img.shields.io/npm/dm/git-contributor.svg
[download-url]: https://npmjs.org/package/git-contributor

> Welcome to join in and feel free to contribute.

<!-- GITCONTRIBUTOR_START -->

## Contributors

|[<img src="https://avatars.githubusercontent.com/u/1011681?v=4" width="100px;"/><br/><sub><b>xudafeng</b></sub>](https://github.com/xudafeng)<br/>|[<img src="https://avatars.githubusercontent.com/u/1209810?v=4" width="100px;"/><br/><sub><b>paradite</b></sub>](https://github.com/paradite)<br/>|
| :---: | :---: |


This project follows the git-contributor [spec](https://github.com/xudafeng/git-contributor), auto updated at `Thu Nov 18 2021 01:33:21 GMT+0800`.

<!-- GITCONTRIBUTOR_END -->

## Who are using

- ⭐⭐⭐[antvis/g2](//github.com/antvis/g2)
- ⭐⭐⭐[cnpm/npminstall](//github.com/cnpm/npminstall)
- ⭐⭐⭐[alibaba/f2etest](//github.com/alibaba/f2etest)
- ⭐⭐⭐[alibaba/uirecorder](//github.com/alibaba/uirecorder)
- ⭐⭐⭐[hiloteam/Hilo](//github.com/hiloteam/Hilo)
- ⭐⭐⭐[node-modules/detect-port](//github.com/node-modules/detect-port)
- ⭐⭐⭐[node-modules/utility](//github.com/node-modules/utility)
- ⭐⭐⭐[node-modules/urllib](//github.com/node-modules/urllib)
- ⭐⭐⭐[macacajs/macaca-datahub](//github.com/macacajs/macaca-datahub)

[For more](//github.com/xudafeng/git-contributor/network/dependents)

## Spec

- The listings show all the contributors.
- Sort by contributions number.

If there is no `repository` field, fall back to the rule:

- Auto generate from git info.
- Sort by commit date.

## Installment

```bash
$ npm i git-contributor --save-dev
```

```json
"devDependencies": {
  ...
  "git-contributor": "*",
  ...
},
"scripts": {
  ...
  "contributor": "git-contributor",
  ...
}
```

```bash
$ npm run contributor
# github API service limit
$ OAUTH_TOKEN=****** npm run contributor
```

### Searching Sample

`encodeURIComponent('xudafeng@126.com')` will be convert to `xudafeng%40126.com`, please replace to test it.

```
https://api.github.com/search/users?q=xudafeng%40126.com%20in%3Aemail%20type%3Auser
```

## License

The MIT License (MIT)
