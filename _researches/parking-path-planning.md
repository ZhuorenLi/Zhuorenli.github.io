---
layout: page
title: "Parking Path Planning"
description: "Simple and effective parking path planning based on geometric curve and MPC optimization. (From Feb 2021 to Aug 2021)"
img: /assets/img/researches/parking/featured.png
importance: 5
category: work
related_publications: false
horizontal: true
---


### **Parking Path Planning in AVP System**
<!-- Collaborating student: *Guizhe Jin, 1st-year Gruaduated Student*. -->

<!-- ### **Motivation**
When DRL directly control the vehicle's motion:
- The output commands are easy to change continuously whent DRL agent directly generates the control command.
- The control commands generated in real-time are prone to sudden changes in dynamically changing environments due to the lack of long-term motion planning. -->

The whole system is consisted of outdoor/indoor localization, parking slot perception, path planning and trakcing control.The overall framework is as following：
![png](/assets/img/researches/parking/featured.png)

Firstly, the minimum road width required for one-step parking is calculated by considering the geometric relationship between the initial position of the vehicle and the parking slot. Secondly, the parking path is determined based on the collision constraints of the parking slot. Finally, we establish the vehicle kinematics error model and use the MPC algorithm to optimize the parking path.
![png](/assets/img/researches/parking/allalg.png)
![png](/assets/img/researches/parking/alg.png)

AVP system demo in Tongji University：
![gif](/assets/img/researches/parking/avpdemogif.gif)

#### **This research havs supported many engineering projects**

AVP system for SAIC Motor Corporation, Ltd. (mass-produced electric vehicle: Marvel X)
![png](/assets/img/researches/parking/marvelx.png)

AVP system for New Energy Vehicle Corporation, Jiangxi Jiangling Motors Group.
![gif](/assets/img/researches/parking/jianglinproj.png)
![png](/assets/img/researches/parking/avptestgif.gif)

Autonomous Parking of Tiev-Plus vehicl for China Future Challenge of Intelligent Vehicles 
![png](/assets/img/researches/parking/realtest.png)


### **Publications:**
1. [Path Planning Method for Perpendicular Parking Based on Vehicle Kinematics Model Using MPC Optimization](https://saemobilus.sae.org/papers/path-planning-method-perpendicular-parking-based-vehicle-kinematics-model-using-mpc-optimization-2022-01-0085), **Zhuoren Li**, Lu Xiong, Bo Leng, Zhiqiang Fu, Dequan Zeng, Yiming Hu and Mingzhi Wu, *SAE Technical Papers*, 2022-01-0085, 2022.
2. Efficient and Flexible Autonomous Parking Planning based on Adaptive Multi-Step Motion Primitives, Bo Leng, Zhiwen Chen, **Zhuoren Li\*** and Lu Xiong, *Journal of Intelligent Transportation Systems*. (under review, R1)
