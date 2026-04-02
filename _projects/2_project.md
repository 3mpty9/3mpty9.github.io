---
layout: page
title: FHE Accelerator Toolchain
description: Compiler and runtime support for CKKS-oriented accelerators.
img: assets/img/3.jpg
importance: 2
---

This project focuses on turning algorithmic insights into practical tooling:

- an intermediate representation for CKKS-heavy compute graphs
- cost models for automorphism, key-switch, and NTT operators
- scheduling heuristics that target throughput under memory limits

The resulting prototype reduced kernel launch overhead and improved end-to-end
inference consistency across multiple parameter sets.
