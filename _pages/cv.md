---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
------
* Ph.D in HPC, Computer Science, Polytechnical University of Catalunya (UPC), 2024 (expected)
* M.S. in HPC and Cryptography, Sorbonne University, 2018
* B.S. in Computer Science, Sorbonne University (previously UPMC, Université Pierre et Marie Curie), 2016

Work experience
------
* Spring 2019 - Present: Ph.D. in HPC
  * UPC & BSC
  * Enhancement of OpenMP compiler and runtime. I mainly optimize the runtime library for OpenMP in LLVM. I also need to play with the LLVM compiler to do it. I also have some experience with OpenMP's implementation in GCC, but limited to the runtime system.

* June - Nov. 2023 : Intern
  * Collins Aerospace, Cork, Ireland
  * Assessing OpenMP on Critical Real-Time Embedded Systems: allow a task to run either on the CPU or on the GPU dynamically, according to the system's needs on the Jetson Orin NX SoC.

* Feb. 2019 - March 2020: Engineering
  * UPC & BSC
  * Configuration of an Adaptive Optics application featuring CUD (Performance bottleneck analysis, migration of the application from Intel X86 onto IBM Power9)

Skills
------
* C/C++ programming language
* Parallel programming:
  * Use OpenMP to parallelize legacy sequential HPC code. Use of profiler to pinpoint the bottleneck to further optimize.
  * Improve the OpenMP compiler and runtime to make the library more efficient.
  * GPU programming (mainly CUDA).
* Other Software skills, including but not limited to: scripting, git, debug, etc.

Publications
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Languages
-----
- A native Chinese speaker who can work with French and English (so called Full Professional Proficiency on Linkedin). I also speak Spanish (B1 level).

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
