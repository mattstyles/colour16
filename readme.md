
# colour16

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Dependency Status](https://david-dm.org/mattstyles/colour16.svg)](https://david-dm.org/mattstyles/colour16)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)

> Some 16-colour palettes

## Getting started

```sh
npm install -S colour16
```

Each palette exposes an array of 16 colours, you can also key by colour name too.

```js
const { db } = require('db')

document.body.style.background = db.blue
document.body.style.color = db[2]
```

You can reach in to the package and pull out just single palettes rather than rely on destructuring and then tree shaking to strip unused palettes.

```js
const c64 = require('db/c64')
```

## License

MIT
