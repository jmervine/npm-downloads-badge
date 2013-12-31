npm-downloads-badge
===================

npmjs.org badge displaying total downloads of a module

usage
-----

With module name:

``` html
<iframe
    src="http://jmervine.github.io/npm-downloads-badge/badge.html?module=MODULE"
    allowtransparency="true" frameborder="0" scrolling="0" width="100" height="20">
</iframe>
```

Without module name:

``` html
<iframe
    src="http://jmervine.github.io/npm-downloads-badge/badge.html?module=MODULE&name=false"
    allowtransparency="true" frameborder="0" scrolling="0" width="100" height="20">
</iframe>
```

> Note: The width attribute may need to be adjusted for count and title. The count will not display correctly if width is too low.
>
> See the [test.html](https://github.com/jmervine/npm-downloads-badge/blob/master/test.html) file for exampels.

credits
-------

* Idea and API call from: https://github.com/bcluca
* Basic implementation and style from: https://github.com/mdo/github-buttons
