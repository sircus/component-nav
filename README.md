# sircus-tools-layout-responsive

[![npm version](https://img.shields.io/npm/v/sircus-tools-layout-responsive.svg?style=flat)](https://www.npmjs.com/package/sircus-tools-layout-responsive)

## Dependencies
- [sircus-global-property](https://github.com/sircus/global-property)


## Installation

> npm:

```bash
$ npm install sircus-tools-layout-responsive sircus-global-property
```

## Usage

> cssnext:

input.css
```css
@import "sircus-tools-layout-responsive";
/*
@import "sircus-tools-layout-responsive/lib/sm";
@import "sircus-tools-layout-responsive/lib/md";
@import "sircus-tools-layout-responsive/lib/lg";
*/
@import "sircus-global-property";
```

> sass:

input.scss
```scss
@import "./node_modules/sircus-global-property/converted";
@import "./node_modules/sircus-tools-layout-responsive/converted";
// @import "./node_modules/sircus-tools-layout-responsive/scss/sm";
// @import "./node_modules/sircus-tools-layout-responsive/scss/md";
// @import "./node_modules/sircus-tools-layout-responsive/scss/lg";
```


> html

```html
<div class="t-sm-pullRight"></div>
<div class="t-sm-pullLeft"></div>
<div class="t-sm-pullNone"></div>
<div class="t-sm-static"></div>
<div class="t-sm-absolute"></div>
<div class="t-sm-fixed"></div>
<div class="t-sm-relative"></div>
<div class="t-sm-center"></div>

<div class="t-md-pullRight"></div>
<div class="t-md-pullLeft"></div>
<div class="t-md-pullNone"></div>
<div class="t-md-static"></div>
<div class="t-md-absolute"></div>
<div class="t-md-fixed"></div>
<div class="t-md-relative"></div>
<div class="t-md-center"></div>

<div class="t-lg-pullRight"></div>
<div class="t-lg-pullLeft"></div>
<div class="t-lg-pullNone"></div>
<div class="t-lg-static"></div>
<div class="t-lg-absolute"></div>
<div class="t-lg-fixed"></div>
<div class="t-lg-relative"></div>
<div class="t-lg-center"></div>
```


## Contributing

We Need Your Help!


## License
Released under the [MIT](https://github.com/sircus/license/blob/master/LICENSE) license.
