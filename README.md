# Central repository for work on susyp2p

<a href="http://susyp2p.io/"><img src="https://img.shields.io/badge/project-susyp2p-yellow.svg?style=flat-square" /></a>
<a href="http://webchat.freenode.net/?channels=%23susyp2p"><img src="https://img.shields.io/badge/freenode-%23susyp2p-yellow.svg?style=flat-square" /></a>
[![dependency status](https://deps.rs/repo/github/susyp2p/rust-susyp2p/status.svg?style=flat-square)](https://deps.rs/repo/github/susyp2p/rust-susyp2p)

This repository is the central place for Rust development of the [susyp2p](https://susyp2p.io) spec.

**Warning**: While we are trying our best to be compatible with other susyp2p implementations, we
cannot guarantee that this is the case considering the lack of a precise susyp2p specifications.

## Documentation

This repository includes a façade crate named `susyp2p`, which reexports the rest of the repository.

For documentation, you are encouraged to clone this repository or add `susyp2p` as a dependency in
your Cargo.toml and run `cargo doc`.

```toml
[dependencies]
susyp2p = "0.2.2"
```

## Notable users

(open a pull request if you want your project to be added here)

- https://github.com/susytech/polkadot
- https://github.com/susytech/higgsfield
- https://github.com/sigp/lighthouse
