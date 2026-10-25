---
title: "Sweep-Your-Map: Efficient Coverage Planning for Aerial Teams in Large-Scale Environments"
collection: publications
category: manuscripts
permalink: /publication/RAL_2022_Sweep_Your_Map
excerpt: 'Addressing the strict battery and flight-time constraints of small drones in large-scale outdoor missions, our pipeline generates structured task partitions to achieve comprehensive visual coverage significantly faster than state-of-the-art exploration baselines. Video available [here](https://www.youtube.com/watch?v=DmOLZ0OPGzM).'
date: 2022-10-23
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 'https://lucabartolomei.github.io/files/RAL_2022_Sweep_Your_Map.pdf'
# citation: 'https://lucabartolomei.github.io/files/RAL_2022_Sweep_Your_Map.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/RAL_2022_Sweep_Your_Map.txt'
---

The efficiency of path-planning in robot navigation is crucial in tasks such as search-and-rescue and disaster surveying, but this is emphasized even more when considering multi-rotor aerial robots due to the limited battery and flight time. In this spirit, this work proposes an efficient, hierarchical planner to achieve comprehensive visual coverage of large-scale outdoor scenarios for small drones. Following an initial reconnaissance flight, a coarse map of the scene gets built in real-time. Then, regions of the map that were not appropriately observed are identified and grouped by a novel perception-aware clustering process that enables the generation of continuous trajectories (sweeps) to cover them efficiently. Thanks to this partitioning of the map into a set of tasks, we can generalize the planning to an arbitrary number of drones and perform a well-balanced workload distribution among them. We compare our approach against a state-of-the-art method for exploration and show the advantages of our pipeline in terms of efficiency for obtaining coverage in large environments.

Additional resources:
<!-- * [Open-source code](https://github.com/VIS4ROB-lab/dmce) -->
* [Video](https://www.youtube.com/watch?v=DmOLZ0OPGzM)
<!-- * [IROS Presentation](https://www.youtube.com/watch?v=SBbDH1m5dmE) -->
