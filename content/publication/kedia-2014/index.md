---
title: "A second-order coupled immersed boundary-SAMR construction for chemically reacting flow over a heat-conducting Cartesian grid-conforming solid"
date: 2014-04-04
publishDate: 2014-04-14
authors: ["K.S. Kedia", "C. Safta", "J. Ray", "H.N. Najm", "A.F. Ghoniem"]
publication_types: ["2"]
abstract: "In this paper, we present a second-order numerical method for simulations of reacting flow around heat-conducting immersed solid objects. The method is coupled with a block-structured adaptive mesh refinement (SAMR) framework and a low-Mach number operator-split projection algorithm. A “buffer zone” methodology is introduced to impose the solid–fluid boundary conditions such that the solver uses symmetric derivatives and interpolation stencils throughout the interior of the numerical domain; irrespective of whether it describes fluid or solid cells. Solid cells are tracked using a binary marker function. The no-slip velocity boundary condition at the immersed wall is imposed using the staggered mesh. Near the immersed solid boundary, single-sided buffer zones (inside the solid) are created to resolve the species discontinuities, and dual buffer zones (inside and outside the solid) are created to capture the temperature gradient discontinuities. The development discussed in this paper is limited to a two-dimensional Cartesian grid-conforming solid. We validate the code using benchmark simulations documented in the literature. We also demonstrate the overall second-order convergence of our numerical method. To demonstrate its capability, a reacting flow simulation of a methane/air premixed flame stabilized on a channel-confined bluff-body using a detailed chemical kinetics model is discussed."
featured: false
publication: "*Journal of Computational Physics*"
doi: "10.1016/j.jcp.2014.04.019"
---

