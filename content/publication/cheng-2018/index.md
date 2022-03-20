---
title: "Distributionally Robust Optimization with Principal Component Analysis"
date: 2018-03-21
publishDate: 2018-03-21
authors: ["J. Cheng", "R.L.-Y. Chen", "H.N. Najm", "A. Pinar", "C. Safta", "J.-P. Watson"]
publication_types: ["2"]
abstract: "Distributionally robust optimization (DRO) is widely used because it offers a way to overcome the conservativeness of robust optimization without requiring the specificity of stochastic programming. On the computational side, many practical DRO instances can be equivalently (or approximately) formulated as semidefinite programming (SDP) problems via conic duality of the moment problem. However, despite being theoretically solvable in polynomial time, SDP problems in practice are computationally challenging and quickly become intractable with increasing problem sizes. We propose a new approximation method to solve DRO problems with moment-based ambiguity sets. Our approximation method relies on principal component analysis (PCA) for optimal lower dimensional representation of variability in random samples. We show that the PCA approximation yields a relaxation of the original problem and derive theoretical bounds on the gap between the original problem and its PCA approximation. Furthermore, an extensive numerical study shows the strength of the proposed approximation method in terms of solution quality and runtime. As examples, for distributionally robust conditional value-at-risk and risk-averse production-transportation problems the proposed PCA approximation using only 50% of the principal components yields near-optimal solutions (within 1%) with a one to two order of magnitude reduction in computation time."
featured: false
publication: "*SIAM Journal on Optimization*"
doi: "10.1137/16M1075910"
---

