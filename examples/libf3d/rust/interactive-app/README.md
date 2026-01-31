# f3d-interactive-app, the rust version

This project reproduces the `interactive-app` example present in other languages in the f3d examples in rust. It uses `cargo` for dependency management.

## Pre-requisites

* A rust compiler such as `rustc`: The recommendation would be to use the official toolchain manager [rustup](https://rustup.rs/) to install it. `rustup` will also naturally install `cargo` for you for managing dependencies.
* [clang](https://clang.llvm.org/): needed for automatic wrapping of the C API using [bindgen](https://github.com/rust-lang/rust-bindgen)
* f3d install: similarly for other examples, f3d needs to be installed somewhere with `library` and `sdk` components. It should be built with the C api (`F3D_BINDINGS_C=ON`)

## Building and running the example

The example can be built in run in one shot from this directory with:

```shell
cargo run
```
