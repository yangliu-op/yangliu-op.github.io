---
title: "A MINRES-based Linesearch Algorithm for Nonconvex Optimization with Non-positive Curvature Detection"
collection: publications
permalink: /publication/zeng2026quasi1
excerpt: 'Authors: Hanfeng Zeng, <strong>Yang Liu</strong>, Wenqing Ouyang, Andre Milzarek'
date: 2025-01-04
venue: 'Arxiv preprint'
paperurl: 'https://arxiv.org/abs/2601.01575'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
We propose a MINRES-based Newton-type algorithm for unconstrained nonconvex problems that leverages second-order and non-positive curvature (NPC) information. The derivation of comprehensive asymptotic convergence properties regarding the Kurdyka-Łojasiewicz inequality are primarily achieved by the integration of proper regularization techniques.

Basically, this thing is really good at dodging strict saddle points! We prove that the algorithm converges to second-order critical points and achieves fast local superlinear convergence under the Polyak-Łojasiewicz condition. Experiments on CUTEst and deep auto-encoders show it works like a charm.