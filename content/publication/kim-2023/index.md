---
title: "TChem: A performance portable parallel software toolkit for complex kinetic mechanisms"
date: 2022-11-30
publishDate: 2022-12-30
authors: ["K. Kim", "O. Díaz-Ibarra", "H. Najm", "J. Zador", "C. Safta"]
publication_types: ["2"]
abstract: "We present TChem, a performance portable software toolkit to enable the analysis of complex kinetic mechanisms. The software provides tools for gas-phase and surface chemistry, thermodynamic properties, and implements formulations for several canonical reactor models. Analytical derivatives necessary to construct Jacobian matrices corresponding to all implemented functionalities are available through automatic differentiation. TChem uses the Kokkos framework to achieve portability across multiple heterogeneous computing platforms with a single version of the code. We implement a hierarchical parallelism framework to enable efficient chemical source term and thermodynamic property evaluations over the number of samples assigned to the local computing device. We analyze parallel efficiency results extracted from test cases for thermodynamic properties, source terms, and Jacobians evaluations on Intel Xeon CPUs and NVIDIA Volta GPUs."
featured: false
publication: "*Computer Physics Communications*"
doi: "10.1016/j.cpc.2022.108628"
---

