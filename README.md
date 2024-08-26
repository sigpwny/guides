# Guides

This repo houses all the guides / docs for SIGPwny.

All docs are written in markdown and rendered with mdbook.

You can read the mdbook docs [here](https://rust-lang.github.io/mdBook/).

Guides are built and deployed through the [sigpwny/websites](https://github.com/sigpwny/websites) monorepo.

## Quick setup

```bash
# install rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
# install mdbook
cargo install mdbook
# <name of book>
mdbook serve fallctf-2023
```
