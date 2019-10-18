# reset.css

A minimal CSS reset usable with [Normalize.css](https://github.com/necolas/normalize.css)

## Install

With curl:

```command
$ curl -O "https://unpkg.com/minimal-css-reset@1.1.0/reset.min.css"
$ curl -O "https://unpkg.com/minimal-css-reset@1.1.0/sass/_reset.scss"
$ curl -O "https://unpkg.com/minimal-css-reset@1.1.0/less/reset.less"
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

## See in action 

[CodePen](https://codepen.io/trevonerd/pen/bGGwxGG)

## Changelog

- removed body margin.
- added body best practices 
- added inputs fonts reset
- fixed dl, dd reset
- removed blockquote left margin
- better image, video
- removed iframe border
- added th,td reset
- remove animations and transitions for people that prefer not to see them
- NEW minified version

----

License: none (public domain)
