---
title: "OpenMP to CUDA Graphs: A Compiler-Based Transformation to Enhance the Programmability of NVIDIA Devices"
collection: publications
permalink: /publication/OpenMP-to-CUDA
excerpt: 'This paper presents a novel compiler transformation technique that automatically transforms OpenMP code into CUDA graphs, combining the benefits of programmability of a high-level programming model such as OpenMP, with the performance benefits of a low-level programming model such as CUDA.'
date: 2020-10-01
venue: 'International Workshop on Software and Compilers for Embedded Systems'
paperurl: 'https://dl.acm.org/doi/10.1145/3378678.3391881'
citation: 'Yu, C., Royuela, S., Quiñones, E.: OpenMP to CUDA Graphs: A Compiler-Based
Transformation to Enhance the Programmability of NVIDIA Devices. In: Proceed-
ings of the 23th International Workshop on Software and Compilers for Embedded
Systems. p. 42–47. SCOPES ’20, Association for Computing Machinery (2020)'
---

Heterogeneous computing is increasingly being used in a diversity of computing systems, ranging from HPC to the real-time embed- ded domain, to cope with the performance requirements. Due to the variety of accelerators, e.g., FPGAs, GPUs, the use of high-level par- allel programming models is desirable to exploit the performance capabilities of them, while maintaining an adequate productivity level. In that regard, OpenMP is a well-known high-level program- ming model that incorporates powerful task and accelerator models capable of efficiently exploiting structured and unstructured par- allelism in heterogeneous computing. This paper presents a novel compiler transformation technique that automatically transforms OpenMP code into CUDA graphs, combining the benefits of pro- grammability of a high-level programming model such as OpenMP, with the performance benefits of a low-level programming model such as CUDA. Evaluations have been performed on two NVIDIA GPUs from the HPC and embedded domains, i.e., the V100 and the Jetson AGX respectively.
