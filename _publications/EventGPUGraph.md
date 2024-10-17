---
title: "Event-Based OpenMP Tasks for Time-Sensitive GPU-Accelerated Systems"
collection: publications
permalink: /publication/EventGPUGraph
excerpt: 'This paper allows users to statically create GPU graphs with external events conveniently with OpenMP. It is based on the taskgraph construct introduced in OpenMP 6.0. To evaluate the performance of framework, we carried out the experiments with real-life Cyber-Physical Systems (CPS) that incorporate camera as external event triggerer.'
date: 2024-09-24
venue: 'International Workshop on OpenMP'
paperurl: 'https://doi.org/10.1007/978-3-031-72567-8_3'
citation: 'Cetre, C., Yu, C., Royuela, S., Barrere, R., Quiñones, E., Gratadour, D. (2024). Event-Based OpenMP Tasks for Time-Sensitive GPU-Accelerated Systems.'
---

The throughput-centric design of GPUs poses challenges when 
integrating them into time-sensitive applications. Nevertheless, 
modern GPU architectures and software have recently evolved, making 
it possible to minimize overheads and interference along the 
critical path through advanced mechanisms, such as GPU graphs, 
while sustaining high throughput. However, GPU vendors provide 
programming ecosystems specific to their products, raising concerns 
about code portability. Hence, there is a need for a 
hardware-agnostic API capable of managing time-sensitive 
GPU-accelerated pipelines. In this context, we propose integrating 
event-based synchronizations into the high-level OpenMP programming 
model to, in combination with GPU graphs, notably reduce 
interference and overheads over the critical path. This work 
showcases how this combination offers significant performance 
improvements and time consistency. We also enable portability 
across several vendor ecosystems and demonstrate our work on a set 
of representative applications for cyber-physical systems. 
According to our experiments, we measured a maximum jitter below 20 
μs, representing less than 5% of time variation.