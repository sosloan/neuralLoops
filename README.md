# neuralLoops

An mdBook for learning Rust through small, iterative examples.

## Build and preview

Install [mdBook](https://rust-lang.github.io/mdBook/guide/installation.html), then run:

```sh
mdbook serve --open
```

To build the book without starting the preview server:

```sh
mdbook build
```

## Custom CSS

The book loads a custom dark theme from `theme/custom.css`, wired through
`additional-css` in `book.toml`. The palette and typography are derived from
`example.css` (gold accent `#D4AF37`, near-black surfaces, mono labels).

Edit `theme/custom.css` to adjust colors, headings, code blocks, or sidebar
chrome. Rebuild or refresh `mdbook serve` to see changes.
