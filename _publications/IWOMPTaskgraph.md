---
title: "Enhancing OpenMP Tasking Model: Performance and Portability"
collection: publications
permalink: /publication/IWOMPTaskgraph
excerpt: 'In this work, we propose to include the concept of Task DependencyGraph (TDG) in the specification by introducing a new clause, namely taskgraph.'
date: 2021-10-01
venue: 'International Workshop on OpenMP'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-85262-7_3'
citation: 'Yu, C., Royuela, S., Quiñones, E. (2021). Enhancing OpenMP Tasking Model: Performance and Portability. In: McIntosh-Smith, S., de Supinski, B.R., Klinkenberg, J. (eds) OpenMP: Enabling Massive Node-Level Parallelism. IWOMP 2021. Lecture Notes in Computer Science(), vol 12870. Springer, Cham. https://doi.org/10.1007/978-3-030-85262-7_3'
---

OpenMP, as the de-facto standard programming model in symmetric multiprocessing for HPC, has seen its performance boosted continuously by the community, either through implementation enhancements or specification augmentations. Furthermore, the language has evolved from a prescriptive nature, as defined by the thread-centric model, to a descriptive behavior, as defined by the task-centric model. However, the overhead related to the orchestration of tasks is still relatively high. Applications exploiting very fine-grained parallelism and systems with a large number of cores available might fail on scaling.

In this work, we propose to include the concept of Task Dependency Graph (TDG) in the specification by introducing a new clause, named taskgraph, attached to task or target directives. By design, the TDG allows alleviating the overhead associated with the OpenMP tasking model, and it also facilitates linking OpenMP with other programming models that support task parallelism. According to our experiments, a GCC implementation of the taskgraph is able to significantly reduce the execution time of fine-grained task applications and increase their scalability with regard to the number of threads.