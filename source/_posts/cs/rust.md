# Rust Learning Notes

This document tracks my progress and details as I learn Rust.

## Getting Started

- Installed Rust using `rustup`.
- Verified installation with `rustc --version`.
- This page is followed by [Rust 圣经](https://course.rs/first-try/slowly-downloading.html) a great guide post
- I only record what I think is best

## Basic Concepts

- Variables are immutable by default. Use `mut` for mutability.
- Functions are declared with `fn`.
- Ownership, borrowing, and lifetimes are core concepts.

## Example

```rust
fn main() {
    let mut x = 5;
    println!("x = {}", x);
    x = 10;
    println!("x = {}", x);
}
```

## Next Steps

- Explore cargo for project management.
- Learn about structs and enums.
- Practice error handling.

---
*Updated as I progress through my Rust journey.*


# Package