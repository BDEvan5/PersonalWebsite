---
draft: false
title: "Accelerating Deep Reinforcement Learning via Supervisory Safety Systems"
slug: safety-system-at-penn
job_type: "Conference paper or"
stack: "Python • Pytorch  • F1Tenth  • Reinforcement Learning • Viability Theory "
website_link: ""
github_link: "https://github.com/bdevan5/SuperSafety/"
color: "#2ECC71"
index: 99

# thumb_image: "https://res.cloudinary.com/bonzdev/image/upload/w_1000,ar_16:9,c_fill,g_auto/v1621922693/mockup_crop/iiw_crop_z7h93m.png"
# cover_image: "https://res.cloudinary.com/bonzdev/image/upload/c_thumb,w_500,g_face/v1622111359/mockup_crop/iiw_crop_z7h93m.png"
---


During 2021 and 2022 as part of my PhD research, I built a supervisory safety system that can be used to train deep reinforcement learning (DRL) agents onboard physical vehicles. 
In June 2022, I travelled to the University of Pennsylvania to test my algorithms with Johannes Betz, and Hongrui Zheng, under Prof. Rahul Mangharam.

We were able to train a DRL agent to drive around the track onboard a physical vehicle, while never crashing.
This research means that the sim-to-real gap, which is often prohibative, can be bypassed, improving the applicability of DRL agents in the real-world.

We wrote a paper that is currently under review for ICRA 2023, called, "Accelerating Online Reinforcement Learning via Supervisory Safety Systems".

### Paper Abstract

Deep reinforcement learning (DRL) is a promising method to learn control policies for robots only from demonstration and experience. 
To cover the whole dynamic behaviour of the robot, the DRL training is an active exploration process typically derived in simulation environments. 
Although this simulation training is cheap and fast, applying DRL algorithms to real-world settings is difficult.
If agents are trained until they perform safely in simulation, transferring them to physical systems is difficult due to the sim-to-real gap caused by the difference between the simulation dynamics and the physical robot.
In this paper, we present a method of online training a DRL agent to drive autonomously on a physical vehicle by using a model-based safety supervisor. 
Our solution uses a supervisory system to check if the action selected by the agent is safe or unsafe and ensure that a safe action is always implemented on the vehicle.
With this, we can bypass the sim-to-real problem while training the DRL algorithm safely, quickly, and efficiently. 
We provide a variety of real-world experiments where we train online a small-scale, physical vehicle to drive autonomously with no prior simulation training.
The evaluation results show that our method trains agents with improved sample efficiency while never crashing, and the trained agents demonstrate better driving performance than those trained in simulation.









