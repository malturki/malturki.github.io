---
title: "Real-Time Rewriting Semantics of Orc"
collection: publications
permalink: /publication/2007-07-14-alturki-meseguer-ppdp
date: 2007-07-14
venue: 'Principles and Practice of Declarative Programming, ACM, pp 131–142'
paperurl: 'http://dl.acm.org/citation.cfm?id=1273920.1273938'
citation: 'Musab A. Alturki and José Meseguer'
pdf: '/files/alturki-meseguer-ppdp.pdf'
bib: '/files/alturki-meseguer-ppdp.bib'
---
Orc is a language proposed by Jayadev Misra for orchestration of distributed services. Orc is very simple and elegant, based on a few basic constructs, and allows succinct and understandable programming of sophisticated applications. However, because of its real-time nature and the different priorities given to internal and external events in an Orc program, giving a formal operational semantics that captures the real-time behavior of Orc programs is nontrivial and poses some interesting challenges. In this paper we propose such a real-time operational Orc semantics, that captures the informal operational semantics given in [19]. This operational semantics is given as a rewrite theory in which the elapse of time is explicitly modeled. The priorities between internal and external events are also modeled in two alternative ways: (i) by a rewrite strategy; and (ii) by adding extra conditions to the semantic rules. Since rewriting logic has efficient implementations such as Maude, we also get, directly out of the semantic definitions, both an Orc interpreter and an LTL model checker for Orc programs.
