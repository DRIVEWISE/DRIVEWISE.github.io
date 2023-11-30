---
layout: publication
title: Fast Planning and Tracking of Complex Autonomous Parking Maneuvers With Optimal Control and Pseudo-Neural Networks
authors: Edoardo Pagot, Mattia Piccinini, Enrico Bertolazzi, Francesco Biral
publication: IEEE Access
pub_type: "journal" # "journal", "conference", "workshop" or "poster"
year: 2023
doi: https://doi.org/10.1109/ACCESS.2023.3330431
video: U2mRTzmFj9w #  false or youtube video id
slides: false
pdf: false # false no pdf true expected pdf with same name in the download folder
noimg: false # false or true to avoid image the publication page
# categories:
#   - Autonomous Driving
#   - Advanced Driving Assistance Systems
#   - Artificial Intelligence
#   - Optimal Control
#   - PINS
#   - Journal
# tags:
#   - Artificial Agent
#   - Parking
#   - Planning
#   - Optimal Control
#   - A* exploration
#   - Edoardo Pagot
#   - Mattia Piccinini
#   - Enrico Bertolazzi
#   - Francesco Biral
#   - IEEE Access
---

## Abstract <!-- omit in toc -->

This paper presents a framework to plan and execute autonomous parking maneuvers in complex parking scenarios. We formulate a minimum-time optimal control problem for trajectory planning, using an indirect optimal control approach. A novel smooth penalty function is devised for collision avoidance with optimal control, and an effective technique is adopted to compute an initial solution guess. The trajectory planning tasks are solved with low computational times, and a dense mesh is used to discretize the domain of the optimal control problems, resulting in accurate collision-free solutions. The planned parking maneuvers are tracked with an original pseudo-neural feedforward-feedback steering controller, which outperforms other techniques from the literature, and a feedback longitudinal controller, to drive a realistic 14-degree-of-freedom vehicle simulator. We validate the planning and tracking algorithms in challenging narrow parking scenarios, including reverse, parallel and angle parking, and unstructured environments. The framework robustness is assessed by changing the vehicle mass, the road adherence conditions, and by introducing measurement noise with realistic sensor models. A video of the trajectory planning and tracking results is available as supplementary material.
