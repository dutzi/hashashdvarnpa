# babel-plugin-hashashdvarnpa

Transform Hebrew characters to English

## Example

**In**

```js
כומבאןםמ כםם )( }
  בםמדםךקץךםע),יקךךם ׳םךרג!,(
{
```

**Out**

```js
function foo() {
  console.log('hello wolrd!');
}
```

## Installation

```sh
npm install babel-plugin-hashashdvarnpa
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["hashashdvarnpa"]
}
```

### Via CLI

```sh
$ babel --plugins hashashdvarnpa script.js
```

### Via Node API

```javascript
require('babel-core').transform('code', {
  plugins: ['hashashdvarnpa'],
});
```
