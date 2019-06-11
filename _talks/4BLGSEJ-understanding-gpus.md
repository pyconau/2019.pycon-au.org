---
layout: talk
permalink: /talks/understanding-gpus
recordingconsent: true
talkid: BLGSEJ
title: Understanding GPUs
track: science
type: talk

speakers:
- biography: Varun has been a data scientist from before the title was coined, having
    been drawn to the mix of computer science and mathematics which had him programming
    GPUs and contributing to open source before they were cool. He's worked as a research
    engineer at various startups, tech companies, HFT firms and even parliament. While
    Varun programs in whatever language is necessary, Python is the one he dreams
    in and it came with him as he went from an OO advocate to the Church of Functional
    programming.
  name: Varun Nayyar

abstract: | 
      With torch and tensorflow we have begun to rely on GPUs to speed up computations. Deep Learning or not, GPUs can provide massive computation speed ups but it's not a panacea as NVIDIA would have you believe. Come along to understand how GPUs work and when to use them.
---

GPUs are very powerful and scale very well for many algorithms that have seen their uptake. However, understanding how GPUs work is helpful when doing any kind of computation. This talk goes through

- Understanding the CUDA computation model
- Thinking with CUDA -  matrix multiplication and summing an array
- grids of blocks of threads and warps
- syncing_threads, necessity and problems.
- Some CUDA example code
- Where GPUs fail:
    - heavily sequential algorithms - computations that require previous state results are significantly less efficient.
    - small data sets - the startup and transfer time costs remove any advantage
    - algorithms that require efficient data structures are difficult to port to GPUs (think DBScan)
