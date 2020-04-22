# co-coders

This repository contains Rust implementation of `co-coders`.

## File Organization

This repository uses `cargo` workspaces to maintain multiple libraries/applications.
It is the same idea as monorepo in `yarn` for example.

Each library contains their own `Cargo.toml`,
`src` for source code,
and `tests` for integration tests.

In `rust`/`cargo`, unit test are written directly within the source file.

## Contribute

### Build

```sh
# build library and executable
cargo build

# build + run
cargo run

# compile but don't build
cargo check
```

### Test

```sh
# run all tests: unit, integration, doc
cargo test

# run specific integration test file
# (assume `tests/specific_test.rs` is the test file)
cargo test --test specific_test
```

## Development Environment

We will primarily be using VS Code.

Here are some recommended extensions in VSCode used when working on this project:

- Rust Extension Pack
- vscode-rust-syntax
- EditorConfig for VS Code
- markdownlint
