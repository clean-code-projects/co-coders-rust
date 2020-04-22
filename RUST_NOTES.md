# Rust Notes

This document contains notes about `rust` as we learn along.

## Enum

`enum` is good for finite set of enumerations.
It does not work with infinite set (a.k.a open set).

```rs
enum Message {
  Quit,
  Move { x: i32, y: i32 }, // anonymous struct
  Write(String),
  ChangeColor(i32, i32, i32)
}
```

## Test Organization

Test util code (code shared by test) can be placed under sub-folder of `tests`. e.g. `tests/common/mod.rs`.
The sub-folder name doesn't matter.

- <https://doc.rust-lang.org/book/ch11-03-test-organization.html>

## Cross Compile

- <https://github.com/japaric/rust-cross>
- <https://github.com/rust-embedded/cross>

## Private Registry

- <https://crates.io/crates/caesium>
- <https://github.com/Hirevo/alexandrie>

## References

- <https://doc.rust-lang.org/std/index.html>
- <https://doc.rust-lang.org/book/title-page.html>
- <https://doc.rust-lang.org/cargo/index.html>
