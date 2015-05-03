Custom Grid
===================

Documents
-------------

**Inatall**

<a href="http://bower.io/search/?q=grid-custom"><img src="https://benschwarz.github.io/bower-badges/badge@2x.png" width="130" height="30"></a>
```
bower install grid-custom
```

**How to use it**

``` scss
  /* application.scss */

  @import 'grid-custom'

  @include grid(5, 5);
```
``` html
<!-- index.html -->
<div class='u-grid-container'>
   <div class='u-grid-r0-c0'>
     (Row 0 , Colum 0)
   </div>
   <div class='u-grid-r1-c1'>
     (Row 1 , Colum 1)
   </div>
   <div class='u-grid-r2-c0'>
     (Row 2 , Colum 0)
   </div>
</div>
```

**Sass Config**

``` scss
// Defaults values

$size-height: 100px;
$size-width: 100px;
```

## <a href="http://codepen.io/imNicoSuarez/pen/qddgeR"> Demo </a>

## License

The MIT License (MIT)

Copyright (c) 2015 Nicolas Suarez

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.