---
title: "Partial differential equations preconditioner resilient to soft and hard faults"
date: 2017-01-29
publishDate: 2017-01-29
authors: ["F. Rizzi", "K. Morris", "K. Sargsyan",  "P. Mycek", "C. Safta", "O. Le Matre", "O. Knio", "B.J. Debuschere"]
publication_types: ["2"]
abstract: "We present a domain-decomposition-based preconditioner for the solution of partial differential equations (PDEs) that is resilient to both soft and hard faults. The algorithm reformulates the PDE as a sampling problem, followed by a solution update through data manipulation that is resilient to both soft and hard faults. This reformulation allows us to recast the problem as a set of independent tasks, and exploit data locality to reduce global communication. We discuss two different parallel implementations: (a) a single program multiple data (SPMD) version based on a one-to-one mapping between subdomain and MPI processes responsible for both state and computation; and (b) an asynchronous server–client implementation where all state information is held by the servers and clients are designed solely as computational units. We present a scalability comparison of both implementations under nominal conditions, showing efficiency within ~80% for up to 12,000 cores. We present a resilience analysis under different fault scenarios based on the server–client implementation. This framework provides resiliency to hard faults such that if a client crashes, it stops asking for work, and the servers simply distribute the work among all of the other clients alive. Erroneous subdomain solves (e.g. due to soft faults) appear as corrupted data, which is either rejected if that causes a task to fail, or is seamlessly filtered out during the regression stage through a suitable noise model. Three different types of faults are modeled: hard faults modeling nodes (or clients) crashing; soft faults occurring during the communication of the tasks between server and clients; and soft faults occurring during task execution. We demonstrate the resiliency of the approach for a 2D elliptic PDE, and explore the effect of the faults at various failure rates."
featured: false
publication: "*The International Journal of High Performance Computing Applications*"
doi: "10.1177/1094342016684975"
---

