---
layout: publication
title: A Physics-Driven Artificial Agent for Online Time-Optimal Vehicle Motion Planning and Control
authors: 
  - Mattia Piccinini
  - Sebastiano Taddei
  - Matteo Larcher
  - Mattia Piazza
  - Francesco Biral
publication: IEEE Access
pub_type: "journal" # "journal", "conference", "workshop" or "poster"
year: 2023
doi: https://doi.org/10.1109/ACCESS.2023.3274836
video: xQ_T96IjGP8 #  false or youtube video id
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
#   - ARD
#   - Optimal Control
#   - Mattia Piccinini
#   - Sebastiano Taddei
#   - Matteo Larcher
#   - Mattia Piazza
#   - Francesco Biral
#   - IEEE Access
---

## Abstract

This paper presents a hierarchical framework with novel analytical and neural physics-driven models, to enable the online planning and tracking of minimum-time maneuvers, for a vehicle with partially-unknown parameters. We introduce a lateral speed prediction model for high-level motion planning with economic nonlinear model predictive control (E-NMPC). A low-level steering controller is developed with a novel feedforward-feedback physics-driven artificial neural network (NN). A longitudinal dynamic model is identified to tune a low-level speed-tracking controller. The high- and low-level control models are identified with an automatic three-step scheme, combining open-loop and closed-loop maneuvers to model the maximum acceleration G-G-v performance constraint for E-NMPC, and to capture the effect of the longitudinal acceleration on the lateral dynamics. The proposed framework is used in a simulation environment, for the online closed-loop control of a highly detailed sedan vehicle simulator, whose parameters are partially-unknown. Two different circuits are adopted to validate the approach, and a robustness analysis is performed by varying the vehicle mass and the load distribution. A minimum-time optimal control problem is solved offline and used for a comparison with the closed-loop results.
