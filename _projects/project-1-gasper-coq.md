---
title: "Modeling and Verification of Gasper"
excerpt: "Modeling Gasper and verifying its properties using the Coq proof assistant"
permalink: /projects/project-1-gasper-coq
collection: projects
---

Gasper is an abstract proof-of-stake protocol layer that is implemented by the Beacon Chain protocol, the underlying protocol of the Ethereum 2.0 network. A key component of Gasper is a finality mechanism that extends the original Casper FFG protocol primarily with k-finalization. In addition to the accountable safety and plausible liveness properties, Gasper describes how the protocol generalizes to the setting of dynamic validator sets and gives a lower bound on validator stake that can provably be slashed in this setting. In this work, we model and verify this finality mechanism of Gasper with dynamic validator sets using the Coq proof assistant.

The project is hosted [here](#).