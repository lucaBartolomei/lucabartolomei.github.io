---
title: "Perception-aware Path Planning for UAVs using Semantic Segmentation"
collection: publications
category: conferences
permalink: /publication/IROS_2020_Active_perception
excerpt: 'This paper presents a perception-aware path-planning pipeline for UAVs that leverages semantic segmentation to avoid texture-less or problematic areas, such as bodies of water, that degrade monocular VIO state estimation, actively steering the robot toward perceptually informative regions. Video available [here](https://youtu.be/vxAXimQ9CGU).'
date: 2020-10-25
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'https://lucabartolomei.github.io/files/IROS_2020_Active_perception.pdf'
# citation: 'https://lucabartolomei.github.io/files/IROS_2020_Active_perception.txt'
bibtexurl: 'https://lucabartolomei.github.io/files/IROS_2020_Active_perception.txt'
---

In this work, we present a perception-aware path-planning pipeline for Unmanned Aerial Vehicles (UAVs) for navigation in challenging environments. The objective is to reach a given destination safely and accurately by relying on monocular camera-based state estimators, such as Keyframe-based Visual-Inertial Odometry (VIO) systems. Motivated by the recent advances in semantic segmentation using deep learning, our path-planning architecture takes into consideration the semantic classes of parts of the scene that are perceptually more informative than others. This work proposes a planning strategy capable of avoiding both texture-less regions and problematic areas, such as lakes and oceans, that may cause large drift or failures in the robot's pose estimation, by using the semantic information to compute the next best action with respect to perception quality. We design a hierarchical planner, composed of an A* path-search step followed by B-Spline trajectory optimization. While the A* steers the UAV towards informative areas, the optimizer keeps the most promising landmarks in the camera's field of view. We extensively evaluate our approach in a set of photo-realistic simulations, showing a remarkable improvement with respect to the state-of-the-art in active perception.

Additional resources:
* [Video](https://youtu.be/vxAXimQ9CGU)
* [IROS Presentation](https://www.youtube.com/watch?v=Pl6M5tiSPpc)
