---
title: "Resource-bounded Intruders in Denial of Service Attacks"
excerpt: "S"
collection: projects
---

Denial of Service (DoS) attacks have been a serious security concern, as no service is, in principle, protected against them. Although a Dolev-Yao intruder with unlimited resources can trivially render any service unavailable, DoS attacks do not necessarily have to be carried out by such (extremely) powerful intruders. It is useful in practice and more challenging for formal protocol verification to determine whether a service is vulnerable even to resource-bounded intruders that cannot generate or intercept arbitrary large volumes of traffic. We develop in this project a novel, more refined intruder model where the intruder can only consume at most some specified amount of resources in any given time window. Additionally, we propose protocol theories that may contain timeouts and specify service resource usage during protocol execution, and illustrate how our approach can represent a number of classes of DoS attacks, such as, Slow, Asymmetric and Amplification DoS attacks.

More detailed can be found [here](#).