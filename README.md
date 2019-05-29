# grid-bootstrap
Responsive grid classes for Bootstrap 4. Extends Bootstrap 4 with display: grid utilities.
Uses Bootstrap 4 variables and mixins. It will pick up Bootstrap's or your override varaibles such as $grid-breakpoints. To generate responsive grid utilities.

## install

``` bash
npm i grid-bootstrap
```

## How to use

### For compiling
Include the entry point grid-bootstrap.scss into your scss file.
Replace {relative/path} with the path of your setup
```scss
@import '{relative/path}node_modules/bootstrap/scss/functions';
@import '{relative/path}/node_modules/bootstrap/scss/variables';
@import '{relative/path}/node_modules/bootstrap/scss/mixins';
@import '{relative/path}/node_modules/grid-bootstrap/scss/variables';
@import '{relative/path}/node_modules/bootstrap/scss/grid/grid';
```

Or, if you already imported bootstrap sources just import grid bootstrap files
```scss
@import '{relative/path}/node_modules/grid-bootstrap/scss/variables';
@import '{relative/path}/node_modules/bootstrap/scss/grid/grid';
```

Now you can compile your scss.

### For using compiled

TBD

## Generated css classes

### General class

```html
.d-grid
```

### Grid col start/end

```html
.grid-col-start-#
.grid-col-sm-start-#
.grid-col-md-start-#
...etc
```

```html
.grid-col-end-#
.grid-col-sm-end-#
.grid-col-md-end-#
...etc
```

### Grid row start/end

```html
.grid-row-start-#
.grid-row-sm-start-#
.grid-row-md-start-#
...etc
```

```html
.grid-row-end-#
.grid-row-sm-end-#
.grid-row-md-end-#
...etc
```