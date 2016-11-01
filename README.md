# css-column-gap 1.0.6

Css module of single purpose classes for column gap

#### Stats

262 | 20 | 60
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-gap
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-column-gap
```

ssh:
```
git clone git@github.com:tachyons-css/css-column-gap.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-gap";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-column-gap@1.0.6/css/css-column-gap.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-gap">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COLUMN GAP
*/
.cg-1 { -webkit-column-gap: 1rem; -moz-column-gap: 1rem; column-gap: 1rem; }
.cg-2 { -webkit-column-gap: 2rem; -moz-column-gap: 2rem; column-gap: 2rem; }
.cg-3 { -webkit-column-gap: 4rem; -moz-column-gap: 4rem; column-gap: 4rem; }
.cg-n { -webkit-column-gap: normal; -moz-column-gap: normal; column-gap: normal; }
.cg-i { -webkit-column-gap: inherit; -moz-column-gap: inherit; column-gap: inherit; }
@media screen and (min-width: 48em) {
 .cg-1-ns { -webkit-column-gap: 1rem; -moz-column-gap: 1rem; column-gap: 1rem; }
 .cg-2-ns { -webkit-column-gap: 2rem; -moz-column-gap: 2rem; column-gap: 2rem; }
 .cg-3-ns { -webkit-column-gap: 4rem; -moz-column-gap: 4rem; column-gap: 4rem; }
 .cg-n-ns { -webkit-column-gap: normal; -moz-column-gap: normal; column-gap: normal; }
 .cg-i-ns { -webkit-column-gap: inherit; -moz-column-gap: inherit; column-gap: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cg-1-m { -webkit-column-gap: 1rem; -moz-column-gap: 1rem; column-gap: 1rem; }
 .cg-2-m { -webkit-column-gap: 2rem; -moz-column-gap: 2rem; column-gap: 2rem; }
 .cg-3-m { -webkit-column-gap: 4rem; -moz-column-gap: 4rem; column-gap: 4rem; }
 .cg-n-m { -webkit-column-gap: normal; -moz-column-gap: normal; column-gap: normal; }
 .cg-i-m { -webkit-column-gap: inherit; -moz-column-gap: inherit; column-gap: inherit; }
}
@media screen and (min-width: 64em) {
 .cg-1-l { -webkit-column-gap: 1rem; -moz-column-gap: 1rem; column-gap: 1rem; }
 .cg-2-l { -webkit-column-gap: 2rem; -moz-column-gap: 2rem; column-gap: 2rem; }
 .cg-3-l { -webkit-column-gap: 4rem; -moz-column-gap: 4rem; column-gap: 4rem; }
 .cg-n-l { -webkit-column-gap: normal; -moz-column-gap: normal; column-gap: normal; }
 .cg-i-l { -webkit-column-gap: inherit; -moz-column-gap: inherit; column-gap: inherit; }
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

ISC

