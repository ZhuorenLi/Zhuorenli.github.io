---
layout: page
title: "Control Granularity Research of RL-based Motion Planning"
description: "Deep reinforcement learning using parameterized trajectory action, for flexible and smooth driving in complex environment. (From Dec 2023 to now)"
img: assets/img/researches/lanning/featured.png
importance: 2
category: work
related_publications: false
horizontal: true
---

## **Stability Enhanced DRL with Parameterized Trajectory Action**
Collaborating student: *Guizhe Jin, 1st-year Gruaduated Student*.


### **Motivation**
When DRL directly control the vehicle's motion:
- The output commands are easy to change continuously whent DRL agent directly generates the control command.
- The control commands generated in real-time are prone to sudden changes in dynamically changing environments due to the lack of long-term motion planning.

![png](/assets/img/researches/lanning/featured.png)

Simultaneously considering the longterm discrete lane-change behavior goal and short-term realtime vehicle control. A hierarchical Reinforcement Learning method with a hybrid action space is designed to enhance driving stability and smoothness based on parameterized trajectory actions.

### **Highlights**
- Proposes a stability enhanced hierarchical reinforcement learning framework to achieve smooth and flexible driving behavior in dynamic traffic environment.
- Enables RL agent to participate in trajectory generation, where the trajectory parameter action is used to generate future motion path that adapt to various scenes.
- Realizes hybrid action output based on parameterized action space, hence the discrete and continuous actions have the optimal consistency.

### **Some Reults**
![png](/assets/img/researches/lanning/result-RLPTA.png)
The proposed hierarchical Reinforcement Learning method with hybrid Parameterized Trajectory Actions (RL-PTA) greatly reduces the ocsillation of the acceleration and steering command, while ensuring maneuvering flexibility and driving efficiency.

<!-- ## **Published paper:**
1. Zhuoren Li, Lu Xiong, Bo Leng et.al. Safe Reinforcement Learning of Lane Change Decision Making with Risk-Fused Constraint, in Proc. IEEE Int. Conf. Intell. Transp. Syst. (ITSC), 2023, pp. 1313-1319. -->

## **Publications:**
1. Zhuoren Li, Guizhe Jin, Ran Yu, Bo Leng and Lu Xiong, “Interaction-Aware Deep Reinforcement Learning Approach Based on Hybrid Parameterized Action Space for Autonomous Driving,” SAE Intell. Connected Veh. Symposium (SAE ICVS), 2024.

2. Guizhe Jin, Zhuoren Li, Bo Leng, Wie Han and Lu Xiong, "Stability Enhanced Hierarchical Reinforcement Learning for Autonomous Driving with Parameterized Trajectory Action." in Proc. IEEE Int. Conf. Intell. Transp. Syst. (ITSC), 2024.
