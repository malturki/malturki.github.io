---
title: "Probabilistic Modeling and Analysis of DoS Protection for the ASV Protocol"
collection: publications
permalink: /publication/2009-03-28-alturki-etal-secret
date: 2009-03-28
venue: 'Security and Rewriting Techniques, ENTCS 234, pp 3-18'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1571066109000747'
citation: 'Musab A. Alturki, José Meseguer and Carl A. Gunter'
---
The Adaptive Selective Verification (ASV) protocol was recently proposed as an effective and efficient DoS countermeasure within the shared channel model, in which clients and attackers probabilistically share communication bandwidth with the server. ASV has been manually shown to satisfy some desirable availability and bandwidth consumption properties. Due to the probabilistic nature of the protocol and its underlying attacker model, it is intrinsically difficult to build a faithful model of the protocol with which one may automatically verify its properties. This paper fills the gap between manual analysis and simulation-based experimental analysis of ASV, through automated formal analysis. We describe a formal model of ASV using probabilistic rewrite theories, implemented in a probabilistic extension of Maude, and show how it can be used to formally verify various characteristics of ASV through automated statistical quantitative model checking analysis techniques. In particular, we formally verify ASV's connection confidence theorem and a slightly more general bandwidth consumption theorem of ASV. This is followed by a statistical comparison of ASV with non-adaptive selective verification protocols. We conclude with remarks on possible further development and future work.

[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)