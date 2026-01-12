---
title: "Efficient Implementation of Third-Order Tensor Methods with Adaptive Regularization for Unconstrained Optimization"
collection: publications
permalink: /publication/liu2025prerejection
excerpt: 'Authors: Coralia Cartis, Raphael Hauser, <strong>Yang Liu</strong>, Karl Welzel, Wenqi Zhu'
date: 2025-01-01
venue: 'Arxiv preprint'
paperurl: 'https://arxiv.org/abs/2501.00404'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
This paper dives into the numerical performance of high-order tensor methods, specifically comparing second- (p=2) and third-order (p=3) variants. We extend the interpolation-based updating strategy to the p≥3 case and introduce a novel pre-rejection technique to filter out bad candidates early. The identification of fundamental differences between the different local minima of the regularised subproblems for various orders and their consequential effects on algorithmic efficacy is discussed herein.

It turns out that with the right tweaks, AR3 variants can actually beat the standard second-order ones. We confirm this with benchmarks and provide an efficient, modular MATLAB package for anyone who wants to experiment with these algorithms.