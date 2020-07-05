---
title: "Implementing the Observer Design Pattern as an Expressive Language Construct"
collection: publications
permalink: /publication/2015-11-15-ghaleb-etal-icsea
date: 2015-11-15
venue: 'Software Engineering Advances, pp 463-469'
paperurl: 'http://www.thinkmind.org/index.php?view=article&articleid=icsea_2015_17_40_10407'
citation: 'Taher A. Ghaleb, Khalid Aljasser and Musab A. Alturki'
pdf: '/files/pub/ghaleb-etal-icsea.pdf'
bib: '/files/pub/ghaleb-etal-icsea.bib'
---

Observer is a commonly used design pattern as it carries a lot of reusability and modularity concerns in object-oriented programming and represents a good example of design reuse. Implementing the observer design pattern (and several other design patterns) is known to typically cause several problems such as implementation overhead and traceability. In the literature, several approaches have been proposed to alleviate such problems. However, these approaches only considered the implementation of a specific scenario of the observer pattern, which is concerned with having a single subject with multiple observers. In addition, the code used to implement this pattern was scattered throughout the program, which complicated implementing, tracing and reusing them. In this paper, we: A) provide a systematic classification of all possible scenarios of the observer design pattern and B) introduce a novel approach to implement them using an expressive and easy-to-use construct in Java. The proposed observer construct is built as a language extension using the abc extensible compiler. We illustrate through several observer scenarios how the construct significantly simplifies the implementation and improves reusability.
