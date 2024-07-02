---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

About
======

I am a PhD candidate in Electrical Engineering at Stanford University, where I am advised by [Christos Kozyrakis](https://web.stanford.edu/~kozyraki/). I am partially supported by a [Stanford Graduate Fellowship](https://vpge.stanford.edu/fellowships-funding/sgf) as the Cisco Systems Fellow.

My recent research explores computer systems for large-scale machine learning workloads.
Specifically, my core goal is to accelerate training for multi-trillion parameter models.
To tackle this challenge, I focus on designing high-throughput end-host network stack architectures, optimizing collective communication, and developing novel memory management frameworks.

Research
======
**Accelerating Mixture of Experts**\
*work in progress*\
Sparsely activated Mixture of Expert models (MoE) increase model size with a sub-linear increase in computation cost. However, this benefit comes at the expense of significantly higher memory capacity requirements. We propose a novel design that significantly reduces the memory footprint of MoE models while simultaneously reducing system latency and leading to faster convergence during training.

**High-Throughput and Flexible End-host Networking**\
*OSDI '24*\
End-host network stacks are struggling to provide both terabit throughput and protocol flexibility.
Today's high-performance RDMA solutions terminate the protocol in the NIC, and do not allow users to easily customize the transport protocol to address diverse workloads and deployments.
In our work, we physically separate the data and control paths, to combine RDMA performance with robust protocols like TCP.
Our design enables a high-throughput sender and receiver zero-copy data path to any endpoint (e.g. GPUs),
and an independent control path to execute arbitrary transport protocols in any execution environment (e.g. the Linux kernel).

**A Database Operating System**\
*VLDB '22, CIDR '22, Poly '21*\
This project pursues the direction of building distributed systems that leverage the guarantees of databases instead of reimplementing them.
The focus is on transparently utilizing database features such as efficiency, transactional guarantees, and the programmability of a declarative language.
In the DBOS project we build a novel Operating System stack, and a high-performance FaaS platform on top of a DBMS.


Publications
======

[High-throughput and Flexible Host Networking via Control and Data Path Physical Separation](files/osdi24-skiadopoulos.pdf)\
**A Skiadopoulos**, Z Xie, M Zhao, Q Cai, S Agarwal, J Adelmann, D Ahern, C Contavalli, M Goldflam, V Mayatskikh, R Raja, D Walton, R Agarwal, S Mukherjee, C Kozyrakis\
*accepted at 18th USENIX Symposium on Operating Systems Design and Implementation (OSDI '24)*

[Scaling a Declarative Cluster Manager Architecture with Query Optimization Techniques](https://dl.acm.org/doi/pdf/10.14778/3603581.3603599)\
K Rong, M Budiu, **A Skiadopoulos**, L Suresh, A Tai\
*Proceedings of the VLDB Endowment, Vol. 16, No. 10 (VLDB '23)*

[Apiary: A DBMS-Integrated Transactional Function-as-a-Service Framework](https://arxiv.org/pdf/2208.13068.pdf)\
P Kraft, Q Li, K Kaffes, **A Skiadopoulos**, D Kumar, D Cho, J Li, R Redmond, N Weckwerth, B Xia, P Bailis, MJ Cafarella, G Graefe, J Kepner, C Kozyrakis, M Stonebraker, L Suresh, X Yu, M Zaharia\
*arXiv preprint, 2023*

[A Progress Report on DBOS: A Database-oriented Operating System](files/dbos-cidr.pdf)\
Q Li, P Kraft, K Kaffes, **A Skiadopoulos**, D Kumar, J Li, MJ Cafarella, G Graefe, J Kepner, C Kozyrakis, M Stonebraker, L Suresh, M Zaharia\
*12th Annual Conference on Innovative Data Systems Research (CIDR '22).*

[DBOS: a DBMS-oriented Operating System](https://dl.acm.org/doi/pdf/10.14778/3485450.3485454)\
**A Skiadopoulos**, Q Li, P Kraft, K Kaffes, D Hong, S Mathew, D Bestor, MJ Cafarella, V Gadepally, G Graefe, J Kepner, C Kozyrakis, T Kraska, M Stonebraker, L Suresh, M Zaharia\
*Proceedings of the VLDB Endowment, Vol. 15, No 1 (VLDB '22)*


Internships
======
[Enfabrica](https://enfabrica.net/), Software Engineering Research Intern\
Mentor: [Shrijeet Mukherjee](https://www.linkedin.com/in/shrijeet-mukherjee-b275/)\
Summer of 2023

[Enfabrica](https://enfabrica.net/), Software Engineering Research Intern\
Mentor: [Shrijeet Mukherjee](https://www.linkedin.com/in/shrijeet-mukherjee-b275/)\
Summer of 2022

[VMware](https://www.vmware.com/), Research Intern\
Mentor: [Lalith Suresh](https://lalith.in/about/)\
Summer of 2021


Contact
======

Email:
<code class="language-plaintext"><span>a</span><span style="display:none;">HIDDEN</span><span>s</span><span>k</span><span style="display:none;">HIDDEN</span><span>i</span><span>a</span><span style="display:none;">HIDDEN</span><span>d</span><span>@</span><span>s</span><span style="display:none;">HIDDEN</span><span>tanf</span><span style="display:none;">HIDDEN</span><span>ord</span><span>.</span><span>edu</span></code>

Office: 353 Jane Stanford Way, Gates CS Building Room 418, Stanford CA

