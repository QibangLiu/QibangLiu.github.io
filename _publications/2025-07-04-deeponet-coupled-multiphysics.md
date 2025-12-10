---
title: "When Network Architecture Meets Physics: Deep Operator Learning for Coupled Multiphysics"
collection: publications
category: manuscripts
permalink: /publication/2025-07-04-deeponet-coupled-multiphysics
# excerpt: "This study evaluates DeepONet variants for coupled multiphysics problems, introducing a coupling-aware design principle for neural operators to achieve real-time surrogate modeling."
date: 2025-07-04
venue: "arXiv"
paperurl: "http://arxiv.org/abs/2507.03660"
doi: "10.48550/arXiv.2507.03660"
citation: 'Kobayashi, Kazuma; Park, Jaewan; Liu, Qibang; Koric, Seid; Abueidda, Diab; Alam, Syed Bahauddin (2025). &quot;When Network Architecture Meets Physics: Deep Operator Learning for Coupled Multiphysics.&quot; <i>arXiv</i>. <a href="http://arxiv.org/abs/2507.03660">arXiv:2507.03660</a>.'
---

<!-- ## Abstract
Scientific applications increasingly demand real-time surrogate models that can capture the behavior of strongly coupled multiphysics systems driven by multiple input functions, such as in thermomechanical and electro-thermal processes. While neural operator frameworks, such as Deep Operator Networks (DeepONets), have shown considerable success in single-physics settings, their extension to multiphysics problems remains poorly understood. In particular, the challenge of learning nonlinear interactions between tightly coupled physical fields has received little systematic attention.
This study addresses a foundational question: should the architectural design of a neural operator reflect the strength of physical coupling it aims to model? To answer this, we present the first comprehensive, architecture-aware evaluation of DeepONet variants across three regimes: single-physics, weakly coupled, and strongly coupled multiphysics systems. We consider a reaction–diffusion equation with dual spatial inputs, a nonlinear thermo-electrical problem with bidirectional coupling through temperature-dependent conductivity, and a viscoplastic thermo-mechanical model of steel solidification governed by transient phase-driven interactions.
Two operator-learning frameworks, the classical DeepONet and its sequential GRU-based extension, S-DeepONet, are benchmarked using both single-branch and multi-branch (MIONet-style) architectures. Our results demonstrate that architectural alignment with physical coupling is crucial: single-branch networks significantly outperform multi-branch counterparts in strongly coupled settings by leveraging shared latent representations, whereas multi-branch encodings offer advantages for decoupled or single-physics problems. Once trained, these surrogates achieve full-field predictions up to 1.8 × 10⁴ times faster than high-fidelity finite-element solvers, without compromising solution accuracy.
These findings introduce a coupling-aware design principle for neural operators, offering a practical foundation for deploying DeepONet-based surrogates in real-time digital twins, design optimization, and uncertainty quantification across complex multiphysics domains. -->
