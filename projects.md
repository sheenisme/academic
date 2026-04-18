---
layout: page
permalink: /projects/index.html
title: Projects
---

# Projects
This page collects an incomplete list of research and engineering projects Guanghui Song has contributed to. Some have public repositories; others are company-maintained or remain private while a paper or release is in preparation.

## PrecTuner
![prectuner](/academic/images/prectuner.jpg)
We present a holistic approach – [*PrecTuner*](https://github.com/sheenisme/lnlamp) – by closely coupling the code generator and the autotuner via only one parameter *r* . Initialized by automatically sampled values, *r* is first used to generate several code variants in the polyhedral model, combining this optimization with loop transformations. These code variants are then used to solve a performance model expressed in terms of *r* , possibly under a quality degradation budget. The value of *r*  that produces the best-performing mixed-precision code is finally predicted without evaluating all code variants.

## AutoPoly
**AutoPoly** is an architecture-aware polyhedral scheduling prototype built on MLIR (active development). The codebase is **not open-sourced yet**; a public repository will be linked here once it is released.

Technically, AutoPoly lifts affine kernels into polyhedral SCoPs, builds call-tree- and dependence-aware graphs, and maps user-selected targets to backend scheduling options (including a CGRA-oriented path on ISL/PPCG with validity, coincidence, and proximity constraints, wavefront and tiling reshaping, and mesh-friendly marks for downstream codegen). A unified CLI/Python driver (`autopoly`) automates LLVM/MLIR toolchain detection, runs scheduling, lowers MLIR to LLVM IR, and drives end-to-end build and test flows with configurable pass pipelines.

## Early Projects
- [Fcc compiler](https://github.com/THeWakeSystems/fcc.git) is based on LLVM, adding internal IP to the latest open source compiler, designing a new middle layer to load more program information, breaking the independence of each optimization tool and choosing profiling independently to achieve program optimization for multi-core parallelization and heterogeneous systems.
- [Weekly_ws](https://github.com/sheenisme/weekly_ws.git) is a set of OKR weekly report system specially developed for Weisheng Company, which can realise the management of OKR for all members of the whole company.
- [JEE](https://github.com/sheenisme/JEEBigHomework) is a simple template site based on JAVA development, you can carry out simple user management, inbound and outbound management and other common operations.
