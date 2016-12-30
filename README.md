### SCSS Color Function

##### Description

A SCSS Function which makes a color lighter or darker depending on the weight. E.g. `color(primary, 700)`,
`color(text, 300)` whereby the default weight is `500`.

 Function accepts 2 parameters `color-name` and `weight`.

##### Organize your colors across your application

Set your color in the `$colors` map.

Avoid variables like `$color-primary-light`, `$color-primary-lighter` and `$color-primary-lightest`.

Instead define `primary` in the map and use color-weights: `color(primary, 400)`, `color(primary, 300)` and `color(primary, 100)`.

##### Usage

Simply use the files in `application/styles/color` and replace the color variables with your own.

```scss
button {
  color: color(primary, 50);

  // this is the same as color(primary, 500)
  background: color(primary);
  border: 1px solid color(primary, 700);
}
```
