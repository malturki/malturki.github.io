---
title: "Resource-Bounded Intruders in Denial of Service Attacks"
collection: publications
permalink: /publication/2019-09-05-urquiza-etal-csf
date: 2019-09-05
venue: 'Computer Security Foundations Symposium, IEEE, pp 382-396'
paperurl: 'https://ieeexplore.ieee.org/document/8823756'
citation: 'Abraão Aires Urquiza, Musab A. Alturki, Max Kanovich, Tajana Ban Kirigin, Vivek Nigam, Andre Scedrov and Carolyn Talcott'
pdf: '/files/pub/urquiza-etal-csf.pdf'
bib: '/files/pub/urquiza-etal-csf.bib'
---

Denial of Service (DoS) attacks have been a serious security concern, as no service is, in principle, protected against them. Although a Dolev-Yao intruder with unlimited resources can trivially render any service unavailable, DoS attacks do not necessarily have to be carried out by such (extremely) powerful intruders. It is useful in practice and more challenging for formal protocol verification to determine whether a service is vulnerable even to resource-bounded intruders that cannot generate or intercept arbitrary large volumes of traffic. This paper proposes a novel, more refined intruder model where the intruder can only consume at most some specified amount of resources in any given time window. Additionally, we propose protocol theories that may contain timeouts and specify service resource usage during protocol execution. In contrast to the existing resource-conscious protocol verification models, our model allows finer and more subtle analysis of DoS problems. We illustrate the power of our approach by representing a number of classes of DoS attacks, such as, Slow, Asymmetric and Amplification DoS attacks, exhausting different types of resources of the target, such as, number of workers, processing power, memory, and network bandwidth. We show that the proposed DoS problem is undecidable in general and is PSPACE-complete for the class of resource-bounded, balanced systems. Finally, we implemented our formal verification model in the rewriting logic tool Maude and analyzed a number of DoS attacks in Maude using Rewriting Modulo SMT in an automated fashion.
