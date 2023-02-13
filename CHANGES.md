# Unreleased

## Changed
- Windows: 'mouse_scroll_y' with a positive number scrolls down just like on the other platforms
- Windows: replaced 'winapi' with the official 'windows' crate
- Rust: Using Rust version 2021
- Rust: Minimum supported Rust version (MSRV) is set in Cargo.toml
- Rust: MSRV is 1.64


## Added
- DSL: Additional ParseError variants to give better feedback what the problem was
- DSL: Additional keys
- All: Added support for F10-F20
- CI/CD: Github Workflows to make sure the code builds and the tests pass

## Fixed
- Windows: panicked at 'cannot transmute_copy if U is larger than T' (https://github.com/enigo-rs/enigo/issues/121)