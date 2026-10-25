---
title: "T-PRM: Temporal Probabilistic Roadmap for Path Planning in Dynamic Environments"
collection: publications
category: conferences
permalink: /publication/IROS_2022_TPRM
excerpt: 'Temporal-PRM maintains the core advantages of traditional PRM—such as multi-query capabilities and smooth path generation—while enabling collision-free navigation in highly dynamic, cluttered environments, operating in real time onboard a flying robot. Video available [here](https://www.youtube.com/watch?v=Eh6brn_dVlU&t).'
date: 2022-10-23
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://lucabartolomei.github.io/files/IROS_2022_TPRM.pdf'
# citation: 'https://lucabartolomei.github.io/files/IROS_2022_TPRM.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/IROS_2022_TPRM.txt'
---

Sampling-based motion planners are widely used in robotics due to their simplicity, flexibility and computational efficiency. However, in their most basic form, these algorithms operate under the assumption of static scenes and lack the ability to avoid collisions with dynamic (i.e. moving) obstacles. This raises safety concerns, limiting the range of possible applications of mobile robots in the real world. Motivated by these challenges, in this work we present Temporal-PRM, a novel sampling-based path-planning algorithm that performs obstacle avoidance in dynamic environments. The proposed approach extends the original Probabilistic Roadmap (PRM) with the notion of time, generating an augmented graph-like structure that can be efficiently queried using a time-aware variant of the A* search algorithm, also introduced in this paper. Our design maintains all the properties of PRM, such as the ability to perform multiple queries and to find smooth paths, while circumventing its downside by enabling collision avoidance in highly dynamic scenes with a minor increase in the computational cost. Through a series of challenging experiments in highly cluttered and dynamic environments, we demonstrate that the proposed path planner outperforms other state-of-the-art sampling-based solvers. Moreover, we show that our algorithm can run onboard a flying robot, performing obstacle avoidance in real time.

Additional resources:
* [Open-source code](https://github.com/VIS4ROB-lab/t_prm)
* [Video](https://www.youtube.com/watch?v=Eh6brn_dVlU&t)
* [IROS Presentation](https://youtu.be/dPXfDjdck20)
