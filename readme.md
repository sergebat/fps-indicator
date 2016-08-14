# fps [![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Micro fps indicator for demo/tests.

[![fps-indicator](https://raw.githubusercontent.com/dfcreative/fps-indicator/gh-pages/preview.png "fps-indicator")](http://dfcreative.github.io/fps-indicator/)

## Usage

[![npm install fps-indicator](https://nodei.co/npm/fps-indicator.png?mini=true)](https://npmjs.org/package/fps-indicator/)

```js
const createFps = require('fps');
let fps = createFps({container: document.body});

//to change color
fps.element.style.color = 'red';
```

## Similar

> [stats.js](https://www.npmjs.com/package/stats.js) — oldschool fps meter for apps, no colors customization.
> [fpsmeter](http://darsa.in/fpsmeter/) — good-looking fps meter, no npm package.