# Demonstration of Thundering Herd in SST 

[Structural Simulation Toolkit](https://sst-simulator.org/) (SST) is a Discrete Event Simulation (DES) framework written in C++ and Python. Although SST has historically focused on simulation of High Performance Computing, the DES framework can be used in other scenarios. 

In this repo, the [thundering herd problem](https://en.wikipedia.org/wiki/Thundering_herd_problem) is modeled using SST. 


This demonstration of the thundering herd problem relies only on [SST-Core](https://github.com/sstsimulator/sst-core)


# Objectives
- [ ] identify minimum features for C++ components needed to create this problem
- [ ] identify minimum size of graph (links, components) to observe the issue
- [ ] identify metrics needed to identify the existence of the problem
- [ ] measure the metrics and demonstrate the detection of the problem
- [ ] use the metrics to identify the problem at various scales (e.g., 10 nodes, 100 nodes, 1000 nodes)

# Context

The intended audience for this documentation has basic familiar with use of SST, C++, Python, Makefiles.

Documentation should explain how the concept of Congestive Collapse is mapped to the SST model.
