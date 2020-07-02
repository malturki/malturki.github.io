---
title: "An executable model of the Beacon Chain protocol"
excerpt: "An executable K model of Ethereum 2.0 Beacon Chain Phase 0 specification"
collection: projects
---

The Beacon Chain is the main proof-of-stake block chain in Ethereum 2.0 maintaining information about validators, attestations, crosslinks, and other components of the protocol. The structure and operation of the Beacon Chain are defined by its reference implementation in Python developed by the Ethereum Foundation. Our ultimate goal is to have a formal framework for specifying and executing the protocol and verifying its safety and liveness properties. In this project, we introduce a first-step towards achieving this goal, which is an executable, formal specification of the full Beacon Chain specification given by "Ethereum 2.0 Phase 0" in the K framework. The model is validated using the standard Beacon Chain test suite and used to generate new tests that improve test coverage.

The project is hosted [here](https://github.com/runtimeverification/beacon-chain-spec).