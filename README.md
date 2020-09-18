# usd-rs

The very start of some rust bindings for [USD](https://github.com/PixarAnimationStudios/USD).

- usd-cpp is a crate to build the cpp shared library and its dependencies (tbb, boost ..).
- usd-rs is the actual bindings crate.
- usd-examples will be examples.

# Building
- git clone git@github.com:luke-titley/usd-rs.git && cd usd-rs
- git submodule update --init --recursive
- cargo build