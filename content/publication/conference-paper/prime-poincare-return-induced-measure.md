---
title: "PRIME: Poincaré Return Induced Measure for Learning Partially Observed Dynamical Systems"
authors:
- Yiting Duan
- Longyan Tan
- Hao Wu
- Mehdi Tavakol
- Yi Guo
# NOTE: production builds skip future-dated pages, so this must not be a future date.
date: "2026-11-23"
publication_types: ["1"]
publication: "**Advances in Neural Information Processing Systems (NeurIPS 2026)** (accepted)"
featured: true
summary: "Accepted at NeurIPS 2026. PRIME imposes recurrence-level long-term temporal constraints to prevent rollout collapse when learning dynamics from sparse partial observations."
abstract: "Learning dynamics from sparse partial observations presents a fundamental dilemma: the pointwise mean squared error (MSE) training objective may induce local contraction and empirically lead to long-term rollout collapse, whereas invariant-measure matching preserves global geometry but lacks long-term temporal ordering constraints. To resolve this, we introduce the Poincaré Return Induced Measure (PRIME) framework. PRIME bridges this gap by imposing long-term temporal constraints through recurrence-level temporal organization. Instead of relying on unstable pointwise matching, PRIME refines the learned dynamics by leveraging recurrence-level temporal information, specifically by aligning the empirical recurrence graph measures constructed from consecutive recurrence events. We evaluate PRIME on the partially observed Lorenz63 system, sensor-observed Kuramoto-Sivashinsky equation, and flow past a cylinder. Across all benchmarks, PRIME effectively mitigates long-term rollout collapse and improves temporal consistency while maintaining or enhancing long-term geometric and spectral fidelity."
tags:
- "Dynamical Systems"
- "Partially Observed Systems"
- "Invariant Measure"
- "Machine Learning"
- "Deep Learning"
---
