common-classes
==============

Common and useful classes for quick and dirty web development.
Some classes are meant for prototyping  (grayscale.scss and margin-and-padding.scss)
but can also be used in production websites/web applications.

## Description of Sass Components included
----

### Clearfix
Copied from unsematic's clearfix.  It's here for convenience (not really necessary if you already have
something like unsemantic installed for you app).

### Display
Short hand classes for the display types:
- display-inline
- display-block
- display-none
- display-inline-block
- @todo add display-table-cell

### Float
Short hand classes for floats:
- float-left, fl
- float-right, fr
- clear-left, cl
- clear-right, cr
- clear-both, cb

### Grayscale
Short hand for grayscale colors and backgrounds:
- c-{0-F} (#000 - #fff)
- bg-{0-F} (#000 - #fff)

```
<div class="bg-3 c-d">
    This div has a dark background with light text on it.
</div>

### Key Value Pairs
Quick styling for fields that represent key value pairs in applications
(useful for key value pairs that are manipulated by javascript where
you want to show a selected value for a key):
- key-value-pair
- key-value-pair key
- key-value-pair value

```
<div class="key-value-pair">
<span class="key">Key:</span>
<span class="value">Value</span>
</div>
```

or

```
<div class="key-value-pair">
<label>Key:</label>
<span class="value">Value</span>
</div>
```

### Margin and Padding
Margin and Padding short hand classes:
- m (T R B L) (0 1 3 5 8 10 13 15 20 30 38 40) (px)
- p (T R B L) (0 1 3 5 8 10 13 15 20 30 38 40) (px)
- m0 = margin: 0;
- p0 = padding: 0;

```
<div class="m20px">
    This div has a margin of 20px
</div>
```

### Position
Short hand classes for position types:
- pos-rel = position: relative;
- pos-abs = position: absolute;
- pos-fix = position: fixed;

### Text
Short hand classes for text:
- text-left, tl
- text-right, tr
- text-justify, tj
- text-center, tc
- text-decor-underline

### Unordered List
Short hand classes for horizontal and vertical menus with opinionated defaults
(actually the styling for vert-menu* and horiz-menu* are compatible with all browsers
up to ie6):
- horiz-menu-left
- vert-menu-left

### Visibility
Short hand classes for visibility values:
-- visible
-- hidden
