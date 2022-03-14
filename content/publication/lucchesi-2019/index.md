---
title: "A hybrid, non-split, stiff/RKC, solver for advection–diffusion–reaction equations and its application to low-Mach number combustion"
date: 2018-10-03
publishDate: 2019-03-13
authors: ["M. Lucchesi", "H.H. Alzahrani", "C. Safta", "O.M. Knio"]
publication_types: ["2"]
abstract: "We present a new strategy to couple, in a non-split fashion, stiff integration schemes with explicit, extended-stability predictor-corrector methods. The approach is illustrated through the construction of a mixed scheme incorporating a stabilised second-order, Runge-Kutta-Chebyshev method and the CVODE stiff solver. The scheme is first applied to an idealised stiff reaction-diffusion problem that admits an analytical solution. Analysis of the computations reveals that as expected the scheme exhibits a second-order in time convergence, and that, compared to an operator-split construction, time integration errors are substantially reduced. The non-split scheme is then applied to model the transient evolution of a freely-propagating, 1D methane-air flame. A low-mach-number, detailed kinetics, combustion model, discretised in space using fourth-order differences, is used for this purpose. To assess the performance of the scheme, self-convergence tests are conducted, and the results are contrasted with computations performed using a Strang-split construction. Whereas both the split and non-split approaches exhibit second-order in time behaviour, it is seen that for the same value of the time step, the non-split approach exhibits significantly smaller time integration errors. On the other hand, the results also indicate that the application of the present non-split construction becomes attractive when large integration steps are used, due to numerical overhead."
featured: false
publication: "*Combustion Theory and Modelling*"
doi: "10.1080/13647830.2019.1600723"
---

