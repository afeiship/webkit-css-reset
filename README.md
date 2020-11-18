# wsui-reset
> Reset css for wsui.

[![version][version-image]][version-url]
[![license][license-image]][license-url]
[![size][size-image]][size-url]
[![download][download-image]][download-url]

## installation
```shell
npm i @jswork/wsui-reset
```

## usage
```scss
// will reset a/h1-6/ul and..
@import '~@jswork/wsui-reset';

// or use basic reset styles
@import '~@jswork/wsui-reset/dist/base.scss';
```

## options
> you can customize use `sass`

```scss
$wsui-reset-options: (
  font-family: "STHeiti, Microsoft YaHei, Helvetica, Arial, sans-serif",
  header1: 14px,
  header4: 12px
) !default;
```

## license
Code released under [the MIT license](https://github.com/afeiship/wsui-reset/blob/master/LICENSE.txt).

[version-image]: https://img.shields.io/npm/v/@jswork/wsui-reset
[version-url]: https://npmjs.org/package/@jswork/wsui-reset

[license-image]: https://img.shields.io/npm/l/@jswork/wsui-reset
[license-url]: https://github.com/afeiship/wsui-reset/blob/master/LICENSE.txt

[size-image]: https://img.shields.io/bundlephobia/minzip/@jswork/wsui-reset
[size-url]: https://github.com/afeiship/wsui-reset/blob/master/dist/wsui-reset.min.js

[download-image]: https://img.shields.io/npm/dm/@jswork/wsui-reset
[download-url]: https://www.npmjs.com/package/@jswork/wsui-reset

