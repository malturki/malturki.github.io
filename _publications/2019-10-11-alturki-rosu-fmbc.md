	---
title: "Statistical Model Checking of RANDAO's Resilience to Pre-computed Reveal Strategies"
collection: publications
permalink: /publication/2019-10-11-alturki-rosu-fmbc
date: 2019-10-11
venue: 'Formal Methods for Blockchains, (to appear)'
paperurl: 'https://sites.google.com/view/fmbc/program?authuser=0'
citation: 'Musab A. Alturki and Grigore Roşu'
pdf: '/files/pub/alturki-rosu-fmbc.pdf'
bib: '/files/pub/alturki-rosu-fmbc.bib'
---

RANDAO is a commit-reveal scheme for generating pseudo-
random numbers in a decentralized fashion. The scheme is used in emerg-
ing blockchain systems as it is widely believed to provide randomness
that is unpredictable and hard to manipulate by maliciously behaving
nodes. However, RANDAO may still be susceptible to look-ahead at-
tacks, in which an attacker (controlling a subset of nodes in the net-
work) may attempt to pre-compute the outcomes of (possibly many)
reveal strategies, and thus may bias the generated random number to
his advantage. In this work, we formally evaluate resilience of RANDAO
against such attacks. We first develop a probabilistic model in rewrit-
ing logic of RANDAO, and then apply statistical model checking and
quantitative verification algorithms (using Maude and PVeStA) to an-
alyze two di↵erent properties that provide di↵erent measures of bias that
the attacker could potentially achieve using pre-computed strategies. We
show through this analysis that unless the attacker is already controlling
a sizable percentage of nodes while aggressively attempting to maximize
control of the nodes selected to participate in the process, the expected
achievable bias is quite limited.
