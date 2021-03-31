# rust-getting-started

## Installing

For more details, see https://www.rust-lang.org/tools/install

### Windows



### Unix

`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`


## Development Tools

### Setup VS Code

See the [Visual Studio Code](https://code.visualstudio.com/) web site to get started using VS Code

### VS Code Extensions for Rust

The following extensions are useful in VS Code for developing with Rust

- [Rust](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust)

## Rust Tools

- rustc - The rust compiler. `rustc --version`
- rustup - The main Rust toolchain tool. `rustup --version`

## Rustup

`rustup toolchain list` - Installed targets
`rustup target list` - Possible targets
`rustup target add wasm32-unknown-unknown` - Install the WebAssembly target

## Cargo

`cargo new --lib project1` - Create a library called "project1"
`cargo​​ ​​build​​ ​​--target​​ ​​wasm32-unknown-unknown` - Build debug project
`cargo​​ ​​build​​ ​​--release​​ ​​--target=wasm32-unknown-unknown` - Build release project

## Web Frameworks

Yew
Actix

## Resources

### Videos

[Rust Crash Course](https://www.youtube.com/watch?v=zF34dRivLOw)

### Reading material

[The Rust Programming Language](https://doc.rust-lang.org/book/)
[Programming WebAssembly with Rust](https://www.oreilly.com/library/view/programming-webassembly-with/9781680506846/)
[Rust and WebAssembly](https://rustwasm.github.io/docs/book/introduction.html)
