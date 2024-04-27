# @f1stnpm2/atque-dolorum-quia [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Meet%20this%20awesome%20library&url=https://github.com/f1stnpm2/atque-dolorum-quia&via=nicolasvanhoren&hashtags=javascript,asyncawait,async,libraries,programming)

![logo](https://github.com/f1stnpm2/atque-dolorum-quia/raw/master/img/facebook_cover_photo_2_680.png)

[![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/@f1stnpm2/atque-dolorum-quia?style=social)](https://github.com/f1stnpm2/atque-dolorum-quia/stargazers) [![Website](https://img.shields.io/website.svg?url=http%3A%2F%2Fnicolas-van.github.io%2F@f1stnpm2/atque-dolorum-quia)](https://nicolas-van.github.io/@f1stnpm2/atque-dolorum-quia)
[![Node.js CI](https://github.com/f1stnpm2/atque-dolorum-quia/workflows/Node.js%20CI/badge.svg)](https://github.com/f1stnpm2/atque-dolorum-quia/actions) [![npm](https://img.shields.io/npm/v/@f1stnpm2/atque-dolorum-quia)](https://www.npmjs.com/package/@f1stnpm2/atque-dolorum-quia) [![Coverage Status](https://coveralls.io/repos/github/nicolas-van/@f1stnpm2/atque-dolorum-quia/badge.svg?branch=master)](https://coveralls.io/github/nicolas-van/@f1stnpm2/atque-dolorum-quia?branch=master) [![](https://data.jsdelivr.com/v1/package/npm/@f1stnpm2/atque-dolorum-quia/badge)](https://www.jsdelivr.com/package/npm/@f1stnpm2/atque-dolorum-quia)

A modern JavaScript tooling library for asynchronous operations using async/await, promises and async generators.

This library is a modernized alternative to a lot of libraries like [Async.js](https://caolan.github.io/async/v3/) that were created using the legacy callback style to handle asynchronous operations. Its goal is to be as complete as any of those libraries while being built from the very beginning with async/await and promises in mind.

[See the documentation](https://nicolas-van.github.io/@f1stnpm2/atque-dolorum-quia).

* Exclusively uses async/await, promises and async generators in its code, tests and documentation.
* Has low bundle size.
* Has 100% code coverage.
* Bundled for ESM modules, CommonJS and UMD.
* Works in node >= 8 and in the vast majority of browsers (very old browser compatibility can be achieved using Babel and shims).
* Has Typescript support.

[![Stargazers repo roster for @nicolas-van/@f1stnpm2/atque-dolorum-quia](https://reporoster.com/stars/nicolas-van/@f1stnpm2/atque-dolorum-quia)](https://github.com/f1stnpm2/atque-dolorum-quia/stargazers)

## Installation

```bash
npm install --save @f1stnpm2/atque-dolorum-quia
```

Or use [jsDelivr](https://www.jsdelivr.com/package/npm/@f1stnpm2/atque-dolorum-quia) to get the UMD version. The content of the library will be available under the `modernAsync` global variable.

## Usage

```javascript
import { asyncMap, asyncSleep } from '@f1stnpm2/atque-dolorum-quia'

const array = [1, 2, 3]
const result = await asyncMap(array, async (v) => {
  await asyncSleep(10)
  return v * 2
})
console.log(result)
```

[See the documentation for the rest](https://nicolas-van.github.io/@f1stnpm2/atque-dolorum-quia).

## Migrating from version 1.X to version 2.X

[See the migration guide](https://github.com/f1stnpm2/atque-dolorum-quia/blob/master/version-1-to-2-guide.md).

## Changelog

[The changelog](https://github.com/f1stnpm2/atque-dolorum-quia/blob/master/CHANGELOG.md).

## Contribution Guide

[The contribution guide](https://github.com/f1stnpm2/atque-dolorum-quia/blob/master/CONTRIBUTING.md)

## License

[The license](https://github.com/f1stnpm2/atque-dolorum-quia/blob/master/LICENSE.md).
