---
layout: post
title: Mobile Robot Navigation Area
---

## DRL(Deep Reinforcement Learning) based Obscacle Avoidance

- Our research in **DRL (Deep Reinforcement Learning) based Obstacle Avoidance** leverages modern reinforcement learning techniques to enable agents to navigate complex environments while avoiding obstacles. We implement advanced algorithms such as **DQN (Deep Q Network)**, **DDPG (Deep Deterministic Policy Gradient)**, and **PPO (Proximal Policy Optimization)** to train agents to make optimal decisions in dynamic scenarios.
- These methods allow the agent to learn through interaction with the environment, continuously improving its ability to avoid both static and moving obstacles in real-time, leading to safe and efficient navigation.

![simulation.gif](https://github.com/tomasvr/turtlebot3_drlnav/blob/main/media/simulation.gif?raw=truef)

Ref: https://github.com/tomasvr/turtlebot3_drlnav/blob/main/media/simulation.gif

## MARL(Multi-Agent Reinforcement Learning) for Cooperative Task Solving

- Our research in **MARL(Multi-Agent Reinforcement Learning)** focuses on training multiple agents to collaborate and solve complex tasks efficiently in dynamic environments. We implement advanced reinforcement learning algorithms such as **MADDPG (Multi-Agent Deep Deterministic Policy Gradient)**, **MAAC (Multi-Agent Actor-Critic)**, and **MAPPO (Multi-Agent Proximal Policy Optimization)** to enable agents to coordinate and make optimal decisions in multi-agent scenarios.
- These methods allow agents to learn through interaction with both the environment and other agents, continuously improving their ability to cooperate, adapt, and efficiently solve tasks in real time. Our research is particularly focused on applications in **autonomous mobile robot coordination**, including **collaborative exploration**, **cooperative transportation**, and **formation control** in dynamic and uncertain environments.

![image](https://camo.githubusercontent.com/0eec68314bcbb7aeefe4580c24fcac485d867b04e8b07f91d752c57b92f97db7/68747470733a2f2f696d616765732e76656c6f672e696f2f696d616765732f6c656568653232382f706f73742f38643031373936642d313333642d343162612d386563362d6266343366393933373033322f696d6167652e706e67)  
## Leveraging Vision Technology for Navigation

- Our research in **SLAM (Simultaneous Localization and Mapping)** focuses on building indoor maps using **RGB-D sensors** combined with advanced models like **CNN**, **Vision-Transformer**, and **CLIP**. These models enable the segmentation of various indoor instances such as sofas and beds.
- The segmented data is used to generate **BEV (Bird's Eye View) maps**, which are essential for effective indoor navigation by providing a structured representation of the environment.

![semexp](https://devendrachaplot.github.io/projects/resources/semexp.gif)

Ref: https://devendrachaplot.github.io/projects/resources/semexp.gif

## Research on Digital Twin

- Our research on **Digital Twins** leverages **ROS (Robot Operating System)** for simulation, and we are enhancing realism by building a more accurate Digital Twin using **Unreal Engine**. This allows us to create a virtual environment that closely mirrors the real world for advanced navigation research.

![archvis-interior-rendering](./cvfolder/archvis-interior-rendering.png)

[https://www.unrealengine.com/marketplace/en-US/product/archvis-interior-rendering](https://www.unrealengine.com/marketplace/en-US/product/archvis-interior-rendering)

- Simultaneously, we are working on real-world mobile robot applications by integrating **embedded boards**, such as **Jetson Nano**, with sensors like **Lidar** and **RGB-D cameras**. A key focus is on **sensor fusion**, combining data from multiple sensors to improve the robot’s perception and navigation capabilities in complex environments.

## Related works

- [GOAT](https://theophilegervet.github.io/projects/goat/); **GO** to **A**ny **T**hing: Object Goal Navigation using Goal-Oriented Semantic Exploration
- [Semantic MapNet](https://arxiv.org/abs/2010.01191): Building Allocentric Semantic Maps and Representations from Egocentric Views
- [Trans4Map](https://arxiv.org/abs/2207.06205): Revisiting Holistic Bird’s-Eye-View Mapping from Egocentric Images to Allocentric Semantics with Vision Transformers
