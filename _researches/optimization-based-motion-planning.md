---
layout: page
title: "Optimization-based Motion Planning"
description: "Smooth, stable and fast motion planning based on optimization-based approaches. (Sep 2021 - Jun 2023)"
img: /assets/img/researches/optimization/featured.png
importance: 4
category: work
related_publications: false
horizontal: true
---

### **Integrated Decision-making and Motion Planning to Enhance Oscilation-free Capability**

#### **Motivation**
**Unstable and Unsmooth motion in Uncertainty Environment:**
- Since there is a high-dimensional state/action modeling and the solution process considers the motion evolution of others, both POMDP and game-theory are easy to fall into the dimensionality problem, which makes the algorithm difficult to solve.
- Most existing studies consider decision making and planning/control separately, simple decision results may not be effectively utilized by planning, which tends to make the solution process of motion planning time-consuming, or the planning unable to reach decision expectations, trajectory shaking and even solving failure in dealing with complex scenarios

![png](/assets/img/researches/optimization/pomdpframe.png) 

An integrated framework of decision-making and motion planning for autonomous driving focus on the lane change/keeping maneuvers. Firstly, we design a belief POMDP decision planner while building the uncertainty of the prediction trajectories. Through the Multi-policy forward solution, getting the optimal decision action and the corresponding future states with the consideration of the uncertainty risk for surrounding vehicles. Then, based on the decision results of lateral semantic behavior and longitudinal continuous acceleration, we build drivable corridors including the reference state and the related boundary constraints, which provide better suited information for planning to solve the optimal motion sequence more quickly and stably, and improve its consistency with decision module. Finally, we consider the vehicle dynamics and introduce some soft constraints to solve the optimal motion trajectory.
![png](/assets/img/researches/optimization/corridor.png)   

#### **Highlights**
- Able to make oscillation-free behavior decisions given biased prediction.
- Able to cut through in the traffic efficiently and safely when being in squeezed. 
- Able to accelerate computation efficiency by building a state transfer model based on prediction uncertainty
- ble to reduce the dissonance between decision-making and motion planning.

#### **Some Reults**
![png](/assets/img/researches/optimization/cutinresult.png)
![png](/assets/img/researches/optimization/overtakeresult11.png)
![png](/assets/img/researches/optimization/overtakeresult12.png)

Able to recat to deceleration in advanced in cut-in scenario with smoother acceleration and speed changes.
In overtaking scenario, it able to overtake continuously with smoother lane-change driving way. It is also capable of avoiding possible lane-change failures and potential risks associated with reckless lane-change maneuver through uncertainty characterization.

Simulation demo in VTD:
![gif](/assets/img/researches/optimization/VTDtestgif.gif)

Real Test with our autonomous electric vehicle platform:
![png](/assets/img/researches/optimization/realtestandvehicle.png)
![gif](/assets/img/researches/optimization/xiqutestgif.gif)
![png](/assets/img/researches/optimization/realresult.png)



### **Mixed Integer Programming with Hybrid Model Predictive Control**
Collaborating student: *Encheng Tu, Graduated Student*.

#### **Motivation**
- Try to directly integrate the semantic behavior decision, trajectroy planning and motion control into a single optimal problem.

An integrated motion planning scheme for autonomous vehicles, which incorporates integer lane state and its logical constraints into the Model Predictive Control (MPC) framework, forming a hybrid MPC-based motion planning framework. 

#### **Highlights**
- Motion planning without semantic decisions: a hybrid model predictive control (HMPC)-based seamless motion planner.
- Able to integrate with external semantic decisions to achieve comprehensive optimization based on the external decisions.

#### **Some Results**
It allows for more efficient lane changing maneuvers in some scenarios wiith more rational lane-changing timing.
![png](/assets/img/researches/optimization/HMPCresult.png)

### **Trajectory Planning and Tracking Control Based on Hierarchical MPC**

A unified framework of trajectory planning and tracking control for autonomous overtaking, which is formed by hierarchical model predictive control, optimizing the lateral and longitudinal movement in two successive steps.

#### **Highlights**
- A unified trajectory planning and tracking control framework for autonomous overtaking using hierarchical MPC.
- Safety corridor generation on ST-Graph with different behavior mode.

#### **Some Reults**
It is able to perform smoothly driving maneuvers such as cornering and overtaking in CARLA simulation.
![png](/assets/img/researches/optimization/MPC1.png)
![png](/assets/img/researches/optimization/MPC2.png)

### **Publications:**
1. [Seamless Overtaking Maneuvers for Automated Driving: Integrated Motion Planning Based on Hybrid Model Predictive Control](https://ieeexplore.ieee.org/document/11390053), Bo Leng, Ran Yu, Chengen Tu, Lu Xiong, Arno Eichberger and **Zhuoren Li\***, *IEEE Trans. Ind. Electron.*, 2026, early access.
2. [Multi-mode Evasion Assistance Control Method for Intelligent Distributed-drive Electric Vehicle Considering Human Driver’s Reaction](https://cjme.springeropen.com/articles/10.1186/s10033-025-01270-2), Bo Leng, **Zhuoren Li\***, Ming Liu, Ce Yang, Yi Luo, Amir Khajepour and Lu Xiong, *Chin. J. Mech. Eng.* 2025, 38: 102. 
3. [An Integrated of Decision Making and Motion Planning Framework for Enhanced Oscillation-Free Capability](https://ieeexplore.ieee.org/document/10328568), **Zhuoren Li**, Jia Hu, Bo Leng, Lu Xiong and Zhiqiang Fu, *IEEE Trans. Intell. Transp. Syst.*, vol. 25, no. 6, pp. 5718-5732, June 2024. 
4. [A Seamless Motion Planning Integrating Maneuver Decision Based on Hybrid Model Predictive Control](https://ieeexplore.ieee.org/document/10422155), Chengen Tu, **Zhuoren Li**, Bo Leng and Lu Xiong, in *Proc. IEEE Int. Intell. Transp. Syst.*, 2023, pp. 3228-3234.
5. [A Unified Trajectory Planning and Tracking Control Framework for Autonomous Overtaking Based on Hierarchical MPC](https://ieeexplore.ieee.org/document/9922186), **Zhuoren Li**, Lu Xiong and Bo Leng, in *Proc. IEEE Intell. Transp. Syst. Conf. (ITSC)*, 2022, pp. 937-944. 
<!-- ### **Submitted/In Progress:** -->
