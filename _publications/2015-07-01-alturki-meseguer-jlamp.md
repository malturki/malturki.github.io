---
title: "Executable Rewriting Logic Semantics of Orc and Formal Analysis of Orc Programs"
collection: publications
permalink: /publication/2015-07-01-alturki-meseguer-jlamp
date: 2015-07-01
venue: 'Journal of Logical and Algebraic Methods in Programming, Volume 84(4), pp 505–533'
paperurl: 'http://www.sciencedirect.com/science/article/pii/S2352220815000334'
citation: 'Musab A. Alturki and José Meseguer'
---

The Orc calculus is a simple, yet powerful theory of concurrent computations with great versatility and practical applicability to a very wide range of applications, as it has been amply demonstrated by the Orc language, which extends the Orc calculus with powerful programming constructs that can be desugared into the underlying formal calculus. This means that for: (i) theoretical, (ii) program verification, and (iii) language implementation reasons, the formal semantics of Orc is of great importance. Furthermore, having a semantics of Orc that is executable is essential to provide: (i) a formally-defined interpreter against which language implementations can be validated, and (ii) a (semi-)automatic way of generating a wide range of semantics-based program verification tools, including model checkers and theorem provers.

This work proposes a formal executable semantics for Orc in rewriting logic, to support formal verification of Orc programs and to make possible semantics-based correct-by-construction Orc implementations. While being a very simple calculus, Orc has a quite subtle semantics, so that fully capturing all its semantic aspects is highly nontrivial. The two main sources of subtlety are: (i) its real-time semantics, and (ii) the priority of internal computations within an Orc expression over external computations that process responses from external sites. In this paper, we show a simple and elegant way of handling these two sources of subtlety in rewriting logic using an order-sorted type system supporting subtypes and subtype polymorphism, and “tick” rewrite rules for capturing time. Moreover, our rewriting semantics incorporates useful semantic equivalences between Orc programs as equations and equational attributes, making the semantics both more abstract and more efficient. The semantics of Orc is given in two different styles: (i) an SOS style, which is directly based on the original SOS of Orc, whose correctness follows immediately by construction, and (ii) a reduction semantics, which is much more efficiently executable and analyzable, as shown through several experiments, and whose correctness is proved using a strong bisimulation theorem. The paper also presents MOrc, a simulator and model checking tool based on the rewriting semantics of Orc and Real-Time Maude. MOrc facilitates formal verification of Orc programs, and allows for user-defined state predicates and LTL formulas, with no need for any prior knowledge of Maude or its rewriting logic foundations.



[Pre-print](http://academicpages.github.io/files/paper1.pdf) |
[Bibtex](#)