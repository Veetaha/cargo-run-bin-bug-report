# Bug report

[Issue link](https://github.com/rust-lang/cargo/issues/8457)

Reporoduction:
```bash

# Compile error:
cargo build --bin the_bin

# Successful compilation:
cargo build --package bin_crate
cargo build --package bin_crate --bin the_bin
```
