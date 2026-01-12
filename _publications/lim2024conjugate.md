---
title: "Conjugate Direction Methods Under Inconsistent Systems"
collection: publications
permalink: /publication/lim2024conjugate
excerpt: 'Authors: Alexander Lim, <strong>Yang Liu</strong>, Fred Roosta'
date: 2024-01-22
venue: 'Arxiv preprint'
paperurl: 'https://arxiv.org/abs/2401.11714'
# citation: ''
---

Everyone uses Conjugate Gradient (CG), while Conjugate Residual (CR) is often ignored. We investigate these methods for inconsistent systems (where Ax=b has no solution). The demonstration that small modifications to the original algorithms allow for the pseudo-inverse solution and that CR is essentially equivalent to the minimum residual method proposed by Paige and Saunders in such contexts is presented.

We ran a bunch of numerical experiments to test stability. Surprisingly, while people usually trust CG, we show that in these cases, it can be a total disaster! It exhibits significant numerical instability, sometimes bordering on catastrophe, unlike CR.