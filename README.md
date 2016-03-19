# is-xlsx
Detect xlsx file type from buffer

## Install

```
npm install is-xlsx
```

## Usage

```js
const fs = require('fs');
const isXlsx = require('is-xlsx');

const file = fs.readFileSync('example.xlsx');

console.log(isXlsx(file)); // > true
```
