---
layout: publication
title: "MPTREE: Motion primitive tree exploration for trajectory planning with dynamic obstacle avoidance"
authors: 
  - Mattia Piazza
  - Mattia Piccinini
publication: Industrial Engineering Day, University of Trento
pub_type: "poster"
year: 2022
doi: false
video: false #  false or youtube video id
slides: false
pdf: true # false no pdf true expected pdf with same name in the download folder
noimg: true # false or true to avoid image the publication page
# categories:
#   - Autonomous Driving
#   - Advanced Driving Assistance Systems
#   - Artificial Intelligence
#   - Optimal Control
#   - Poster
#   - Poster session
#   - Industrial Engineering Day
# tags:
#   - Artificial Agent
#   - Planning
#   - Optimal Control
#   - RRT* exploration
#   - Mattia Piazza
#   - Mattia Piccinini
#   - Francesco Biral
#   - Mauro Da Lio
#   - IED Trento
---

The MPTREE is a motion primitive tree exploration algorithm for trajectory planning with dynamic obstacle avoidance. The algorithm is based on the exploration of the vehicle state space by means of a tree. The algorithm is able to generate trajectories in real-time and to avoid dynamic obstacles.

The motion planning and decision-making algorithms have to satisfy the following high level goals:

  1. Generate trajectories (path plus speed profiles and actuation commands) to navigate autonomously in complex urban scenario.
  2. Consider communicated by other vehicles or use advance motion prediction models of other road users.
  3. Change the type of maneuver generated according to different vehicle categories (e.g. cars vs trucks) and according to different safety and comfort criteria.

<!-- The Tree Planner algorithm (TP) is the core of the maneuver generation. From a general overview the TP major iteration is composed by two main parts: the update and the tree expansion loop (sub-iterations). The TP receives information about the environment from perception and sensors and updates its internal state. In this scenario update, information are collected about the current states of the ego vehicle, about the map (via Electronic Horizon or similar), obstacles characteristic values and, if cooperative feature is active also the exchanged maneuvers.

As a first step the road geometry is populated with a mesh of way lines and extends the information of those elements with kinematic, dynamic and legal constraints (i.e. maximum velocity due to curvature, maximum legal velocity) or time-space prohibition-inhibition related to obstacles.

After this first setup step the algorithm performs the tree expansion.  The expansion is developed with an anytime approach. At every loop iteration the algorithm checks for the exit condition which is function of a maximum number of iterations and or a maximum time.
Here we summarize the basic principle behind the loop. The TP sample a new point with some characteristics such as position velocity and heading. Multiple approaches can be used to choose a new point (i.e. the RRT* implementation is based on random sampling). In our implementation we choose to exploit a mixed approach combining a greedy approach with known maneuvers, a structured lattice-like exploration and a random part. In this way we can enforce the TP to populate waypoints with a specific density in some region (i.e. explore most interesting zones and/or states).
Then the tree expansion tries to find a parent for the new sampled node. For each candidate parent in the neighbors’ list (previous) of the new waypoint it tries to connect and select the best one that satisfies all constraints. If no connection is available due to constraints or lack of neighbors, the new sample point is discarded. Elsewhere, the waypoint and its connection is stored and the rewiring procedure can be called. The rewiring aims at checking if new sampled node is a better parent for a sub-branch of the tree. For each candidate rewire in the neighbors’ list (forward) of the new waypoint it tries to connect and select the best one that satisfies all constraints. If it is better than the previously stored one, the subtree is updated, otherwise the tree remain the same.
At the end of the loop, the exit condition is checked. If it is satisfied, the loop is terminated, the best planned solution planned so far evaluated are implemented and communicated. If the exit condition is not yet satisfied another the expansion loop is reiterated looking for a better maneuver.
The faster the sub-iteration the larger the state set explored therefore the bigger tree is generated. The number of explored nodes plays a key role in the maneuver selection. A low number of nodes can produce an ill-conditioned fluctuating maneuver, while a reasonable number of nodes fairly approximate an optimal maneuver and a stable solution. Different implementation strategies can be adopted to improve the expansion phase in order not to explore not promising states and refine the best maneuvers. -->
