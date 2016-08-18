# css-text-decoration 0.0.6

Css module of single purpose classes for text decoration

#### Stats

246 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-text-decoration
```

#### With Git

```
git clone https://github.com/tachyons-css/css-text-decoration
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-text-decoration";
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
<link rel="stylesheet" href="path/to/module/css/css-text-decoration">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TEXT DECORATION
*/
.under { text-decoration: underline; }
.over { text-decoration: overline; }
.strike { text-decoration: line-through; }
.blink { text-decoration: blink; }
.none { text-decoration: none; }
@media screen and (min-width: 48em) {
 .under-ns { text-decoration: underline; }
 .over-ns { text-decoration: overline; }
 .strike-ns { text-decoration: line-through; }
 .blink-ns { text-decoration: blink; }
 .none-ns { text-decoration: none; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .under-m { text-decoration: underline; }
 .over-m { text-decoration: overline; }
 .strike-m { text-decoration: line-through; }
 .blink-m { text-decoration: blink; }
 .none-m { text-decoration: none; }
}
@media screen and (min-width: 64em) {
 .under-l { text-decoration: underline; }
 .over-l { text-decoration: overline; }
 .strike-l { text-decoration: line-through; }
 .blink-l { text-decoration: blink; }
 .none-l { text-decoration: none; }
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
