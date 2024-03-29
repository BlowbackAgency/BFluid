# BFluid Grid System

**CSS grids for LESS**

BFluid v2.0.1 and up requires LESS.js [v1.7.1](https://github.com/less/less.js/releases/tag/v1.7.1) or newer.

## Use example

LESS
```css
@import "path/to/bfluid.less";

@grid-layout: 6; // layout column count, can be many (eg. 6 10 24) but beware bloat!
@grid-gutter: 40; // gutter size, relative to container (gutter/container)
@grid-container: 1200; // container size, relates to gutter...

@grid-use-media: true; // enable media query breakpoints
@grid-media-direction: min; // set direction `min` for mobile first
@grid-media-namespace: large huge; // define namespaces for media queries
@grid-media-breakpoint: 52em 76em; // define breakpoints for media queries

// let's mod output a little, I hate that default underscore...
@grid-name-separator: -;
@grid-name-container: columns;
@grid-name-column: col;

// we want to disable stuff from output we do not use
@grid-use-prefix: false;
@grid-use-suffix: false;
@grid-use-push: false;
@grid-use-pull: false;

// execute build
#grid.build();
```

HTML
```html
<div class="columns-6">
	<div class="col-6 large-col-3 huge-col-2">ONE</div>
	<div class="col-6 large-col-3 huge-col-2">TWO</div>
	<div class="col-6 huge-col-2">THREE</div>
</div>
```

## License

[The MIT License (MIT)](LICENCE.md)

Copyright (c) 2014 Blowback - https://github.com/BlowbackDesign