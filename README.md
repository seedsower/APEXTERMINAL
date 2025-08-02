<div align="center">
  <h1 style="margin-top:20px;">APex Commodity</h1>

  <p>
    <a href="#"><img alt="Docs" src="https://img.shields.io/badge/docs-tutorials-blueviolet" /></a>
    <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/github/license/project-serum/anchor?color=blueviolet" /></a>
  </p>
</div>

# APex Commodity

This repository provides open source access to APex Commodity's Typescript SDK, Solana Programs, and more.

Integrating APex Commodity? [Go here](./sdk/README.md)

# SDK Guide

SDK docs can be found [here](./sdk/README.md)

# Example Bot Implementations

Example bots (makers, liquidators, fillers, etc) can be found [here](https://github.com/drift-labs/keeper-bots-v2)

# Building Locally

Note: If you are running the build on an Apple computer with an M1 chip, please set the default rust toolchain to `stable-x86_64-apple-darwin`

```bash
rustup default stable-x86_64-apple-darwin
```

## Compiling Programs

```bash
# build v2
anchor build
# install packages
yarn
# build sdk
cd sdk/ && yarn && yarn build && cd ..
```

## Running Rust Test

```bash
cargo test
```

## Running Javascript Tests

```bash
bash test-scripts/run-anchor-tests.sh
```

# Bug Bounty

Information about the Bug Bounty can be found [here](./bug-bounty/README.md)
