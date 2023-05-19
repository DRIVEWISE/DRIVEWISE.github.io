---
title: "Publications"
layout: single
permalink: /Publications/
image_path: ../_images/_img_papers/
# classes: wide
toc: true
---

# Journal Papers

## A Physics-Driven Artificial Agent for Online <br/>  Time-Optimal Vehicle Motion Planning and Control

*Mattia Piccinini, Sebastiano Taddei, Matteo Larcher, Mattia Piazza, Francesco Biral*

<iframe width="1239" height="697" src="https://www.youtube.com/embed/xQ_T96IjGP8" title="A Physics-Driven Artificial Agent for Online Time-Optimal VehicleMotion Planning and Control" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Abstract

This paper presents a hierarchical framework with novel analytical and neural physics-driven models, to enable the online planning and tracking of minimum-time maneuvers, for a vehicle with partially-unknown parameters. We introduce a lateral speed prediction model for high-level motion planning with economic nonlinear model predictive control (E-NMPC). A low-level steering controller is developed with a novel feedforward-feedback physics-driven artificial neural network (NN). A longitudinal dynamic model is identified to tune a low-level speed-tracking controller. The high- and low-level control models are identified with an automatic three-step scheme, combining open-loop and closed-loop maneuvers to model the maximum acceleration G-G-v performance constraint for E-NMPC, and to capture the effect of the longitudinal acceleration on the lateral dynamics. The proposed framework is used in a simulation environment, for the online closed-loop control of a highly detailed sedan vehicle simulator, whose parameters are partially-unknown. Two different circuits are adopted to validate the approach, and a robustness analysis is performed by varying the vehicle mass and the load distribution. A minimum-time optimal control problem is solved offline and used for a comparison with the closed-loop results.

#### Publication Details

**Journal**: IEEE Access

**Date**: May 2023

**PDF**: <https://ieeexplore.ieee.org/abstract/document/10122539>

**Cite**: M. Piccinini, S. Taddei, M. Larcher, M. Piazza and F. Biral, "A Physics-Driven Artificial Agent for Online Time-Optimal Vehicle Motion Planning and Control," in IEEE Access, doi: 10.1109/ACCESS.2023.3274836 
 ___


## A Predictive Neural Hierarchical Framework <br/> for On-line Time-Optimal Motion Planning and Control <br/> of Black-Box Vehicle Models

*Mattia Piccinini, Matteo Larcher, Edoardo Pagot, Davide Piscini, Leone Pasquato, Francesco Biral*

<iframe width="1239" height="697" src="https://www.youtube.com/embed/h5eW01xXWaw" title="A predictive-neural framework for on-line time-optimal motion planning with black-box vehicle models" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Abstract

This paper addresses the on-line minimum-time motion planning and control of a black-box racing vehicle model. We present a hierarchical control framework, composed of a high-level non-linear model predictive controller (NMPC) based on an advanced kineto- dynamical vehicle model, a low-level neural network to compute the inverse steering dynamics and a longitudinal controller for the low-level tracking of speed profiles. An off-line identification proce- dure, consisting of simulated manoeuvres, is defined to learn the high-level and low-level models. A closed-loop simulation is setup to control the black-box vehicle near the limits of handling along a racetrack. Simulation results are compared with the off-line solution of a minimum-time-optimal control problem.

#### Publication Details

**Journal**: Vehicle System Dynamics

**Date**: February 2022

**PDF**: <https://www.tandfonline.com/doi/abs/10.1080/00423114.2022.2035776>

**Cite**: Mattia Piccinini, Matteo Larcher, Edoardo Pagot, Davide Piscini, Leone Pasquato & Francesco Biral (2022): A predictive neural hierarchical framework for on-line time- optimal motion planning and control of black-box vehicle models, Vehicle System Dynamics, DOI: 10.1080/00423114.2022.2035776
 ___

# Conference Papers

## Real-time Optimal Control of an Autonomous RC Car <br/> with Minimum-Time Maneuvers <br/> and a Novel Kineto-Dynamical Model

*Edoardo Pagot, Mattia Piccinini, Francesco Biral*

<iframe width="1239" height="697" src="https://www.youtube.com/embed/HADLEr5eTj0" title="Real time optimal control of an autonomous RC car with minimum-time maneuvers" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Abstract

In this paper, we present a real-time non-linear model-predictive control (NMPC) framework to perform minimum-time motion planning for autonomous racing cars. We introduce an innovative kineto-dynamical vehicle model, able to accurately predict non-linear longitudinal and lateral vehicle dynamics. The main parameters of this vehicle model can be tuned with only experimental or simulated maneuvers, aimed to identify the handling diagram and the maximum performance G-G envelope. The kineto-dynamical model is adopted to generate on-line minimum time trajectories with an indirect optimal control method. The motion planning framework is applied to control an autonomous 1:8 RC vehicle near the limits of handling along a test circuit. Finally, the effectiveness of the proposed algorithms is illustrated by comparing the experimental results with the solution of an off-line minimum-time optimal control problem.

#### Publication Details

**Conference**: 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)

**Date**: October 2020

**PDF**: <https://ieeexplore.ieee.org/document/9340640>

**Cite**: E. Pagot, M. Piccinini and F. Biral, "Real-time optimal control of an autonomous RC car with minimum-time maneuvers and a novel kineto-dynamical model," 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Las Vegas, NV, USA, 2020, pp. 2390-2396, doi: 10.1109/IROS45743.2020.9340640
 ___


# Workshop Papers

## Real-time Autonomous Parking in Unstructured Scenarios with an Indirect Optimal Control Approach

*Edoardo Pagot, Mattia Piccinini, Alice Plebe, Enrico Bertolazzi, Francesco Biral*

<iframe width="1239" height="697" src="https://www.youtube.com/embed/U2mRTzmFj9w" title="Real-time Planning and Tracking of Complex Parking Maneuvers with Indirect Optimal Control" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 
### Abstract

This paper presents a framework to generate in real-time autonomous parking maneuvers for generic and unstructured parking scenarios. Our method is based on the solution of minimum-time optimal control problems by means of an indirect approach. In a single optimization, the framework computes parking maneuvers composed of two or more segments of forward and reverse driving. The trajectory planning tasks are solved in real-time, and a fine grid is used to discretize the domain of the optimal control problems, resulting in accurate and collision-free solutions. Moreover, we introduce a novel method to deal with static obstacles in the optimal control problems, using penalty functions defined as regularized three-dimensional clip functions. The results show the effectiveness of our approach in various scenarios with narrow parking spots.

#### Publication Details

**Workshop**: Behavior-Driven Autonomous Driving in Unstructured Environments (BADUE), 
IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2022

**Date**: October 2022

**PDF**: <https://obj.umiacs.umd.edu/badue-accepted/8.pdf>





# Poster Sessions

## Mptree: Motion primitive tree exploration for trajectory planning with dynamic obstacle avoidance

*Mattia Piazza, Mattia Piccinini*

#### Details

**Poster Session**: Industrial Engineering Day, University of Trento

**Date**: November 2022

**PDF**:
 ___


## Virtual driver to control race cars near the limits

*Mattia Piccinini, Edoardo Pagot, Sebastiano Taddei*

#### Details

**Poster Session**: PhDII Poster Session, University of Trento

**Date**: June 2022

**PDF**:
 ___
