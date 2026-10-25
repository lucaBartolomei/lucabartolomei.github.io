---
title: "Semantic-aware Active Perception for UAVs using Deep Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/IROS_2021_RL_based_Active_Perception
excerpt: 'We present a semantic-aware path-planning pipeline for UAVs that uses deep reinforcement learning to evaluate the perceptual informativeness of visible semantic classes. By training on semantic cues across non-photorealistic, randomly generated scenes, the deep policy network successfully generalizes to unseen environments while guiding the UAV away from perceptually degraded regions. Video available [here](https://www.youtube.com/watch?v=RaO3whUBVnc).'
date: 2021-09-27
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://lucabartolomei.github.io/files/IROS_2021_RL_based_Active_Perception.pdf'
# citation: 'https://lucabartolomei.github.io/files/IROS_2021_RL_based_Active_Perception.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/IROS_2021_RL_based_Active_Perception.txt'
---

This work presents a semantic-aware path-planning pipeline for Unmanned Aerial Vehicles (UAVs) using deep reinforcement learning for vision-based navigation in challenging environments. Driven by the maturity of works in semantic segmentation, the proposed path-planning architecture uses reinforcement learning to distinguish the parts of the scene that are perceptually more informative using semantic cues, in effect guiding more robust, repeatable, and accurate navigation of the UAV to the predefined goal destination. Assuming that the UAV performs vision-based state estimation, such as keyframe-based visual odometry, and semantic segmentation onboard, the proposed deep policy network continuously evaluates the optimal relative perceptual informativeness of each semantic class in view. A perception-aware path planner uses these informativeness values to perform trajectory optimization in order to generate the next best action with respect to the current state and the perception quality of the surroundings, essentially guiding the UAV to avoid flying over perceptually degraded regions. Thanks to the use of semantic cues, the policy can be trained in a large number of non-photorealistic randomly-generated scenes, and results to an architecture that is generalizable to environments with the same semantic classes, independently of their visual appearance. Extensive evaluations on challenging, photorealistic simulations reveal a remarkable improvement in robustness and success rate with the proposed approach over the state of the art in active perception.

Additional resources:
* [Video](https://www.youtube.com/watch?v=RaO3whUBVnc)
* [IROS Presentation](https://youtu.be/tDvvdlv7Feg)
