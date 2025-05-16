---
layout: page
title: "LLM enhanced RL for AD"
description: "Enhancing scenario understanding ablility for RL agent using LLM while suppressing the hallucinatory problems. (From Dec. 2024 to now)"
img: /assets/img/researches/LLM/featured.png
importance: 2
category: work
related_publications: false
horizontal: true
---
### **HCRMP: A LLM-Hinted Contextual Reinforcement Learning Framework for Autonomous Driving**
Collaborating student: *Zhiwen Chen, 1st-year Ph.D. Student*.

#### **Motivation**
Deep reinforcement learning (DRL) has become a powerful method for autonomous driving while often lacking safety guarantees.

![png](/assets/img/researches/safe/featured.png) 

Proposeing a safety enhanced deep reinforcement learning for autonomous motion planning in lane-changing maneuver. The goal of this work is to design a DRL motion planner, which dares to make mistakes to learn the safe driving policy faster and better.

#### **Highlights**
- Evaluate the future motion risk by projecting DRL behavior action into the feasible trajectory, while sorrunding vehicles' trajecotires are obtained from the prediction module.
- Dangerous action will be prevented and the dangerous virtual experiences are recoreded to gain various valuable experience data.
- Dangerous experiences are sampled with priority weight according their anticipated risk, enabling DRL agnet to learn a safer policy.

#### **Some Results**
<!-- ![png](/assets/img/researches/safe/traincurve.png) 
![png](/assets/img/researches/safe/testTR.png) -->

Proposing safety enhanced DRL approach could improve the driving performance, espeacially in safety metrics such as reducing collision rate, anticipated risk, etc.

More details can be found in our recent paper "Safety Enhanced Reinforcement Learning for Autonomous Driving: Dare to Make Mistakes to Learn Faster and Better." (under review, it will come soon)


### **Submitted/In Progress:**
1. **Zhuoren Li**, Jia Hu, Bo Leng, Lu Xiong, et.al., “Safety Enhanced Reinforcement Learning for Autonomous Driving: Dare to Make Mistakes to Learn Faster and Better,” *IEEE Trans. Intell. Transp. Syst.* (under review)
2. Ruolin Yang, **Zhuoren Li**, Bo Leng, et.al.，"Convergent Harmonious Decision: Lane Changing in a more Traffic Friendly Way." *IEEE Trans. Intell. Transp. Syst.* (under review)
3. Bo Leng, Ran Yu, **Zhuoren Li\***, Wei Han, Bo Leng, Lu Xiong and Hailong Huang, “Risk-Aware Reinforcement Learning for Autonomous Driving: Improving Safety When Driving through Intersection,” *Eng. Appl. Artif. Intel* (under review) [PDF](/assets/pdf/paper/SRL2024In.pdf) [arXiv](http://arxiv.org/abs/2503.19690).
