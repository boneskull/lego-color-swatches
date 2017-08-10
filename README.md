# lego-color-swatches

> All LEGO colors in various formats

## Formats

- `.ase` - Adobe Swatch Exchange
- `.clr` - Apple Color List
- `.csv` - Comma-Separated Volume
- `.json` - JavaScript Object Notation

## Subsets

- All LEGO colors, past & present
- *TODO*: Transparent, historical, and present color sets

## JavaScript / Node.js Usage

You can install this module via [npm](https://npmjs.com):

```shell
$ npm i lego-color-swatches
```

Then:

```js
const {colors} = require('lego-color-swatches');

colors.forEach(color => {
  console.log(color.name);
});
```

## Attribution

- Color codes from [Rebrickable](https://rebrickable.com)
- Conversions via [Sip](https://sipapp.io) and [ColorTools](https://github.com/ramonpoca/ColorTools)

## License

Licensed [CC0-1.0](http://creativecommons.org/publicdomain/zero/1.0/).

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Christopher Hiller](https://boneskull.com) has waived all copyright and related or neighboring rights to [lego-color-swatches](https://github.com/lego-color-swatches). This work is published from: United States.
