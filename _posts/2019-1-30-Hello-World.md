---
layout: post
title: Hello World!
---

This post is just to test Rust syntax highlighting in Solarized Dark theme.
Here is a valid syntax in Rust.

```rust
let lambda = || || || "Hello, World!";
```

Let's try with main() function.

```rust
fn main() {
    println!(
        "{}",
        (|| || || || || || ||  "Hello, World!")()()()()()()()
    );
}
```
