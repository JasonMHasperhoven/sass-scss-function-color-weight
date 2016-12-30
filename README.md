### SCSS Color Function

##### Description

A SCSS Function which returns the color with the given weight. Make a color lighter or darker depending on the weight. Function accepts 2 parameters `color-name` and `weight`,
whereby the default weight is `500`.

##### Philosphy

This is designed to avoid variables like `$color-primary-light`, `$color-primary-lighter` and `$color-primary-lightest`. Instead you can write `color(primary, 400)`, `color(primary, 300)` and `color(primary, 100)`. Inspiration comes from the attribute font-weight.

##### Usage

Simply use the files in `application/styles/color` and replace the color variables with your own.
