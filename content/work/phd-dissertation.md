---
draft: false
title: "Accelerating Deep Reinforcement Learning for Autonomous Racing"
slug: phd-dissertation
job_type: "PhD Dissertation"
stack: "Python • Pytorch  • F1Tenth  • Reinforcement Learning • Control Systems "
website_link: ""
github_link: "https://github.com/bdevan5/FoneTenth/"
color: "#E74C3C"
index: 99

# thumb_image: "https://res.cloudinary.com/bonzdev/image/upload/w_1000,ar_16:9,c_fill,g_auto/v1621922693/mockup_crop/iiw_crop_z7h93m.png"
# cover_image: "https://res.cloudinary.com/bonzdev/image/upload/c_thumb,w_500,g_face/v1622111359/mockup_crop/iiw_crop_z7h93m.png"
---


Two weeks ago, on the 1st of November, I submitted my PhD Disseratation in Electronic Engineering at Stellenbosch University. 
My dissertation is titled, "Accelerating Deep Reinforcement Learning for Autonomous Racing" and looks at how DRL methods can be improved for F1/10th racing.
It is very relieving to be at the end of a three year journey involving a lot of hard work and personal growth. 
I am thankful to God who gave me the opportunity and the strength to complete it. 

## Lay Summary

F1/10TH autonomous racing has been approached using classical methods that use vehicle models to generate and follow a plan, resulting in high-performance racing.
While deep reinforcement learning (DRL) agents, which learn from experience, have been used for racing, approaches have suffered from poor performance and safety concerns due to training the agent in a simulator before transferring it to a physical vehicle.
This work combines classical vehicle models and machine learning techniques to accelerate DRL methods for autonomous racing by making the three contributions of, (1) novel learning formulations resulting in feasible, high-speed racing behaviour, (2) a method for safely training agents to race onboard physical vehicles, with them never crashing, and (3) investigating hybrid architectures for obstacle avoidance.
The novel learning formulations enable the agent to learn an appropriate speed profile of slowing down and speeding up, resulting in lower lap times, using higher top speeds than in previous work.
The online learning method can train agents to race without ever crashing, which enables agents to be trained onboard physical vehicles, resulting in better driving performance.
Finally, the hybrid architectures for obstacle avoidance demonstrate that DRL agents can expand the capability of classical planners to avoid obstacles.



## Contributions

In the work, I made three contributions of:

1) The development of learning formulationsfor high-speed racing through a comprehensive evaluation of current methods, identification of current limitations, and development of new learning formulations that harness vehicle models to aid the training.

2) The development of a supervisor that can ensure vehicle safety and be used to train DRL agents without them ever crashing, enabling agents to be trained online physical vehicles, thus bypassing the sim-to-real gap

3) The extension of the racing problem to include avoiding un-mapped obstacles on the track and investigating how the flexibility of DRL agents in can be combined with classical solutions for high-performance obstacle avoidance.





