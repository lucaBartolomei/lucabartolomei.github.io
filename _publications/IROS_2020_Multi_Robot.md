---
title: "Multi-robot Coordination with Agent-Server Architecture for Autonomous Navigation in Partially Unknown Environments"
collection: publications
category: conferences
permalink: /publication/IROS_2020_Multi_Robot
excerpt: 'A server-agent system architecture for multi-robot autonomous navigation in partially unknown environments is presented, where computationally demanding tasks like global mapping and path planning are outsourced to a central server, while agents handle local pose estimation and obstacle avoidance onboard. Video available [here](https://www.youtube.com/watch?v=BlFbiuV-d10).'
date: 2020-10-25
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://lucabartolomei.github.io/files/IROS_2020_Multi_Robot.pdf'
# citation: 'https://lucabartolomei.github.io/files/IROS_2020_Multi_Robot.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/IROS_2020_Multi_Robot.txt'
---

In this work, we present a system architecture to enable autonomous navigation of multiple agents across user-selected global interest points in a partially unknown environment. The system is composed of a server and a team of agents, here small aircrafts. Leveraging this architecture, computation-ally demanding tasks, such as global dense mapping and global path planning can be outsourced to a potentially powerful central server, limiting the onboard computation for each agent to local pose estimation using Visual-Inertial Odometry (VIO) and local path planning for obstacle avoidance. By assigning priorities to the agents, we propose a hierarchical multi-robot global planning pipeline, which avoids collisions amongst the agents and computes their paths towards the respective goals. The resulting global paths are communicated to the agents and serve as reference input to the local planner running onboard each agent. In contrast to previous works, here we relax the common assumption of a previously mapped environment and perfect knowledge about the state, and we show the effectiveness of the proposed approach in photo-realistic simulations with up to four agents operating in an industrial environment.

Additional resources:
* [Open-source code](https://github.com/v4rl-ucy/multi_robot_coordination)
* [Video](https://www.youtube.com/watch?v=BlFbiuV-d10)
* [IROS Presentation](https://www.youtube.com/watch?v=ATQiTsbaSOw)
