---
title: "Towards Reproducible Evaluation of Distributed Quantum Circuit Partitioning Algorithms"
authors_before: ""
authors_after: ", Davud Azizov, Tian Guo"
collection: publications
permalink: /publication/2026_dqceval
tldr: Distributed Quantum Computing (DQC) connects modular Quantum Processing Units (QPUs) to overcome the scaling limits of monolithic processors. Executing algorithms across QPUs requires circuit partitioning while minimizing inter-QPU communication. Existing evaluations focus mainly on entanglement cost and overlook structural and temporal overheads. We address this gap by applying established benchmarking metrics to partitioned circuits. Using an open-source evaluation pipeline, we assess partitioning algorithms across standard workloads and network topologies. Results show that algorithms with similar entanglement costs can cause very different execution penalties, including deeper circuits and lower gate density. These findings highlight the need for comprehensive circuit-level metrics when designing DQC compilers.
date: 2026-8-27
header:
  teaser: publications/dqceval.png
code: https://github.com/cake-lab/dqc-evaluation/
preprint: https://arxiv.org/abs/2608.27099
categories:
  - Distributed Quantum Computing
  - Quantum Benchmarking
  - Circuit Partitioning
---
