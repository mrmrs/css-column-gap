# CSS COLUMN GAP

  Mobile-first classes for css-column-gap.
  Set the desired css-column-gap on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-column-gap
```
or download the css on github and include in your project.

## File Size


## The Code
```
.cg-1 { column-gap: 1rem; }
.cg-2 { column-gap: 2rem; }
.cg-3 { column-gap: 4rem; }
.cg-n { column-gap: normal; }
.cg-i { column-gap: inherit; }

@include break(not-small) {
  .cg-1-ns { column-gap: 1rem; }
  .cg-2-ns { column-gap: 2rem; }
  .cg-3-ns { column-gap: 4rem; }
  .cg-n-ns { column-gap: normal; }
  .cg-i-ns { column-gap: inherit; }
}

@include break(medium) {
  .cg-1-m { column-gap: 1rem; }
  .cg-2-m { column-gap: 2rem; }
  .cg-3-m { column-gap: 4rem; }
  .cg-n-m { column-gap: normal; }
  .cg-i-m { column-gap: inherit; }
}

@include break(large) {
  .cg-1-l { column-gap: 1rem; }
  .cg-2-l { column-gap: 2rem; }
  .cg-3-l { column-gap: 4rem; }
  .cg-n-l { column-gap: normal; }
  .cg-i-l { column-gap: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

