# reset.css

A minimal CSS reset usable with [Normalize.css](https://github.com/necolas/normalize.css)

## Install

With curl:

```command
$ curl -O "https://unpkg.com/minimal-css-reset@1.0.0/reset.css"
$ curl -O "https://unpkg.com/minimal-css-reset@1.0.0/sass/_reset.scss"
$ curl -O "https://unpkg.com/minimal-css-reset@1.0.0/less/reset.less"
```

With [NPM](http://npmjs.com):

```command
$ npm install --save reset-css
```

With [Yarn](https://yarnpkg.com):

```command
$ yarn add reset-css
```

## Usage

HTML:

```html
<link rel="stylesheet" href="/path/to/minimal-css-reset/reset.css" />
```

CSS:

```css
@import '/path/to/minimal-css-reset/reset.css';
```

Via PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'minimal-css-reset';
```

Via webpack and [css-loader](https://github.com/webpack-contrib/css-loader):

```js
import 'minimal-css-reset';
```

Via Sass:

```scss
@import '/path/to/minimal-css-reset/sass/reset';
```

Via Less:

```less
@import '/path/to/minimal-css-reset/less/reset';
```

----

License: none (public domain)
