---
title: "Stable Availability under Denial of Service Attacks through Formal Patterns"
collection: publications
permalink: /publication/2012-04-01-eckhardt-etal-fase
date: 2012-04-01
venue: 'Fundamental Approaches to Software Engineering, Springer, LNCS 7212, pp 78-93'
paperurl: 'http://link.springer.com/chapter/10.1007%2F978-3-642-28872-2_6'
citation: 'Jonas Eckhardt, Tobias Mühlbauer, Musab A. Alturki, José Meseguer and Martin Wirsing'
---

Availability is an important security property for Internet services and a key ingredient of most service level agreements. It can be compromised by distributed Denial of Service (DoS) attacks. In this work we propose a formal pattern-based approach to study defense mechanisms against DoS attacks. We enhance pattern descriptions with formal models that allow the designer to give guarantees on the behavior of the proposed solution. The underlying executable specification formalism we use is the rewriting logic language Maude and its real-time and probabilistic extensions. We introduce the notion of stable availability, which means that with very high probability service quality remains very close to a threshold, regardless of how bad the DoS attack can get. Then we present two formal patterns which can serve as defenses against DoS attacks: the Adaptive Selective Verification (ASV) pattern, which enhances a communication protocol with a defense mechanism, and the Server Replicator (SR) pattern, which provisions additional resources on demand. However, ASV achieves availability without stability, and SR cannot achieve stable availability at a reasonable cost. As a main result we show, by statistical model checking with the PVeStA tool, that the composition of both patterns yields a new improved pattern which guarantees stable availability at a reasonable cost.





[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)