---
layout: talk
permalink: /talks/cudf-rapids-gpu-accelerated-dataframe-library
recordingconsent: true
talkid: RCYSDC
title: 'cuDF: RAPIDS GPU-Accelerated Dataframe Library'
track: science
nicetrack: "Science and Data"
type: talk

speakers:
- biography: 'Mark is a Principal System Software Engineer working on RAPIDS. Mark
    has twenty years of experience developing software for GPUs, ranging from graphics
    and games, to physically-based simulation, to parallel algorithms and high-performance
    computing. While a Ph.D. student at The University of North Carolina he recognized
    a nascent trend and coined a name for it: GPGPU (General-Purpose computing on
    Graphics Processing Units), and started GPGPU.org to provide a forum for those
    working in the field to share and discuss their work. Mark lives with his family
    in the MacKellar range in northern New South Wales.'
  name: Mark Harris

abstract: | 
      RAPIDS open-source software enables end-to-end data science and analytics pipelines to run entirely on GPUs. Key to RAPIDS is cuDF, a pandas-like Python data frame library with a high-performance CUDA C++ implementation. cuDF and RAPIDS enable large speedups for end-to-end data science using GPUs.
---

Modern data science demands interactive exploration and analysis of very large volumes of data. Data scientists rely on Python for solving problems of all scales, but the biggest workloads today run up against the limits of CPU performance and scalability. The massive parallelism, high memory bandwidth and high-speed interconnect of the latest GPUs provide a solution.

RAPIDS is a suite of open-source software libraries that enables end-to-end data science and analytics pipelines to run entirely on GPUs, providing end-to-end speedups of 50x or more. cuDF is a DataFrame manipulation library based on Apache Arrow, a columnar in-memory data format. cuDF provides a familiar pandas-like Python API to accelerate loading, filtering, and manipulation of data for model training data preparation.

cuDF accelerates data preparation workloads by keeping datasets in GPU memory and applying high-performance data-parallel CUDA C++ algorithms for everything from file parsing (CSV, Parquet, ORC, etc), decompression and loading, to selection, sorting, joining, grouping, and aggregation. Combined with the RAPIDS cuML machine learning library and the cuGraph GRAPH analytics library, data scientists can achieve impressive end-to-end speedups and perform interactive ETL and training on very large data sets.

In this talk I will provide an overview of RAPIDS with a focus on the features, functionality and software architecture of cuDF. I’ll share some performance results along with details of how cuDF combines Python and Apache Arrow with Numba, CUDA, and Dask to achieve high performance and scalability on massive workloads.
