---
title: "Reduction Semantics and Formal Analysis of Orc Programs"
collection: publications
permalink: /publication/2008-01-01-alturki-meseguer-wwv
date: 2008-01-01
venue: 'Automated Specification and Verification of Web Systems, ENTCS 200, pp 25–41, 2008'
paperurl: 'http://www.sciencedirect.com/science/article/pii/S157106610800306X'
citation: 'Musab A. Alturki and José Meseguer'
---
Orc is a language for orchestration of web services developed by J. Misra that offers simple, yet powerful and elegant, constructs to program sophisticated web orchestration applications. The formal semantics of Orc poses interesting challenges, because of its real-time nature and the different priorities of external and internal actions. In this paper, building upon our previous SOS semantics of Orc in rewriting logic, we present a much more efficient reduction semantics of Orc, which is provably equivalent to the SOS semantics thanks to a strong bisimulation. We view this reduction semantics as a key intermediate stage towards a future, provably correct distributed implementation of Orc, and show how it can naturally be extended to a distributed actor-like semantics. We show experiments demonstrating the much better performance of the reduction semantics when compared to the SOS semantics. Using the Maude rewriting logic language, we also illustrate how the reduction semantics can be used to endow Orc with useful formal analysis capabilities, including an LTL model checker. We illustrate these formal analysis features by means of an online auction system, which is modeled as a distributed system of actors that perform Orc computations.

[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)