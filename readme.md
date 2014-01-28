# BFluid Grid System

** BFluid v2 - CSS grids for LESS **

## Use

LESS
```css
@import "path/to/bfluid.less";

@grid-layout: 6;
@grid-gutter: 40;
@grid-container: 1200;

@grid-use-media: true;
@grid-media-namespace: small tiny;
@grid-media-breakpoint: 55em 35em;
@grid-media-direction: max;

@grid-name-container: columns;
@grid-name-column: col;

#grid.build();
```

HTML
```
<div class="columns_6">
	<div class="col_2 small_col_3 tiny_col_6">ONE</div>
	<div class="col_2 small_col_3 tiny_col_6">TWO</div>
	<div class="col_2 small_col_6">THREE</div>
</div>
```

## License

[The MIT License (MIT)](LICENCE.md)

Copyright (c) 2014 Blowback - https://github.com/BlowbackDesign