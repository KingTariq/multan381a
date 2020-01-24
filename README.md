# First Welcome
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`multan381a = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "multan381a"
version = "0.1.0"
authors = ["KingTariq<tariqmasood2k2@yahoo.com>"]
edition = "2018"

[dependencies]
multan381a = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use multan381a;
fn main() {
    println!("Hello, world!");
    multan381a::city();
}
```
following will also work:
```
use mulatn381a::city;
fn main() {
    println!("Hello, world!");
    city();
    }
```

now `cargo run` for results
