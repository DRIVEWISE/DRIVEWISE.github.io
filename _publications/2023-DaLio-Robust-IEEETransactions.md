---
layout: publication
title: Robust and Sample-Efficient Estimation of Vehicle Lateral Velocity Using Neural Networks With Explainable Structure Informed by Kinematic Principles
authors: 
  - Mauro Da Lio
  - Mattia Piccinini
  - Francesco Biral
publication: IEEE Transactions on Intelligent Transportation Systems
pub_type: "journal" # "journal", "conference", "workshop" or "poster"
year: 2023
doi: https://doi.org/10.1109/TITS.2023.3303776
video: false #  false or youtube video id
slides: false
pdf: false # false no pdf true expected pdf with same name in the download folder
noimg: true # false or true to avoid image the publication page
logo: xplore_logo_white.svg
# categories:
#   - Autonomous Driving
#   - Advanced Driving Assistance Systems
#   - Artificial Intelligence
#   - Neural Network
#   - Optimal Control
#   - Journal
# tags:
#   - Artificial Agent
#   - Estimation
#   - Mattia Piccinini
#   - Mauro Da Lio
#   - Francesco Biral
#   - IEEE Xplore
#   - IEEE Transactions
#   - Intelligent Transportation Systems
author_profile: true
---

## Abstract <!-- omit in toc -->

This paper presents kinematics-structured neural networks (KS-NN) for the lateral speed estimation of vehicles. The internal structure of the networks is designed to incorporate the kinematic principles, enhancing the physical explainability and generalization capacity. Both the internal structure and training method are devised for better generalization performance. Various linear and nonlinear variants of our estimator are assessed for accuracy and robustness. The approach is validated using an openly accessible dataset with two race cars. The performance of the novel networks is evaluated against Luenberger, neural network, factor graph and Kalman filter estimators from the literature. In comparison with a Luenberger kinematic observer, our networks improve noise rejection, and overcome the well-known observability problem for low yaw rates. Compared to existing neural network estimators, our networks exhibit better generalization capacity, are more sample-efficient, require fewer learnable parameters, and their structure is physically explainable.
