	---
title: "Towards a Verified Model of the Algorand Consensus Protocol in Coq"
collection: publications
permalink: /publication/2019-10-11-alturki-etal-fmbc
date: 2019-10-11
venue: 'Formal Methods for Blockchains, (to appear)'
paperurl: 'https://sites.google.com/view/fmbc/program?authuser=0'
citation: 'Musab A. Alturki, Jing Chen, Victor Luchangco, Brandon Moore, Karl Palmskog, Lucas Peña and Grigore Roşu'
---

The Algorand blockchain is a secure and decentralized public
ledger based on pure proof of stake rather than proof of work. At its core
it is a novel consensus protocol with exactly one block certified in each
round: that is, the protocol guarantees that the blockchain does not
fork. In this paper, we report on our effort to model and formally verify
the Algorand consensus protocol in the Coq proof assistant. Similar to
previous consensus protocol verification efforts, we model the protocol
as a state transition system and reason over reachable global states.
However, in contrast to previous work, our model explicitly incorporates
timing issues (e.g., timeouts and network delays) and adversarial actions,
reflecting a more realistic environment faced by a public blockchain.
Thus far, we have proved asynchronous safety of the protocol: two differ-
ent blocks cannot be certified in the same round, even when the adver-
sary has complete control of message delivery in the network. We believe
that our model is sufficiently general and other relevant properties of the
protocol such as liveness can be proved for the same model.

[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)