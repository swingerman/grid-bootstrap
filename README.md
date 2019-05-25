# grid-bootstrap
Responsive grid classes for Bootstrap 4. Extends Bootstrap 4 with display: grid utilities.
Uses Bootstrap 4 variables and mixins. It will pick up Bootstrap's or your override varaibles such as $grid-breakpoints. To generate respinsive grid utilities.

## install
`npm i grid-bootstrap`

## How to use

### For compiling
Include the entry point grid-bootstrap.scss into your scss file.
Replace {relative/path} with the path of your setup
```
@import '{relative/path}node_modules/bootstrap/scss/functions';
@import '{relative/path}/node_modules/bootstrap/scss/variables';
@import '{relative/path}/node_modules/bootstrap/scss/mixins';
@import '{relative/path}/node_modules/grid-bootstrap/scss/variables';
@import '{relative/path}/node_modules/bootstrap/scss/grid/grid';
```

Or, if you already imported bootstrap sources just import grid bootstrap files
```
@import '{relative/path}/node_modules/grid-bootstrap/scss/variables';
@import '{relative/path}/node_modules/bootstrap/scss/grid/grid';
```

### For using compiled
``

Now you can compile your scss.

## Generated css classes:

.d-grid

.grid-col-start-#
.grid-col-sm-start-#
.grid-col-md-start-#
...etc

.grid-col-end-#
.grid-col-sm-end-#
.grid-col-md-end-#
...etc
