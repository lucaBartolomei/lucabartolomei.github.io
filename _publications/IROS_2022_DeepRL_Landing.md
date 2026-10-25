---
title: "Autonomous Emergency Landing for Multicopters using Deep Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/IROS_2022_DeepRL_Landing
excerpt: 'We present an autonomous emergency landing pipeline for multicopters that handles critical failures, such as mechanical malfunctions, GPS jamming, or sudden battery drops. By leveraging semantic and depth representations, our policy achieves direct zero-shot transfer to the real world without requiring any additional fine-tuning. Video available [here](https://www.youtube.com/watch?v=p8tpLL7Q0GE).'
date: 2022-10-23
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://lucabartolomei.github.io/files/IROS_2022_DeepRL_Landing.pdf'
# citation: 'https://lucabartolomei.github.io/files/IROS_2022_DeepRL_Landing.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/IROS_2022_DeepRL_Landing.txt'
---

This work presents a pipeline for autonomous emergency landing for multicopters, such as rotary wing Unmanned Aerial Vehicles (UAVs), using deep Reinforcement Learning (RL). Mechanical malfunctions, strong winds, sudden battery life drops (e.g, due to cold weather), failure in localization or GPS jamming are not uncommon and all constitute emergency situations that require a UAV to abort its mission early and land as quickly as possible in the immediate vicinity. To this end, it is crucial for a UAV that is deployed in real missions to be able to detect a safe landing spot efficiently and proceed to land autonomously, avoiding damage to both its integrity and the surroundings. Driven by the advances in semantic segmentation and depth completion using machine learning, the proposed architecture uses deep RL to infer actions from semantic and depth information, flying the robot towards secure areas, while respecting safety constraints. Thanks to our robust training strategy and the choice of these mid-level representations as input to the RL agent, we show that our policy can directly transfer to the real world, without the need for any additional fine-tuning. In a series of challenging experiments both in simulation and with a real platform, we demonstrate that our planner guides a rotorcraft UAV to a safe landing spot up to 1.5 times faster and with double success rate than the state of the art (including a commercially available solution), paving the way towards realistically deployable UAVs.

Additional resources:
* [Open-source code](https://github.com/VIS4ROB-lab/multirotors_landing)
* [Video](https://www.youtube.com/watch?v=p8tpLL7Q0GE)
* [IROS Presentation](https://youtu.be/wOxZIGdsINs)
