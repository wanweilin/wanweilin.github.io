---
title: "Explore and Establish Synergistic Effects Between Weight Pruning and Coreset Selection in Neural Network Training"
collection: publications
category: conferences
permalink: /publication/2025-SWaST
excerpt: 'This paper investigates the interplay between weight pruning and coreset selection, proposing a synergistic training mechanism (SWaST) that alternately optimizes both to improve efficiency and accuracy while preventing critical information loss.'
date: 2026-01-24
venue: 'AAAI'
paperurl: 'https://arxiv.org/pdf/2511.09901'
authors: "<b>Weilin Wan</b>, Fan Yi, Weizhong Zhang, Quan Zhou, Cheng Jin"  

---

Modern deep neural networks require massive computational resources. Weight pruning and coreset selection are two effective paradigms for reducing these costs, but they are typically studied in isolation. This paper explores the synergistic effects between them, revealing that redundant samples complicate weight pruning while irrelevant weights undermine coreset selection.

To harness this interplay, the authors propose **Simultaneous Weight and Sample Tailoring (SWaST)**, a mechanism that alternately performs weight pruning and coreset selection. They identify a phenomenon termed "critical double-loss," where important weights and supportive samples are simultaneously removed, leading to irreversible degradation. SWaST incorporates a state preservation mechanism to mitigate this issue, enabling stable joint optimization. Experiments demonstrate that SWaST achieves significant accuracy boosts (up to 17.83%) and FLOPs reductions (10%-90%) compared to independent application of these techniques.
