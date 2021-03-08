---
layout: archive
title: "Constrained Consensus"
permalink: /constrainedCon/
author_profile: false
---

{% include base_path %}

# Distributed Constrained Consensus of MAS with Uncertainties and Disturbances under Switching Directed Graphs

## Description
-   Consensus of multi-agent systems(MAS) has wide applications. Many consensus control algorithms have been proposed. However, state-of-the-art algorithms do not work well in realistic conditions. On one hand, MAS in real-life situations are subject to various constraints, e.g. kinematic constraints, actuator saturation, safety concerns, etc., along with parameteric uncertainties and disturbances. On the other hand, most algorithms assume that any point in the state spaces of agents is legit and therefore they do not have guarantees on not breaking the predesignated constraints. 
-   In this project, we investigate **distributed** consensus control algorithms for MAS with **time-varying state constraints**, parameter uncertainties and external disturbances. We hope to extend applications of MAS into realistic scenarios involving the above conditions.  

<br/>

## Progress: 

-   We have proposed a distributed leaderless consensus algorithm framework for a type of continuous-time linear multi-agent systems with time-varying asymmetric state constraints, uncertainties, and disturbances under time-varying directed topologies. 
-   In the presence of bounded disturbances, continuous parametric uncertainties in agents' models, and **time-varying constraints on agents' positions**, consensus control algorithms under our framework for MAS consisting of agents governed by first- or second-order dynamics have been proposed and validated theoretically and numerically.  

<img src="../images/2ord.png" scale="100%" align="center">

(Consensus of 4 double integrators under switching directed topologies) 

<br/>

-   Simulations with [Robotarium](https://www.robotarium.gatech.edu/) have shown the effectiveness of our algorithms. 

<img src="../images/robotariumSim.gif" scale="120%" align="center">

<br/>

-   More details will be disclosed in our paper. Stay tuned. 

<br/>

