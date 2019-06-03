# saveplot

saveplot is an R package of utility functions for saving high quality plots to svg and png formats for publication in print and online.

## Installation

Install from GitHub using devtools.

``` r
install.packages("devtools")
devtools::install_github("olihawkins/saveplot")
```

## Saving plots

Use `save_svg` and `save_png` to save plots to each format.

---

_saveplot_::__save_svg__(_plot_, _filename_, _width_, _height_)

Save an svg with the following arguments:

* __plot__  A plot object.
* __filename__ Filename to save to an svg.
* __width__ Width of the image in inches.
* __height__ Height of the image in inches.

_saveplot_::__save_png__(_plot_, _filename_, _width_, _height_, _ppi = 400_)

Save a png with the following arguments:

* __plot__  A plot object.
* __filename__ Filename to save to a png.
* __width__ Width of the image in inches.
* __height__ Height of the image in inches.
* __width__ Number of pixels per inch for the png.

---
