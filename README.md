# @mikker/chk

A `.chk` checkbox class for use with [Tachyons](http://tachyons.io).

## Usage

Put this in your html **before** you include Tachyons.

```html
<link rel='stylesheet' href='https://unpkg.com/@mikker/chk@latest/css/chk.css' />
```

Or add it directly to your project:

```sh
npm install @mikker/chk
# or
yarn add @mikker/chk
```

Then using postcss or however you'd like

```css
@import '~tachyons';

@import '~chk;
/* or if you want to customize variables */
@import '~chk/src/chk;
```

**NB: Be sure to include `chk.css` _before_ `tachyons.css.**

## License

MIT
