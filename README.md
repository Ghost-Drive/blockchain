<!--
parent:
  order: false
-->

<div align="center">
  <h1> Blockchain </h1>
</div>

<div align="center">
  <a href="https://github.com/evmos/evmos/releases/latest">
    <img alt="Version" src="https://img.shields.io/github/tag/evmos/evmos.svg" />
  </a>
  <a href="https://github.com/evmos/evmos/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/evmos/evmos.svg" />
  </a>
  <a href="https://pkg.go.dev/github.com/evmos/evmos">
    <img alt="GoDoc" src="https://godoc.org/github.com/evmos/evmos?status.svg" />
  </a>
  <a href="https://goreportcard.com/report/github.com/evmos/evmos">
    <img alt="Go report card" src="https://goreportcard.com/badge/github.com/evmos/evmos"/>
  </a>
</div>
<div align="center">
  <a href="https://discord.gg/evmos">
    <img alt="Discord" src="https://img.shields.io/discord/809048090249134080.svg" />
  </a>
  <a href="https://github.com/evmos/evmos/actions?query=branch%3Amain+workflow%3ALint">
    <img alt="Lint Status" src="https://github.com/evmos/evmos/actions/workflows/lint.yml/badge.svg?branch=main" />
  </a>
  <a href="https://codecov.io/gh/evmos/evmos">
    <img alt="Code Coverage" src="https://codecov.io/gh/evmos/evmos/branch/main/graph/badge.svg" />
  </a>
  <a href="https://twitter.com/EvmosOrg">
    <img alt="Twitter Follow Evmos" src="https://img.shields.io/twitter/follow/EvmosOrg"/>
  </a>
</div>

## About

Ghostdrive is a scalable, high-throughput Proof-of-Stake EVM blockchain
that is fully compatible and interoperable with Ethereum.
It's built using the [Cosmos SDK](https://github.com/cosmos/cosmos-sdk/)
which runs on top of the [CometBFT](https://github.com/cometbft/cometbft) consensus engine.

## Quick Start

To learn how Ghostdrive works from a high-level perspective,
go to the [Protocol Overview](https://docs.evmos.org/protocol) section of the documentation.
You can also check the instructions to [Run a Node](https://docs.evmos.org/protocol/evmos-cli#run-an-evmos-node).

## Documentation

Our documentation is hosted in a [separate repository](https://github.com/evmos/docs) and can be found at [docs.evmos.org](https://docs.evmos.org).
Head over there and check it out.

## Installation

For prerequisites and detailed build instructions
please read the [Installation](https://docs.evmos.org/protocol/evmos-cli) instructions.
Once the dependencies are installed, run:

```bash
make install
```


## Contributing

Looking for a good place to start contributing?
Check out some
[`good first issues`](https://github.com/evmos/evmos/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22).

For additional instructions, standards and style guides, please refer to the [Contributing](./CONTRIBUTING.md) document.

### SPDX Identifier

The following header including a license identifier in [SPDX](https://spdx.dev/learn/handling-license-info/)
short form has been added to all ENCL-1.0 files:

```go
// Copyright Tharsis Labs Ltd.(Evmos)
// SPDX-License-Identifier:ENCL-1.0(https://github.com/evmos/evmos/blob/main/LICENSE)
```

Exempted files contain the following SPDX ID:

```go
// Copyright Tharsis Labs Ltd.(Evmos)
// SPDX-License-Identifier:LGPL-3.0-only
```




