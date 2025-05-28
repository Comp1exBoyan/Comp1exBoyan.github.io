---
permalink: /
title: "Yifeng Tang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
## Biography 
I am currently a second year PhD student of [Centre for Robotics and AI]((https://www.robotics.manchester.ac.uk/)), the University of Manchester (UoM), and I am also a Doctoral Candidates of the EU Marie Sklodowska-Curie Action (MSCA) Doctoral Network (DN) [MSCA-DN](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/doctoral-networks), [RAICAM](www.raicam.eu). My research interests include robot learning, robotic manipulation, and reinforcement learning.

I decided to quit this PhD program and seek a new PhD position in dual-arm manipulation using learning-based methods. I am now the assitant researcher in Chinese Academy of Sciences. 


I received my bachelor's and master's degrees from Chongqing University(CQU) in 2020 and the University of Chinese Academy of Sciences(UCAS) in 2023, both in Control Science and Engineering. 

You can access my publications via [Yifeng Tang`s Google Scholar](https://scholar.google.com/citations?user=9V3txQ0AAAAJ&hl=en).

## Robots 
My story with robots started from a global competition [Robomaster](https://www.youtube.com/watch?v=Z2FR5xpIVeo). 
We formed teams according to the competition rules and completed task assignments. Team members designed mechanical structures, hardware circuits, and software algorithms.
The following pictures are my design during 2016-2018.
<div align="center">
    <img src="/images/robot1.png" alt="robot1" width="30%" style="margin-right: 20px;">
    <img src="/images/robot2.png" alt="robot2" width="33%" style="margin-right: 20px;">
    <img src="/images/PCB.png"   alt="PCB" width="30%">
</div>
Then, from 2019 to 2022, I served as the team's supervisor, guiding subsequent students to complete a series of excellent projects.
<!-- <div align="center">
    <img src="/images/mechaxcover1.png" alt="p1" width="95%" style="max-width: 400px;">
</div> -->
<img src="/images/mechaxcover1.png" alt="p1">

<div align="center">
    <img src="/images/all.gif" alt="robot1" width="30%" style="margin-right: 0px;">
<!--     <img src="/images/ser_1.gif" alt="robot2" width="30%" style="margin-right: 0px;"> -->
</div>

You can see more designs from the website of one of my most talented students, [Jiajian Fu](https://jiajianfu.github.io/). 

## Projects and publications
From 2020-2023, I served as a master student of UCAS and also an engineer in [SIAT-robot](https://english.siat.ac.cn/SI2017/IAIT2017/RC1/CIB/). 
My work included designing the autonomous driving control system and learning from demonstration for the robotic arm. 
### Autonomous Driving
<div align="center">
    <img src="/images/real.png" alt="robot1" width="50%" style="margin-right: 20px;">
    <img src="/images/t1.png" alt="robot2" width="40%" style="margin-right: 0px;">
</div>
I developed the control and local planning software module using C++. I designed two control algorithms: one is model predictive control, and the other is nonlinear control. I primarily devoted my time and effort to engineering tasks in this project. 
<div align="center">
    <img src="/images/nav.gif" alt="robot1" width="30%" style="margin-right: 0px;">
<!--     <img src="/images/ad_2.gif" alt="robot2" width="30%" style="margin-right: 0px;"> -->
    <img src="/images/turn.gif" alt="robot2" width="30%" style="margin-right: 0px;">
</div>

Access the papers [MPC](https://ieeexplore.ieee.org/abstract/document/10327667), [Nonlinear](https://ieeexplore.ieee.org/abstract/document/10218838).

### Learning from Demonstration(LfD)
I also completed the operation of a robotic arm through demonstration learning, where I was mainly responsible for designing and deriving the control laws. In this article, we present, for the first time, a stability proof that considers force-position information and validate it on a real machine.
<div align="center">
    <img src="/images/ex2.png" alt="robot1" width="60%" style="margin-right: 0px;">
    <img src="/images/plat.png" alt="robot2" width="35%" style="margin-right: 0px;">
</div>
The paper [TIE](https://ieeexplore.ieee.org/abstract/document/10373993).

### Game-theoretic RL controller for legged robot locomotion. 
In legged robots, the stance (support) leg and swing leg inherently exhibit a game-theoretic relationship in their influence on the overall system behavior. To address this, I designed a game-theoretic reward structure, treating the stance and swing legs as independent yet coupled agents. This framework was employed to train the control policies of both legs, and I provided a theoretical proof for the existence of a Nash equilibrium within this setup. The associated software implementation was jointly developed in collaboration with my research partner, Dr. D.C., from the FORTH Institute in Greece.

<div align="center">
    <img src="/images/barkour_n.gif" alt="robot1" width="35%" style="margin-right: 0px;">    <img src="/images/go2_n.gif" alt="robot1" width="35%" style="margin-right: 0px;">
  
</div>

<div align="center">
    <img src="/images/humanoid_n.gif" alt="robot1" width="35%" style="margin-right: 0px;">
    <img src="/images/real_go2.gif" alt="robot1" width="35%" style="margin-right: 0px;">
  
</div>

### AI Robot for Science

Before starting my new PhD program, I will be working at the Chinese Academy of Sciences on AI-driven robotic systems for chemical and materials experiments. I will lead the development of a robotic platform that integrates large language models (LLMs) with vision-language models (VLMs).
Furthermore, I hope to maintain an active connection with this project when I begin my new PhD program.
