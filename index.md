<!-- Heading -->
# Manu's User Page

<!-- Styled Test -->
I'm **Manu**, a second year at UCSD.

## Table of Contents
<!-- Section Links and Ordered List -->
1. [Favorites](https://enigmurl-ucsd.github.io/cse110-lab1/#favorites)
2. [Bucket List](https://enigmurl-ucsd.github.io/cse110-lab1/#my-bucket-list)
3. [Bibliography](https://enigmurl-ucsd.github.io/cse110-lab1/#bibliography)

<!-- Unordered List -->
## Favorites
<!-- Relative Link -->
- As a hobby, I enjoy *mathematical animations*. I provided a separate page [here](animation.md) with a few examples.

-  My favorite programming language is Rust due to its type system. I particularly like method chaining. Here's a snippet where I try to decompose a string that looks like `[key: value]`
<!-- Code Block -->
```rust
let parts: Vec<&str> = line[1 .. line.len() - 1]
        .splitn(2, ':')
        .map(str::trim)
        .collect();
```
<!-- Image -->
![Rust](/images/rust.png)

Another thing I like about Rust is its philisophy on multithreaded programming. Although this quote comes from Go, it is still largely relevant in Rust:
<!-- Quote -->
> Do not communicate by sharing memory; instead, share memory by communicating.

<!-- Task List -->
## My Bucket List
Some of the things I want to do before graduating.
- [x] Visit the Beach
- [ ] Meet more professors
- [ ] Take graduate courses

## Bibliography
<!-- External Link -->
1. [Share Memory By Communicating](https://go.dev/blog/codelab-share)