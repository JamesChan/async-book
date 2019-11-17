2019-11-17: refactoring for gitdoc

building now using the following instead of change before

mdbook build ./gitdoc

IMPORTANTLY: NOW I can use gitbook editor to edit this repo in the root directory

___

# async-book
Asynchronous Programming in Rust

## Requirements
The async book is built with [`mdbook`], you can install it using cargo.

```
cargo install mdbook
```

[`mdbook`]: https://github.com/rust-lang/mdBook

## Building
To create a finished book, run `mdbook build` to generate it under the `book/` directory.
```
mdbook build
```

## Development
While writing it can be handy to see your changes, `mdbook serve` will launch a local web
server to serve the book.
```
mdbook serve
```
