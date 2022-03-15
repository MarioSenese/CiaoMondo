# @mariosenese/ciaomondo

[![npm (scoped)](https://img.shields.io/npm/v/@mariosenese/ciaomondo)](https://www.npmjs.com/package/@mariosenese/ciaomondo)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@mariosenese/ciaomondo)](https://www.npmjs.com/package/@mariosenese/ciaomondo)
[![license](https://img.shields.io/github/license/MarioSenese/create-readme)](https://github.com/MarioSenese/CiaoMondo/blob/main/LICENSE)

First NPM package - CiaoMondo

## Install

```
$ npm install @mariosenese/ciaomondo
```

## Usage

Call external script into <head></head>

```html
<head>
  <script type="module" src="index.js"></script>
</head>
```
In index.js file, insert the next code

```js
import {} from './node_modules/@mariosenese/ciaomondo/index.js'; 
import {stampaMessaggio} from './node_modules/@mariosenese/ciaomondo/index.js'; 
stampaMessaggio();
```

