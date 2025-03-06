---
layout: page
title: "Control Granularity Research of RL-based Motion Planning"
description: "DRL using parameterized action with sufficient control granularity, for flexible and smooth driving in complex environment. (From Dec 2023 to now)"
img: assets/img/researches/CGRL/featured.png
importance: 2
category: work
related_publications: false
horizontal: true
---

### **Hybrid Action Based Reinforcement Learning for Multi-Objective Compatible Autonomous Driving**
Collaborating student: *Guizhe Jin, 2nd-year Gruaduate Student*.

#### **Motivation**
- Coordinate both stability and flexibility of driving maneuver.
- Compating multi-attributes reward during RL policy training.
- Facilitating the policy exploration for finding global optimal solution.

![png](/assets/img/researches/CGRL/MoEC.png)

Simultaneously considering the longterm discrete lane-change behavior goal and short-term realtime vehicle control. A hierarchical Reinforcement Learning method with a hybrid action space is designed to enhance driving stability and smoothness based on parameterized trajectory actions.

#### **Highlights**
- Designing a hybrid action structure including long-horizon behavior action and trajectory parameters, and short-horizon control command.
- Constructing a multi-critic approach to compat efficiency reward and safety reward during RL policy training.
- Proposing an epistemic uncertainty-based exploration strategy to improve sample efficiency and comprehensive learning performance.

#### **Some Reults**
![png](/assets/img/researches/CGRL/MoEC-train.png)
![png](/assets/img/researches/CGRL/MoEC-test.png)


### **Stability Enhanced DRL with Parameterized Trajectory Action**
Collaborating student: *Guizhe Jin, 2nd-year Gruaduate Student*.

#### **Motivation**
When DRL directly control the vehicle's motion:
- The output commands are easy to change continuously whent DRL agent directly generates the control command.
- The control commands generated in real-time are prone to sudden changes in dynamically changing environments due to the lack of long-term motion planning.

![png](/assets/img/researches/CGRL/RLTPA.png)

Simultaneously considering the longterm discrete lane-change behavior goal and short-term realtime vehicle control. A hierarchical Reinforcement Learning method with a hybrid action space is designed to enhance driving stability and smoothness based on parameterized trajectory actions.

#### **Highlights**
- Proposes a stability enhanced hierarchical reinforcement learning framework to achieve smooth and flexible driving behavior in dynamic traffic environment.
- Enables RL agent to participate in trajectory generation, where the trajectory parameter action is used to generate future motion path that adapt to various scenes.
- Realizes hybrid action output based on parameterized action space, hence the discrete and continuous actions have the optimal consistency.

#### **Some Reults**
![png](/assets/img/researches/CGRL/result-RLPTA.png)
The proposed hierarchical Reinforcement Learning method with hybrid Parameterized Trajectory Actions (RL-PTA) greatly reduces the ocsillation of the acceleration and steering command, while ensuring maneuvering flexibility and driving efficiency.


### **Published paper:**
1. Guizhe Jin, **Zhuoren Li**, Bo Leng, et al. "Hybrid Action Based Reinforcement Learning for Multi-Objective Compatible Autonomous Driving," 2025. [PDF](/assets/pdf/paper/Hybrid_Action_Based_Reinforcement_Learning_for_Multi_Objective_Compatible_Autonomous_Driving.pdf), [arxiv](https://arxiv.org/abs/2501.08096).

2. **Zhuoren Li**, Guizhe Jin, Ran Yu, Bo Leng and Lu Xiong, “Interaction-Aware Deep Reinforcement Learning Approach Based on Hybrid Parameterized Action Space for Autonomous Driving," *SAE Intell. Connected Veh. Symposium (SAE ICVS)*, 2024. [PDF](/assets/pdf/paper/2024SAEICVS 2024-01-7035.pdf), [DOI](https://www.sae.org/publications/technical-papers/content/2024-01-7035/).

3. Guizhe Jin, **Zhuoren Li**, Bo Leng, Wie Han and Lu Xiong, "Stability Enhanced Hierarchical Reinforcement Learning for Autonomous Driving with Parameterized Trajectory Action." in *Proc. IEEE Int. Conf. Intell. Transp. Syst. (ITSC)*, 2024.

### **Paper in Preparation:**
1. Guizhe Jin, **Zhuoren Li**, Bo Leng, et al. "Hybrid Time-Scale Hierarchical RL for Motion Planning of Autonomous Driving," 2025.
