# CSS TEXT DECORATION

  Mobile-first classes for css-text-decoration.
  Set the desired css-text-decoration on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-text-decoration
```
View on [npm](https://www.npmjs.org/package/css-text-decoration)


## File Size

1.0K text-decoration.css
797B text-decoration.min.css
204B minified and gzipped

## The Code
```
.under  { text-decoration: underline; }
.over   { text-decoration: overline; }
.strike { text-decoration: line-through; }
.blink  { text-decoration: blink; }
.none   { text-decoration: none; }


@media screen and (min-width: 48em) {
  .under-ns  { text-decoration: underline; }
  .over-ns   { text-decoration: overline; }
  .strike-ns { text-decoration: line-through; }
  .blink-ns  { text-decoration: blink; }
  .none-ns   { text-decoration: none; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .under-m  { text-decoration: underline; }
  .over-m   { text-decoration: overline; }
  .strike-m { text-decoration: line-through; }
  .blink-m  { text-decoration: blink; }
  .none-m   { text-decoration: none; }
}

@media screen and (min-width: 64em)  {
  .under-l  { text-decoration: underline; }
  .over-l   { text-decoration: overline; }
  .strike-l { text-decoration: line-through; }
  .blink-l  { text-decoration: blink; }
  .none-l   { text-decoration: none; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

