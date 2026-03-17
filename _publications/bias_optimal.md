---
layout: default
title: "Bias-Optimal Bounds for SGD: A Computer-Aided Lyapunov Analysis"
authors:
  - name: D. Cortild
    url: https://daniel.cortild.com/
  - name: L. Ketels
    url:
  - name: G. Garrigos
    url: https://guillaume-garrigos.com/
  - name: J. Peypouquet
    url: https://sites.google.com/rug.nl/peypouquet/home
publication: arXiv preprint arXiv:2505.17965
year: 2025
doi: http://dx.doi.org/XX.XXX/
arxiv: https://arxiv.org/pdf/2505.17965?
abstract: >
  The non-asymptotic analysis of Stochastic Gradient Descent (SGD) typically yields bounds that decompose into a bias term and a variance term. In this work, we focus on the bias component and study the extent to which SGD can match the optimal convergence behavior of deterministic gradient descent. Assuming only (strong) convexity and smoothness of the objective, we derive new bounds that are bias-optimal, in the sense that the bias term coincides with the worst-case rate of gradient descent. Our results hold for the full range of constant step-sizes γL ∈(0,2), including critical and large step-size regimes that were previously unexplored without additional variance assumptions. The bounds are obtained through the construction of a simple Lyapunov energy whose monotonicity yields sharp convergence guarantees. To design the parameters of this energy, we employ the Performance Estimation Problem framework, which we also use to provide numerical evidence for the optimality of the associated variance terms.

bibtex: |
  @article{cortild_new_2025,
    title = {{Bias-Optimal Bounds for SGD: A Computer-Aided Lyapunov Analysis}},
    author = {Cortild, Daniel and Ketels, Lucas and Peypouquet, Juan and Garrigos, Guillaume},
    month = may,
    year = {2025},
    journal = {arXiv preprint arXiv:2505.17965}
  }


---