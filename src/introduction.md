# Introduction

Welcome to **neuralLoops**, a hands-on guide to learning Rust one small loop at a time.

The book is organized as short, focused examples. Each chapter introduces a Rust
concept, shows how it works in code, and builds toward programs that process data
iteratively.

For example, a `for` loop can repeat an operation over a range:

```rust
fn main() {
    for iteration in 1..=3 {
        println!("neuralLoops iteration {iteration}");
    }
}
```

The `1..=3` range includes both endpoints, so this program prints three iterations.
