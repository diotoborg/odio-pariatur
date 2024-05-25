<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

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

# Regular Expressions

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Regular expressions.

<section class="installation">

## Installation

```bash
npm install @diotoborg/odio-pariatur
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var regexp = require( '@diotoborg/odio-pariatur' );
```

#### regexp

Namespace containing regular expressions.

```javascript
var re = regexp;
// returns {...}
```

The following regular expressions are currently exported:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`reBasenamePosix()`][@diotoborg/odio-pariatur/basename-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a POSIX path.</span>
-   <span class="signature">[`reBasenameWindows()`][@diotoborg/odio-pariatur/basename-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a Windows path.</span>
-   <span class="signature">[`reBasename( [platform] )`][@diotoborg/odio-pariatur/basename]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a path.</span>
-   <span class="signature">[`reColorHexadecimal( [mode] )`][@diotoborg/odio-pariatur/color-hexadecimal]</span><span class="delimiter">: </span><span class="description">regular expression to match a hexadecimal color.</span>
-   <span class="signature">[`reDecimalNumber( [options] )`][@diotoborg/odio-pariatur/decimal-number]</span><span class="delimiter">: </span><span class="description">regular expression to match a decimal number.</span>
-   <span class="signature">[`reDirnamePosix()`][@diotoborg/odio-pariatur/dirname-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture a POSIX path dirname.</span>
-   <span class="signature">[`reDirnameWindows()`][@diotoborg/odio-pariatur/dirname-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture a Windows path dirname.</span>
-   <span class="signature">[`reDirname( [platform] )`][@diotoborg/odio-pariatur/dirname]</span><span class="delimiter">: </span><span class="description">regular expression to capture a path dirname.</span>
-   <span class="signature">[`reDurationString()`][@diotoborg/odio-pariatur/duration-string]</span><span class="delimiter">: </span><span class="description">regular expression to match a duration string.</span>
-   <span class="signature">[`reEOL( [options] )`][@diotoborg/odio-pariatur/eol]</span><span class="delimiter">: </span><span class="description">regular expression to match a newline character sequence.</span>
-   <span class="signature">[`reExtendedLengthPath()`][@diotoborg/odio-pariatur/extended-length-path]</span><span class="delimiter">: </span><span class="description">regular expression to detect an extended-length path.</span>
-   <span class="signature">[`reExtnamePosix()`][@diotoborg/odio-pariatur/extname-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture a POSIX filename extension.</span>
-   <span class="signature">[`reExtnameWindows()`][@diotoborg/odio-pariatur/extname-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture a Windows filename extension.</span>
-   <span class="signature">[`reExtname( [platform] )`][@diotoborg/odio-pariatur/extname]</span><span class="delimiter">: </span><span class="description">regular expression to capture a filename extension.</span>
-   <span class="signature">[`reFilenamePosix()`][@diotoborg/odio-pariatur/filename-posix]</span><span class="delimiter">: </span><span class="description">regular expression to split a POSIX filename.</span>
-   <span class="signature">[`reFilenameWindows()`][@diotoborg/odio-pariatur/filename-windows]</span><span class="delimiter">: </span><span class="description">regular expression to split a Windows filename.</span>
-   <span class="signature">[`reFilename( [platform] )`][@diotoborg/odio-pariatur/filename]</span><span class="delimiter">: </span><span class="description">regular expression to split a filename.</span>
-   <span class="signature">[`reFunctionName()`][@diotoborg/odio-pariatur/function-name]</span><span class="delimiter">: </span><span class="description">regular expression to capture a function name.</span>
-   <span class="signature">[`reNativeFunction()`][@diotoborg/odio-pariatur/native-function]</span><span class="delimiter">: </span><span class="description">regular expression to match a native function.</span>
-   <span class="signature">[`reRegExp()`][@diotoborg/odio-pariatur/regexp]</span><span class="delimiter">: </span><span class="description">regular expression to parse a regular expression string.</span>
-   <span class="signature">[`reviveRegExp( key, value )`][@diotoborg/odio-pariatur/reviver]</span><span class="delimiter">: </span><span class="description">revive a JSON-serialized regular expression.</span>
-   <span class="signature">[`reSemVer()`][@diotoborg/odio-pariatur/semver]</span><span class="delimiter">: </span><span class="description">regular expression to match a semantic version string.</span>
-   <span class="signature">[`regexp2json( regexp )`][@diotoborg/odio-pariatur/to-json]</span><span class="delimiter">: </span><span class="description">return a JSON representation of a regular expression.</span>
-   <span class="signature">[`reUncPath()`][@diotoborg/odio-pariatur/unc-path]</span><span class="delimiter">: </span><span class="description">regular expression to parse a UNC path.</span>
-   <span class="signature">[`reUtf16SurrogatePair()`][@diotoborg/odio-pariatur/utf16-surrogate-pair]</span><span class="delimiter">: </span><span class="description">regular expression to match a UTF-16 surrogate pair.</span>
-   <span class="signature">[`reUtf16UnpairedSurrogate()`][@diotoborg/odio-pariatur/utf16-unpaired-surrogate]</span><span class="delimiter">: </span><span class="description">regular expression to match an unpaired UTF-16 surrogate.</span>
-   <span class="signature">[`reWhitespace( [options] )`][@diotoborg/odio-pariatur/whitespace]</span><span class="delimiter">: </span><span class="description">regular expression to match a white space character.</span>

</div>

<!-- </toc> -->

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var regexp = require( '@diotoborg/odio-pariatur' );

console.log( objectKeys( regexp ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@diotoborg/odio-pariatur.svg
[npm-url]: https://npmjs.org/package/@diotoborg/odio-pariatur

[test-image]: https://github.com/diotoborg/odio-pariatur/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/diotoborg/odio-pariatur/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/diotoborg/odio-pariatur/main.svg
[coverage-url]: https://codecov.io/github/diotoborg/odio-pariatur?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/diotoborg/odio-pariatur.svg
[dependencies-url]: https://david-dm.org/diotoborg/odio-pariatur/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/diotoborg/odio-pariatur/tree/deno
[deno-readme]: https://github.com/diotoborg/odio-pariatur/blob/deno/README.md
[umd-url]: https://github.com/diotoborg/odio-pariatur/tree/umd
[umd-readme]: https://github.com/diotoborg/odio-pariatur/blob/umd/README.md
[esm-url]: https://github.com/diotoborg/odio-pariatur/tree/esm
[esm-readme]: https://github.com/diotoborg/odio-pariatur/blob/esm/README.md
[branches-url]: https://github.com/diotoborg/odio-pariatur/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/diotoborg/odio-pariatur/main/LICENSE

<!-- <toc-links> -->

[@diotoborg/odio-pariatur/basename-posix]: https://github.com/diotoborg/odio-pariatur/tree/main/basename-posix

[@diotoborg/odio-pariatur/basename-windows]: https://github.com/diotoborg/odio-pariatur/tree/main/basename-windows

[@diotoborg/odio-pariatur/basename]: https://github.com/diotoborg/odio-pariatur/tree/main/basename

[@diotoborg/odio-pariatur/color-hexadecimal]: https://github.com/diotoborg/odio-pariatur/tree/main/color-hexadecimal

[@diotoborg/odio-pariatur/decimal-number]: https://github.com/diotoborg/odio-pariatur/tree/main/decimal-number

[@diotoborg/odio-pariatur/dirname-posix]: https://github.com/diotoborg/odio-pariatur/tree/main/dirname-posix

[@diotoborg/odio-pariatur/dirname-windows]: https://github.com/diotoborg/odio-pariatur/tree/main/dirname-windows

[@diotoborg/odio-pariatur/dirname]: https://github.com/diotoborg/odio-pariatur/tree/main/dirname

[@diotoborg/odio-pariatur/duration-string]: https://github.com/diotoborg/odio-pariatur/tree/main/duration-string

[@diotoborg/odio-pariatur/eol]: https://github.com/diotoborg/odio-pariatur/tree/main/eol

[@diotoborg/odio-pariatur/extended-length-path]: https://github.com/diotoborg/odio-pariatur/tree/main/extended-length-path

[@diotoborg/odio-pariatur/extname-posix]: https://github.com/diotoborg/odio-pariatur/tree/main/extname-posix

[@diotoborg/odio-pariatur/extname-windows]: https://github.com/diotoborg/odio-pariatur/tree/main/extname-windows

[@diotoborg/odio-pariatur/extname]: https://github.com/diotoborg/odio-pariatur/tree/main/extname

[@diotoborg/odio-pariatur/filename-posix]: https://github.com/diotoborg/odio-pariatur/tree/main/filename-posix

[@diotoborg/odio-pariatur/filename-windows]: https://github.com/diotoborg/odio-pariatur/tree/main/filename-windows

[@diotoborg/odio-pariatur/filename]: https://github.com/diotoborg/odio-pariatur/tree/main/filename

[@diotoborg/odio-pariatur/function-name]: https://github.com/diotoborg/odio-pariatur/tree/main/function-name

[@diotoborg/odio-pariatur/native-function]: https://github.com/diotoborg/odio-pariatur/tree/main/native-function

[@diotoborg/odio-pariatur/regexp]: https://github.com/diotoborg/odio-pariatur/tree/main/regexp

[@diotoborg/odio-pariatur/reviver]: https://github.com/diotoborg/odio-pariatur/tree/main/reviver

[@diotoborg/odio-pariatur/semver]: https://github.com/diotoborg/odio-pariatur/tree/main/semver

[@diotoborg/odio-pariatur/to-json]: https://github.com/diotoborg/odio-pariatur/tree/main/to-json

[@diotoborg/odio-pariatur/unc-path]: https://github.com/diotoborg/odio-pariatur/tree/main/unc-path

[@diotoborg/odio-pariatur/utf16-surrogate-pair]: https://github.com/diotoborg/odio-pariatur/tree/main/utf16-surrogate-pair

[@diotoborg/odio-pariatur/utf16-unpaired-surrogate]: https://github.com/diotoborg/odio-pariatur/tree/main/utf16-unpaired-surrogate

[@diotoborg/odio-pariatur/whitespace]: https://github.com/diotoborg/odio-pariatur/tree/main/whitespace

<!-- </toc-links> -->

</section>

<!-- /.links -->
