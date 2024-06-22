---
title: "Enhancing Heterogeneous Computing Through OpenMP and GPU Graph"
collection: publications
permalink: /publication/DynamicCUDAGraph
excerpt: 'This paper proposes a mechanism to dynamically generate GPU graphs, such as CUDA graphs, based on OpenMP target offloading mechanism with the taskgraph framework. The work enhances the interoperability of OpenMP with other parallel programming models and improves the performance of OpenMP accelerator model.'
date: 2024-08-01
venue: 'International Conference on Parallel Processing'
paperurl: 'https://doi.org/10.1145/3673038.3673050'
citation: ' Yu, C., Royuela, S., Quiñones, E.: Enhancing heterogeneous computing through openmp and gpu graph. In: 53rd International Conference on Parallel Processing (2024).'
---

Modern computing platforms are increasingly heterogeneous, most
of them include accelerators such as GPU. OpenMP as the de-facto
standard to parallelize CPU applications, incorporates target con-
struct allowing users to offload work onto such accelerators, to
leverage the computing capability provided by these accelerators
while maintaining a simple, directive based programming style.
However, due to architectural differences between CPUs and GPUs,
OpenMP is not always able to exploit the latest computing opti-
mizations available on GPUs.
This work is based on a recent proposal to OpenMP: taskgraph.
With this, we aim to enable an efficient execution model available
on GPUs: the Graph framework. The latter is available on Nvidia
GPUs as CUDA Graph, and on AMD GPUs as HIP Graph. This
paper presents an implementation of a taskgraph to CUDA Graph
transformation on top of the LLVM compiler. This technique im-
proves unstructured target applications’ performance by exploiting
GPU more efficiently while delivering comparable performance
for structured target applications using embarrassingly parallel
kernels.