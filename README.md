[![Build Status](https://travis-ci.com/jaredforth/webp.svg?token=mH2pScYxqRkBEzpBQAu6&branch=master)](https://travis-ci.com/jaredforth/webp)
[![Build status](https://ci.appveyor.com/api/projects/status/w75cp0q4qr0hngf8?svg=true)](https://ci.appveyor.com/project/jaredforth/webp)
[![Crate](https://img.shields.io/crates/v/webp.svg)](https://crates.io/crates/webp)
[![API](https://docs.rs/webp/badge.svg)](https://docs.rs/webp)
![Crates.io](https://img.shields.io/crates/d/webp)

# webp

A WebP conversion library. WIP;

Documentation:
-   [API Reference](https://docs.rs/webp)


## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies]
webp = "0.2"
```

## Examples

An example for converting an image between JPEG and WebP formats is provided in the 
`examples` directory. It can be run using 
```sh
$ cargo run --release --example convert
```

## License

**webp** is distributed under the terms of both the MIT license and the
Apache License (Version 2.0).

See [LICENSE-APACHE](LICENSE-APACHE) and [LICENSE-MIT](LICENSE-MIT), and
[COPYRIGHT](COPYRIGHT) for details.

The photo `lake.jpg` included in the `assets/` directory is licensed under 
[CC0](https://creativecommons.org/publicdomain/zero/1.0/)/"Public Domain Dedication". 
