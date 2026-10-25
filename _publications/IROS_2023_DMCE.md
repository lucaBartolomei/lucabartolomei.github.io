---
title: "Decentralised Multi-Robot Exploration Using Monte Carlo Tree Search"
collection: publications
category: conferences
permalink: /publication/IROS_2023_DMCE
excerpt: 'Addressing real-world challenges in inspection and surveying, the proposed DMCE strategy enables efficient, decentralized multi-robot exploration across unknown environments, outperforming state-of-the-art planners and greedy baselines with up to a 30% reduction in exploration time. Video available [here](https://youtu.be/3RfDq8wlnPI).'
date: 2022-10-23
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://lucabartolomei.github.io/files/IROS_2023_DMCE.pdf'
# citation: 'https://lucabartolomei.github.io/files/IROS_2023_DMCE.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/IROS_2023_DMCE.txt'
---

Autonomous robotic systems are useful in automating tasks such as inspection and surveying of unknown areas, where speed is often an important factor. In order to effectively reduce the time required to complete missions, an efficient exploration and coordination strategy is needed. In this spirit, this work proposes an approach based on the Monte Carlo Tree Search (MCTS) algorithm to guide robots during exploration missions. Our method first expands a search tree of possible actions from the robot's position towards unknown regions, and then selects the sequence of movements that best drive the exploration process forward with respect to a given reward function. The proposed approach, which is able to balance short- and long-term decision-making, is then extended to accommodate the presence of multiple robots, in a bid to push the efficiency of exploration further. Our method allows for the coordination of the robots' movements in a decentralized manner, relying on point-to-point communication. This results in an efficient strategy, which we refer to as Decentralized Monte Carlo Exploration (DMCE). The experimental results demonstrate that our pipeline outperforms a greedy exploration approach, as well as state-of-the-art planners, with up to 30% reduction in exploration times in a series of real-world maps.

Additional resources:
* [Open-source code](https://github.com/VIS4ROB-lab/dmce)
* [Video](https://youtu.be/3RfDq8wlnPI)
* [IROS Presentation](https://www.youtube.com/watch?v=SBbDH1m5dmE)
