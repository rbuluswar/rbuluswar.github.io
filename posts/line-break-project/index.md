---
title: "How a Tiny Transformer Learns Line Structure"
description: "An interactive investigation of representation geometry and causal mechanisms in a small Transformer trained to predict line breaks."
author: "Rohan Buluswar"
date: 2026-10-13
categories: [mechanistic interpretability, transformers]
---

This is the long-form research writeup for the line-break prediction project.

The final version will combine the conceptual story with interactive 3D PCA
figures that readers can rotate, zoom, and inspect with hover labels. The
underlying experiments and notebooks live in the
[Line Break Project repository](https://github.com/rbuluswar/Line-Break-Project).

## Planned structure

1. The prediction task and toy Transformer.
2. The emergence of a line-progress representation.
3. Layer-1 attention and the character-count feature.
4. Causal ablations and interventions.
5. How later layers use the constructed state.

Interactive figures and static fallbacks will be added under this post's
`figures/` directory as the writeup is assembled.
