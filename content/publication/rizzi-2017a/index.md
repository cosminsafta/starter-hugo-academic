---
title: "Exploring the Interplay of Resilience and Energy Consumption for a Task-Based Partial Differential Equations Preconditioner"
date: 2018-04-01
publishDate: 2018-04-01
authors: ["F. Rizzi", "K. Morris", "K. Sargsyan",  "P. Mycek", "C. Safta", "O. Le Matre", "O.M. Knio", "B.J. Debuschere"]
publication_types: ["2"]
abstract: "Task-based PDE preconditioner resilient to silent data corruptions (SDCs).Demonstrate excellent scalability and suitability to run at large scale.Demonstrate potential energy savings via dynamics voltage/frequency scaling.Demonstrate resilience to SDCs stemming from single and double bit-flips. We discuss algorithm-based resilience to silent data corruptions (SDCs) in a task-based domain-decomposition preconditioner for partial differential equations (PDEs). The algorithm exploits a reformulation of the PDE as a sampling problem, followed by a solution update through data manipulation that is resilient to SDCs. The implementation is based on a server-client model where all state information is held by the servers, while clients are designed solely as computational units. Scalability tests run up to 51K cores show a parallel efficiency greater than 90%. We use a 2D elliptic PDE and a fault model based on random single and double bit-flip to demonstrate the resilience of the application to synthetically injected SDC. We discuss two fault scenarios: one based on the corruption of all data of a target task, and the other involving the corruption of a single data point. We show that for our application, given the test problem considered, a four-fold increase in the number of faults only yields a 2% change in the overhead to overcome their presence, from 7% to 9%. We then discuss potential savings in energy consumption via dynamic voltage/frequency scaling, and its interplay with fault-rates, and application overhead."
featured: false
publication: "*Parallel Computing*"
doi: "10.1016/j.parco.2017.05.005"
---

