---
title: "Towards Formal Verification of Orchestration Computations Using the K Framework"
collection: publications
permalink: /publication/2015-04-01-alturki-alzuhaibi-fm
date: 2015-04-01
venue: 'Formal Methods, Springer, LNCS 9109, pp 40-56'
paperurl: 'http://link.springer.com/chapter/10.1007%2F978-3-319-19249-9_4'
citation: 'Musab A. Alturki and Omar Alzuhaibi'
---

Orchestration provides a general model of concurrent computations. A minimal yet expressive theory of orchestration is provided by Orc, in which computations are modeled by site calls and their orchestrations through a few combinators. Using Orc, formal verification of correctness of orchestrations amounts to devising an executable formal semantics of Orc and leveraging existing tool support. Despite its simplicity and elegance, giving formal semantics to Orc capturing precisely its intended behaviors is far from trivial primarily due to the challenges posed by concurrency, timing and the distinction between internal and external actions. This paper presents a semantics-based approach for formally verifying Orc orchestrations using the K framework. Unlike previously developed operational semantics of Orc, the K semantics is not directly based on the interleaving semantics given by Orc’s SOS specification. Instead, it is based on concurrent rewriting enabled by K. It also utilizes various K facilities to arrive at a clean, minimal and elegant semantic specification. To demonstrate the usefulness of the proposed approach, we describe a specification for a simple robotics case study and provide initial formal verification results.


[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)