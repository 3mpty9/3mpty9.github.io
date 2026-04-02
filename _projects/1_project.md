---
layout: page
title: CKKS Kernel Profiler
description: Profiling framework for secure ML primitives.
img: assets/img/12.jpg
importance: 1
related_publications: true
---

This project provides a profiling and analysis toolkit for CKKS-based workloads.
It focuses on identifying runtime hotspots in automorphism and NTT-heavy operator pipelines.

## Highlights

- detailed operator-level tracing for encrypted inference paths
- latency and memory breakdown across kernel stages
- reusable experiment scripts for architecture studies

## Outcome

The framework makes it easier to compare optimization strategies and supports
reproducible reporting for paper artifacts.
