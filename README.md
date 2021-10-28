# TIMSAC: Time Series Analysis and Control Package

[![BSD-3](https://img.shields.io/github/license/zoziha/timsac?color=pink)](LICENSE)
[![fpm](https://github.com/zoziha/timsac/workflows/fpm/badge.svg)](https://github.com/zoziha/timsac/actions)
[![mdbook](https://github.com/zoziha/timsac/workflows/mdbook/badge.svg)](https://github.com/zoziha/timsac/actions)

Functions for statistical analysis, prediction and control of time series based mainly on Akaike and Nakagawa (1988) <ISBN 978-90-277-2786-2>.

|Terms|Description|
|:-:|:-:|
|Version:|1.3.6|
|Author:|The Institute of Statistical Mathematics|
|API-Doc:|https://zoziha.github.io/timsac/|
|License:|GPL(>=2)|

## Get Started

### Dependencies

- Git
- [fortran-lang/fpm](https://github.com/fortran-lang/fpm)
- [Rust](https://www.rust-lang.org/zh-CN/)
- [mdbook](https://github.com/rust-lang/mdBook)

### Get the code

```sh
git clone https://github.com/zoziha/timsac.git
cd timsac
```

### Build with [fortran-lang/fpm](https://github.com/fortran-lang/fpm)

Fortran Package Manager (fpm) is a package manager and build system for Fortran. <br>
You can build `timsac` using provided `fpm.toml`:

```sh
fpm build
```

To use `timsac` within your `fpm` project, add the following lines to your `fpm.toml` file:

```toml
[dependencies]
timsac = { git="https://github.com/zoziha/timsac.git" }
```

### Build API-Doc with [mdbook](https://github.com/rust-lang/mdBook)

mdBook is a utility to create modern online books from Markdown files.<br>
You can build `timsac` API-Doc using provided `book.toml`

```sh
cd doc && mdbook build
```

## Links

- [cran/timsac](https://github.com/cran/timsac)