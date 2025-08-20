<!--

@license Apache-2.0

Copyright (c) 2023 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# fliplr2d

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Reverse the order of elements along the last dimension of a two-dimensional nested input array.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->



<section class="usage">

## Usage

```javascript
import fliplr2d from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-base-fliplr2d@deno/mod.js';
```

#### fliplr2d( x )

Reverses the order of elements along the last dimension of a two-dimensional nested input array.

```javascript
var out = fliplr2d( [ [ 1, 2 ], [ 3, 4 ] ] );
// returns [ [ 2, 1 ], [ 4, 3 ] ]
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var discreteUniform = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/random-base-discrete-uniform' ).factory;
import filled2dBy from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-base-filled2d-by@deno/mod.js';
import fliplr2d from 'https://cdn.jsdelivr.net/gh/stdlib-js/array-base-fliplr2d@deno/mod.js';

var x = filled2dBy( [ 3, 3 ], discreteUniform( -50, 50 ) );
console.log( x );

var y = fliplr2d( x );
console.log( y );
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/array-base/fliplr3d`][@stdlib/array/base/fliplr3d]</span><span class="delimiter">: </span><span class="description">reverse the order of elements along the last dimension of a three-dimensional nested input array.</span>
-   <span class="package-name">[`@stdlib/array-base/fliplr4d`][@stdlib/array/base/fliplr4d]</span><span class="delimiter">: </span><span class="description">reverse the order of elements along the last dimension of a four-dimensional nested input array.</span>
-   <span class="package-name">[`@stdlib/array-base/fliplr5d`][@stdlib/array/base/fliplr5d]</span><span class="delimiter">: </span><span class="description">reverse the order of elements along the last dimension of a five-dimensional nested input array.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2025. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/array-base-fliplr2d.svg
[npm-url]: https://npmjs.org/package/@stdlib/array-base-fliplr2d

[test-image]: https://github.com/stdlib-js/array-base-fliplr2d/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/stdlib-js/array-base-fliplr2d/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/array-base-fliplr2d/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/array-base-fliplr2d?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/array-base-fliplr2d.svg
[dependencies-url]: https://david-dm.org/stdlib-js/array-base-fliplr2d/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/array-base-fliplr2d/tree/deno
[deno-readme]: https://github.com/stdlib-js/array-base-fliplr2d/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/array-base-fliplr2d/tree/umd
[umd-readme]: https://github.com/stdlib-js/array-base-fliplr2d/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/array-base-fliplr2d/tree/esm
[esm-readme]: https://github.com/stdlib-js/array-base-fliplr2d/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/array-base-fliplr2d/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/array-base-fliplr2d/main/LICENSE

<!-- <related-links> -->

[@stdlib/array/base/fliplr3d]: https://github.com/stdlib-js/array-base-fliplr3d/tree/deno

[@stdlib/array/base/fliplr4d]: https://github.com/stdlib-js/array-base-fliplr4d/tree/deno

[@stdlib/array/base/fliplr5d]: https://github.com/stdlib-js/array-base-fliplr5d/tree/deno

<!-- </related-links> -->

</section>

<!-- /.links -->
