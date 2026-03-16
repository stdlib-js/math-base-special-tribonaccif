# CHANGELOG

> Package changelog.

<section class="release" id="v0.1.1">

## 0.1.1 (2026-02-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2026-01-29)

<section class="features">

### Features

-   [`6724610`](https://github.com/stdlib-js/stdlib/commit/672461019c6893cfddc9227d407ebab4e04f4c40) - add `math/base/special/tribonaccif` [(#6066)](https://github.com/stdlib-js/stdlib/pull/6066)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`dc3487c`](https://github.com/stdlib-js/stdlib/commit/dc3487cf4d8063b22fc6311ac4492579c815911e): update signature to accept floats

    -   User code should behave similarly in the primary case of providing integer-valued input values. However, no longer will real-values truncate. Now, real-valued inputs will result in `NaN`, which is, arguably, better behavior, as real-to-integer truncation can be a source of silent bugs.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`4126672`](https://github.com/stdlib-js/stdlib/commit/41266720aa68fb932272101857bac854d7fde9d0) - **chore:** add structured package data for `math/base/special/tribonaccif` [(#8284)](https://github.com/stdlib-js/stdlib/pull/8284) _(by Manvith M, Athan Reines)_
-   [`dc3487c`](https://github.com/stdlib-js/stdlib/commit/dc3487cf4d8063b22fc6311ac4492579c815911e) - **refactor:** modify C implementation to accept `float` instead of `int32` in `math/base/special/tribonaccif` [(#8032)](https://github.com/stdlib-js/stdlib/pull/8032) _(by Gunj Joshi, Athan Reines)_
-   [`6724610`](https://github.com/stdlib-js/stdlib/commit/672461019c6893cfddc9227d407ebab4e04f4c40) - **feat:** add `math/base/special/tribonaccif` [(#6066)](https://github.com/stdlib-js/stdlib/pull/6066) _(by Neeraj Pathak, Athan Reines, stdlib-bot, Karan Anand)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 5 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gunj Joshi
-   Karan Anand
-   Manvith M
-   Neeraj Pathak

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

