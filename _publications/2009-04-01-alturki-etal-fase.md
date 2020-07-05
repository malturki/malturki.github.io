---
title: "Formal Specification and Analysis of Timing Properties in Software Systems"
collection: publications
permalink: /publication/2009-04-01-alturki-etal-fase
date: 2009-04-01
venue: 'Fundamental Approaches to Software Engineering, Springer, LNCS 5503, pp 262-277'
paperurl: 'http://link.springer.com/chapter/10.1007/978-3-642-00593-0_18'
citation: 'Musab A. Alturki, Dinakar Dhurjati, Dachuan Yu, Ajay Chander and Hiroshi Inamura'
pdf: '/files/pub/alturki-etal-fase.pdf'
bib: '/files/pub/alturki-etal-fase.bib'
---
Specifying and analyzing timing properties is a critical but error-prone aspect of developing many modern software systems. In this paper, we propose a new specification language and analysis framework for expressing and analyzing timing behaviors of complex software systems. Our framework has the following significant benefits: a) it is expressive, b) it supports trace analysis and simulation of timing behaviors, c) allows for verification of properties of specification, and d) checks for common usage errors of timing constructs. The language constructs for timing were chosen to be very flexible, suitable for expressing different kinds of timing behaviors, and are inspired from timing constructs used in previous languages like SDL. We define the formal semantics of our language using a real-time rewrite theory. Since real-time rewrite theories are executable in Real-Time Maude, our framework supports trace analysis and simulation of timing behavior for specifications. Furthermore, the timed model checker for Real-Time Maude can be readily used for analyzing and verifying various real-time properties of the specifications. Finally, to prevent misuses of timing constructs that can be made possible due to their flexibility, we develop abstract interpretation based static analysis tools that check for common usage errors. We believe that our framework, with the above benefits, provides a significant step forward in facilitating the use of formal tools for specification and analysis of timing behaviors in software development.
