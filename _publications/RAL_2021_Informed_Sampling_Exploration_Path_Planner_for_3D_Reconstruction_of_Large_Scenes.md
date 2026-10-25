---
title: "Informed Sampling Exploration Path Planner for 3D Reconstruction of Large Scenes"
collection: publications
category: manuscripts
permalink: /publication/RAL_2021_Informed_Sampling_Exploration_Path_Planner_for_3D_Reconstruction_of_Large_Scenes
excerpt: 'Addressing MAV computational and energy constraints, our frontier-based informed sampling approach streamlines viewpoint evaluation to accelerate autonomous exploration, outperforming state-of-the-art planners in both exploration speed and final 3D reconstruction quality. Video available [here](https://www.youtube.com/watch?v=QR3Ay8AUQE8&feature=youtu.be).'
date: 2021-09-27
venue: 'IEEE Robotics and Automation Letters (RA-L)'
paperurl: 'https://lucabartolomei.github.io/files/RAL_2021_Informed_Sampling_Exploration_Path_Planner_for_3D_Reconstruction_of_Large_Scenes.pdf'
# citation: 'https://lucabartolomei.github.io/files/RAL_2021_Informed_Sampling_Exploration_Path_Planner_for_3D_Reconstruction_of_Large_Scenes.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/RAL_2021_Informed_Sampling_Exploration_Path_Planner_for_3D_Reconstruction_of_Large_Scenes.txt'
---

As vision-based navigation of small aircraft has been demonstrated to reach relative maturity, research into effective path-planning algorithms to complete the loop of autonomous navigation has been booming. Although the literature has seen some impressive works in this area, efficient path-planning that can be used in tasks such as inspection and coverage is still an open problem. In this spirit, this letter presents an online path-planning algorithm for fast exploration and 3D reconstruction of a previously unknown area of interest. Micro Aerial Vehicles (MAVs) are an ideal candidate for this task due to their maneuverability, but their limited computational power and endurance require efficient planning strategies. Popular sampling-based methods randomly sample the MAV's configuration space and evaluate viewpoints according to their expected information gain. Most often, however, valuable resources are spent on information gain calculations of unpromising viewpoints. This letter proposes a novel informed sampling approach that leverages surface frontiers to sample viewpoints only where high information gain is expected, leading to faster exploration. We study the impact of informed sampling in a wide range of photo-realistic scenes, and we show that our approach outperforms state-of-the-art exploration path planners in terms of both speed and reconstruction quality.

Additional resources:
<!-- * [Open-source code](https://github.com/VIS4ROB-lab/dmce) -->
* [Video](https://www.youtube.com/watch?v=QR3Ay8AUQE8&feature=youtu.be)
<!-- * [IROS Presentation](https://www.youtube.com/watch?v=SBbDH1m5dmE) -->
