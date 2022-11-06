# setup-substrate

[![CI](https://github.com/chiefbiiko/setup-substrate/workflows/ci/badge.svg)](https://github.com/chiefbiiko/setup-substrate/actions)

A GitHub action that installs a Substrate Rust toolchain.

[`zombienet`](https://github.com/paritytech/zombienet) is included in the installation.

Supports Linux runners only for now.

## Usage

```yml
- uses: chiefbiiko/setup-substrate@v0.1.0
```

## Inputs

+ `nightly-version` Nightly Rust toolchain to set up. Default: `nightly`
+ `target-dir` Main Rust target dir to be cached. Default: `./target/`

## Outputs

+ `rust-version`
+ `cargo-version`
+ `zombienet-version`