---
title: "Reverse-mode differentiation in arbitrary tensor network format: with application to supervised learning"
date: 2021-03-01
publishDate: 2022-05-01
authors: ["A.A. Gorodetsky", "C. Safta", "J.D. Jakeman"]
publication_types: ["2"]
abstract: "This paper describes an efficient reverse-mode differentiation algorithm for contraction op- erations for arbitrary and unconventional tensor network topologies. The approach lever- ages the tensor contraction tree of Evenbly and Pfeifer (2014), which provides an instruction set for the contraction sequence of a network. We show that this tree can be efficiently leveraged for differentiation of a full tensor network contraction using a recursive scheme that exploits (1) the bilinear property of contraction and (2) the property that trees have a single path from root to leaves. While differentiation of tensor-tensor contraction is already possible in most automatic differentiation packages, we show that exploiting these two ad- ditional properties in the specific context of contraction sequences can improve efficiency. Following a description of the algorithm and computational complexity analysis, we inves- tigate its utility for gradient-based supervised learning for low-rank function recovery and for fitting real-world unstructured datasets. We demonstrate improved performance over alternating least-squares optimization approaches and the capability to handle heteroge- neous and arbitrary tensor network formats. When compared to alternating minimization algorithms, we find that the gradient-based approach requires a smaller oversampling ratio (number of samples compared to number model parameters) for recovery. This increased efficiency extends to fitting unstructured data of varying dimensionality and when em- ploying a variety of tensor network formats. Here, we show improved learning using the hierarchical Tucker method over the tensor-train in high-dimensional settings on a number of benchmark problems."
featured: false
publication: "*Journal of Machine Learning Research*"
doi: "http://jmlr.org/papers/v23/21-0225.html"
---

