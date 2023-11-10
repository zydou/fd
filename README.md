# fd

This repository uses GitHub Actions to build the `fd` tool.

The [official repository](sharkdp/fd) lacks support for architectures such as `aarch64-apple-darwin`. This repository aims to build the following architectures:

- aarch64-unknown-linux-musl
- aarch64-unknown-linux-gnu
- aarch64-apple-darwin
- x86_64-unknown-linux-musl
- x86_64-unknown-linux-gnu
- x86_64-apple-darwin