# ext-cmp

> A Vue.js component module

# Usage

## ES6 Modules / CommonJS

```bash
$ npm run build
```

```js
import ExtCmp from 'dist/ext-cmp';

Vue.component('ext-cmp', ExtCmp);
```

```html
<ext-cmp text="Hello World!"></ext-cmp>
```

## UMD

```bash
$ npm run build:umd
```

```html
<ext-cmp text="Hello World!"></ext-cmp>

<script src="https://unpkg.com/vue" charset="utf-8"></script>
<script src="./dist/ext-cmp.min.js" charset="utf-8"></script>

<script type="text/javascript">
  Vue.component('ext-cmp', window.ExtCmp);
</script>
```

## Installation

### Using yarn

`yarn add ext-cmp`

### Using npm

`npm i --save ext-cmp`

## Demo and Docs

`npm run serve`

## Tests

This template uses karma with chai by default, you can change test settings in poi.config.js

`npm run test`
`npm run test:watch`
`npm run test:cov`

## License

This project is licensed under [MIT License](http://en.wikipedia.org/wiki/MIT_License)
