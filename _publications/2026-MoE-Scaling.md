---
title: "Holistic Scaling Laws for Optimal Mixture-of-Experts Architecture Optimization"
collection: publications
category: preprint
permalink: /publication/2026-MoE-Scaling
excerpt: 'This paper establishes the first holistic framework for global MoE architectural optimization, reducing the intractable 16-dimensional search space to a two-phase sequential procedure via mathematical constraints and rank-preserving properties.'
date: 2026-03-23
venue: 'arXiv preprint arXiv:2603.21862'
paperurl: 'https://arxiv.org/pdf/2603.21862'
authors: "<b>Weilin Wan</b>, Jingtao Han, Weizhong Zhang, Cheng Jin"

---

Scaling laws for Large Language Models govern macroscopic resource allocation, yet translating these into concrete Mixture-of-Experts (MoE) architectural designs remains challenging. Existing approaches either directly incorporate MoE-specific variables into scaling formulas—causing coefficient explosion and unreliable fitting—or isolate MoE parameters while fixing other components, limiting generalizability. This paper proposes a holistic framework that reduces the complex 16-dimensional architectural search space into a tractable two-phase sequential procedure through mathematical constraints, empirically validated rank-preserving properties, and coordinate transformations.

A key insight is that FLOPs per token alone is insufficient for characterizing MoE models; instead, a joint constraint triad of FLOPs per token, active parameters, and total parameters is required to prevent misleading gains driven by parameter inflation. Validated across approximately 670 MoE models spanning computational scales from 10^18 to 3×10^20 FLOPs, the framework produces robust scaling laws that map any given compute budget to a complete, deterministic architectural specification. A critical empirical finding reveals that the near-optimal configuration band widens with scale, granting larger models greater architectural flexibility while maintaining near-optimal performance—offering practitioners a quantitative basis for navigating trade-offs between theoretical recommendations and real-world infrastructure constraints.
