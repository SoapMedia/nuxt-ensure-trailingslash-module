# nuxt-ensure-trailingslash-module

[![npm (scoped with tag)](https://img.shields.io/npm/v/nuxt-ensure-trailingslash-module/latest.svg?style=flat-square)](https://npmjs.com/package/nuxt-ensure-trailingslash-module)
[![npm](https://img.shields.io/npm/dt/nuxt-ensure-trailingslash-module.svg?style=flat-square)](https://npmjs.com/package/nuxt-ensure-trailingslash-module)
[![js-standard-style](https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square)](http://standardjs.com)

> A NuxtJS module to add trailing slashes to URLs

## Table of Contents ##

* [Requirements](#requirements)
* [Install](#install)
* [Getting Started](#getting-started)

## Requirements

* npm or yarn
* NuxtJS
* NodeJS

## Install

```bash
$ npm install --save nuxt-ensure-trailingslash-module
// or
$ yarn add nuxt-ensure-trailingslash-module
```

## Getting Started

Add `nuxt-ensure-trailingslash-module` to `modules` section of `nuxt.config.js`.
```js
{
  modules: [
    // Simple usage
    'nuxt-ensure-trailingslash-module',

    // With options
    ['nuxt-ensure-trailingslash-module', {
      /* module options */
      methods: [
        'GET',
        'HEAD',
      ],
    }],
 ]
}
```
or even
```js
{
  modules: [
    'nuxt-ensure-trailingslash-module',
  ],
  trailingslash: {
    methods: [
      'GET',
      'HEAD',
    ],
  },
}
```

## License

[MIT License](./LICENSE)
