---
title: "Dist-Orc: A Rewriting-based Distributed Implementation of Orc with Formal Analysis"
collection: publications
permalink: /publication/2010-09-22-alturki-meseguer-rtrts
date: 2010-09-22
venue: 'Rewriting Techniques for Real-Time Systems, EPTCS 36, pp 26-45'
paperurl: 'http://arxiv.org/abs/1009.4260v1'
citation: 'Musab A. Alturki and José Meseguer'
---

Orc is a theory of orchestration of services that allows structured programming of distributed and timed computations. Several formal semantics have been proposed for Orc, including a rewriting logic semantics developed by the authors. Orc also has a fully fledged implementation in Java with functional programming features. However, as with descriptions of most distributed languages, there exists a fairly substantial gap between Orc's formal semantics and its implementation, in that: (i) programs in Orc are not easily deployable in a distributed implementation just by using Orc's formal semantics, and (ii) they are not readily formally analyzable at the level of a distributed Orc implementation. In this work, we overcome problems (i) and (ii) for Orc. Specifically, we describe an implementation technique based on rewriting logic and Maude that narrows this gap considerably. The enabling feature of this technique is Maude's support for external objects through TCP sockets. We describe how sockets are used to implement Orc site calls and returns, and to provide real-time timing information to Orc expressions and sites. We then show how Orc programs in the resulting distributed implementation can be formally analyzed at a reasonable level of abstraction by defining an abstract model of time and the socket communication infrastructure, and discuss the assumptions under which the analysis can be deemed correct. Finally, the distributed implementation and the formal analysis methodology are illustrated with a case study.

[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)