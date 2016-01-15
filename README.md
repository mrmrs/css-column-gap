# css-column-gap 0.0.7

Css module of single purpose classes for column gap

#### Stats

214 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-gap
```

#### With Git

```
git clone https://github.com/tachyons-css/css-column-gap
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-gap";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-gap">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   COLUMN GAP
*/
.cg-1 { column-gap: 1rem; }
.cg-2 { column-gap: 2rem; }
.cg-3 { column-gap: 4rem; }
.cg-n { column-gap: normal; }
.cg-i { column-gap: inherit; }
@media screen and (min-width: 48em) {
 .cg-1-ns { column-gap: 1rem; }
 .cg-2-ns { column-gap: 2rem; }
 .cg-3-ns { column-gap: 4rem; }
 .cg-n-ns { column-gap: normal; }
 .cg-i-ns { column-gap: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cg-1-m { column-gap: 1rem; }
 .cg-2-m { column-gap: 2rem; }
 .cg-3-m { column-gap: 4rem; }
 .cg-n-m { column-gap: normal; }
 .cg-i-m { column-gap: inherit; }
}
@media screen and (min-width: 64em) {
 .cg-1-l { column-gap: 1rem; }
 .cg-2-l { column-gap: 2rem; }
 .cg-3-l { column-gap: 4rem; }
 .cg-n-l { column-gap: normal; }
 .cg-i-l { column-gap: inherit; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

