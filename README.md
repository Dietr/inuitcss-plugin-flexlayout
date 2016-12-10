# InuitCSS plugin: flexlayout

A flexbox layout system object for the [InuitCSS](https://github.com/inuitcss/inuitcss) framework.

Works as a drop-in replacement for the default `objects.layout.scss` layout object by using the same classes and variables.

## How to use
Replace the `objects.layout.scss` reference in your screen.scss file with `objects.flexlayout.scss`. Make sure that you put the correct path if you load this with NPM.

This plugins adds an additional modifier (`.o-layout--match`) to match the height of your layout items' content. Which makes equal sized blocks easy to construct.

## Credits
- [InuitCSS](https://github.com/inuitcss/inuitcss) by [@csswizardry](https://twitter.com/csswizardry)
