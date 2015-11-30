color-sass
=========

A collection of Sass color functions and color variables.

# Functions
## layer($above, $below)
This function outputs the resulting visible color from two colors as if they were layered on top of each other in Photoshop or in-browser. This function differs from `mix()` because the resulting color is not an average of both colors.

## tint($above, $below, $alpha: 0)
This function is a shortcut that uses `layer()` and strips away any alpha from `$above`, but has the option to redefine it with the `$alpha` argument.

# Todo
+ Ability to pass a list of colors to `layer()`.
