# Spacings
8-point spacings.

### Installation
```bash
npm i -D spacings
```

### Usage
```scss
// Place this at the top of your SCSS/CSS file
@use 'spacings';     /* for SCSS */
OR
@import 'spacings';  /* for CSS */
```

### Variables
```css
:root {
    --s-00: 0rem;       /* Zero */
    --s-01: 0.0625rem;  /* 1px */
    --s-02: 0.125rem;   /* 2px */
    --s-04: 0.25rem;    /* 4px */
    --s-08: 0.5rem;     /* 8px */
    ...
}
```

### Utilities
- Format: `.sp-u-[property][axis]-[value]`
- Properties: `m` margin, `p` padding
- Axes: `x` horizontal, `y` vertical, `t` top, `b` bottom, `s` start, `e` end

```html
<!-- Add 1.5rem padding to the bottom -->
<div class="sp-u-pb-24"></div>

<!-- Add 32px padding to both top and bottom -->
<div class="sp-u-py-32"></div>

<!-- Add 8px margin on both sides (inline) -->
<div class="sp-u-mx-08"></div>
```

### Components
- Format: `.sp-c-[value]`
- Values: `00`, `01`, `02`, `04`, `06`, `08`, `12`, `16`, `20`, `24`, `32`, `40`, `48`, `56`, `64`, `72`, `80`, `96`, `112`, `120`, `128`, `160` 

```html
<!-- Render a block with height 2rem -->
<div class="sp-c-32"></div>

<!-- Render a block with height 128px -->
<div class="sp-c-128"></div>
```
