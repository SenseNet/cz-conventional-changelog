# sensenet-kfi-cz-conventional-changelog

[![npm version](https://img.shields.io/npm/v/sensenet-kfi-cz-conventional-changelog.svg?style=flat-square)](https://www.npmjs.com/package/sensenet-kfi-cz-conventional-changelog)
[![npm downloads](https://img.shields.io/npm/dm/sensenet-kfi-cz-conventional-changelog.svg?style=flat-square)](http://npm-stat.com/charts.html?package=sensenet-kfi-cz-conventional-changelog&from=2015-08-01)
[![Build Status](https://img.shields.io/travis/commitizen/sensenet-kfi-cz-conventional-changelog.svg?style=flat-square)](https://travis-ci.org/sensenet/sensenet-kfi-cz-conventional-changelog)

## Install and config

```
$ npm install --save commitizen sensenet-kfi-cz-conventional-changelog
```

Add following config to your projects package.json

```
"config": {
    "commitizen": {
      "path": "sensenet-kfi-cz-conventional-changelog"
    }
}
```

Add the following script to your projects package.json

```
"commit": "git-cz"
```

## Usage

Run the following

```
npm run commit
```

Part of the [commitizen](https://github.com/commitizen/cz-cli) family. Prompts for [conventional changelog](https://github.com/stevemao/conventional-changelog-angular/blob/master/index.js) standard for the sensenet KFI project.
