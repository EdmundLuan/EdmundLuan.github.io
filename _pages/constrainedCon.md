---
layout: archive
title: "CAMERAS"
permalink: /constrainedcon/
author_profile: false
---

{% include base_path %}

# ConstrAined ModEl Reference Adaptive conSensus: a framework

## Description
-   Consensus of multi-agent systems (MAS) has wide applications. Many consensus control algorithms have been proposed. However, state-of-the-art algorithms do not work well in realistic conditions. On one hand, MAS in real-life situations are subject to various constraints, e.g. kinematic constraints, actuator saturation, safety concerns, etc., along with uncertainties and disturbances. On the other hand, most algorithms assume that any point in the state spaces of agents is legit and therefore they do not have guarantees on not breaking the predesignated constraints.

<img src="../images/1ord_basic.png" scale="50%" align="center"> 

(Fig. 1: Consensus subject to time-varying state constraints)

<br/>

-   In this project, we investigate **distributed consensus** control algorithms for MAS with **time-varying state constraints**, parameter uncertainties and external disturbances. We hope to extend applications of MAS into realistic scenarios involving the above conditions.  

<br/>
<br/>

## Progress:

-   We have proposed a distributed leaderless consensus algorithm framework for a type of continuous-time linear multi-agent systems with time-varying asymmetric state constraints, uncertainties, and disturbances under time-varying directed topologies. 
-   In the presence of bounded disturbances, continuous uncertainties in agents' models, and **time-varying constraints on agents' positions**, consensus control algorithms under our framework for MAS consisting of agents governed by first- or second-order dynamics have been proposed and validated theoretically and numerically.  

<img src="../images/2ord.png" scale="100%" align="center">

(Fig. 2: Numerical simulation results of four double integrators achieving consensus under switching directed topologies) 

<br/>
<br/>

-   Simulations powered by [Robotarium](https://www.robotarium.gatech.edu/)[^1] have shown the effectiveness of our algorithms. See Fig. 3.  

<img src="../images/6_simResults_03151152.gif" scale="120%" align="center">

(Fig. 3: Six robots rendezvous under switching directed topologies subject to time-varying constraints) 

<br/>
<br/>
<br/>

-   **More details will be disclosed in our paper**. Stay tuned. 

<br/>

[^1]: Pickem, Daniel, et al. "The robotarium: A remotely accessible swarm robotics research testbed." *2017 IEEE International Conference on Robotics and Automation (ICRA)*. IEEE, 2017. Available at [*https://ieeexplore.ieee.org/abstract/document/7989200*

