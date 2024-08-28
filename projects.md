---
layout: page
permalink: /projects/index.html
title: Projects
---

# Projects
This page collects a(n incomplete) list of open-source projects that Guanghui Song has ever involved in or currently participates in. Some of them are maintained by companies and some are repositories of research projects.

## PrecTuner
![prectuner](/academic/images/prectuner.jpg)
We presents a holistic approach – [*PrecTuner*](https://gitee.com/link?target=https%3A%2F%2Fgithub.com%2Fsheenisme%2Flnlamp.git) – by closely coupling the code generator and the autotuner via only one parameter *r* . Initialized by automatically sampled values, *r* is first used to generate several code variants in the polyhedral model, combining this optimization with loop transformations. These code variants are then used to solve a performance model expressed in terms of *r* , possibly under a quality degradation budget. The value of *r*  that produces the best-performing mixed-precision code is finally predicted without evaluating all code variants.

## Early Projects
- [Fcc compiler](https://github.com/THeWakeSystems/fcc.git) is based on LLVM, adding internal IP to the latest open source compiler, designing a new middle layer to load more program information, breaking the independence of each optimization tool and choosing profiling independently to achieve program optimization for multi-core parallelization and heterogeneous systems.
- [Weekly_ws](https://github.com/sheenisme/weekly_ws.git) is a set of OKR weekly report system specially developed for Weisheng Company, which can realise the management of OKR for all members of the whole company.
- [JEE](https://github.com/sheenisme/JEEBigHomework) is a simple template site based on JAVA development, you can carry out simple user management, inbound and outbound management and other common operations.
