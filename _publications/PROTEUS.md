---
title: "PROTEUS: Proactive Latency-Constrained Enhanced Ubiquitous Surveillance"
collection: publications
permalink: /publication/proteus
excerpt: 'In this paper we introduce a system for robotic swarms for autonomous surveillance to cover an entire area and meet tight communication-latency budgets using a computationally efficient approach.'
date: 2026-06-03
venue: '2026 24th International Symposium on Modeling and Optimization in Mobile, Ad Hoc, and Wireless Networks (WiOpt)'
paperurl: 'https://doi.org/10.23919/WiOpt71098.2026.11568238'
citation: 'G. Singh, A. Ghosh, and D. Roy, "PROTEUS: Proactive Latency-Constrained Enhanced Ubiquitous Surveillance," in Proc. 2026 24th International Symposium on Modeling and Optimization in Mobile, Ad Hoc, and Wireless Networks (WiOpt), Columbus, OH, USA, 2026, pp. 1–8, doi: 10.23919/WiOpt71098.2026.11568238.'
---

Deploying robotic swarms for autonomous surveillance is often bottlenecked by the need to cover an entire area and meet tight communication-latency budgets using a computationally efficient approach. We introduce PROTEUS, a modular, computationally efficient framework that achieves both objectives through three coordinated components: (i) a Multi-Agent Reinforcement Learning (MARL) algorithm for efficient environmental exploration and collecting a small set of "seed" latency measurements; (ii) a novel sampling based imputation method that accurately generates latency maps for all possible leader positions from these sparse samples; and (iii) a constrained submodular optimization approach to determine the optimal, latency-constrained leader and follower placements that guarantee full coverage with the minimum number of robots. We validate PROTEUS through extensive experiments on a physical testbed using Limobot and Turtlebot4 robots. Our results show that by applying a latency-constrained greedy placement strategy, PROTEUS successfully identifies optimal deployments that achieve full coverage. For instance, at a latency constraint of 1.90 milliseconds (ms), our framework finds a leader position that provides 100% area coverage with only four follower robots. Furthermore, our framework outperforms the state-of-the-art by providing near-100% coverage with up to 62% lower communication latency. These results demonstrate that PROTEUS can serve as a practical foundation for efficient network-aware swarm deployments in high-stakes environments.
    
