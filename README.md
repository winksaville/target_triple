# Print target-triple

Based on work by Shnatsel:
  * https://stackoverflow.com/a/71872544/4812090
  * https://crates.io/crates/current_platform

Print current compiler target triple

## Run:

```
$ cargo run
   Compiling current_platform v0.2.0
   Compiling target_triple v0.2.0 (/home/wink/prgs/rust/myrepos/target_triple)
    Finished dev [unoptimized + debuginfo] target(s) in 0.43s
     Running `target/debug/target_triple`
x86_64-unknown-linux-gnu

```

## Install

```
$ cargo install --path .
  Installing target_triple v0.1.0 (/home/wink/prgs/rust/myrepos/target_triple)
    Updating crates.io index
   Compiling current_platform v0.2.0
   Compiling target_triple v0.1.0 (/home/wink/prgs/rust/myrepos/target_triple)
    Finished release [optimized] target(s) in 1.25s
  Installing /home/wink/.cargo/bin/target_triple
   Installed package `target_triple v0.1.0 (/home/wink/prgs/rust/myrepos/target_triple)` (executable `target_triple`)
```


## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or http://apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall
be dual licensed as above, without any additional terms or conditions.
