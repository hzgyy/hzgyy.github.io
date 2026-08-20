---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
My name is Yiyang Ge. I am a senior student in Zhejiang University majoring in Automation. 

My research focuses on robot learning, with an emphasis on reinforcement learning. My long-term goal is to maximize the potential of learning-based methods in robotics — particularly their ability to generalize and adapt easily to new tasks.

<!-- # 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->
# 📝 Projects
<div class='paper-box'><div class='paper-box-image'><div><img src='images/bachlar_thesis.gif' alt="sym" width="150%"></div></div>



<div class='paper-box-text' markdown="1">
<strong>Research on Reward Model in Real-World Robot Reinforcement Learning</strong>
- Investigated sample-efficient offline robot reinforcement learning using learned visual reward functions.
- Fine-tuned a pretrained Valine-Implicit Pretraining(VIP) model with a small set of demonstrations to esti-
mate task rewards.
- Integrated the learned reward model with Reward-Weighted Regression (RWR) to enable offline policy
improvement without manually designed rewards.
- Evaluated the approach in ManiSkill and deployed it on an AgileX Piper robot arm for a real-world cube
pick-and-place task
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/film.png' alt="sym" width="50%"><img src='images/film_success_rate.png' alt="sym" width="50%"></div></div>

<div class='paper-box-text' markdown="1">
<strong>A FiLM based Multi-task Reinforecement Learning</strong>
- This project was conducted as part of the course CS 4756: Robot Learning at Cornell University.
- Integrated a Feature-wise Linear Modulation (FiLM) layer into a multi-task RL model, allowing the task encoding to exert more direct control over the network.
- Observed that the FiLM-enabled model outperformed the vanilla multi-task learning baseline, which only concatenated a one-hot task encoding to the input.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/drone.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<strong>Quadropter Building and Autonomous Hovering</strong>
- Build a quadrotor and its controller from zero, and automatically hover it under motion capture system
- Implementing basic cascaded PID controller and SE(3) controller.
- Practice hardware, PCB design and assembling.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/hand.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
<strong>Force Control of an Under-actuated Exoskeleton</strong>
- Welding and assembling of magnetic encoder and exo-skeleton.
- Implement basic robotics modelling methods like DH-Parameters,forward kinematics and Jacobian.
- Using Field-Oriented-Control Method to control torque output of a BLDC motor.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/rl.gif' alt="sym" width="50%"><img src='images/cartpole.gif' alt="sym" width="50%"></div></div>

<div class='paper-box-text' markdown="1">
<strong>Reinforcement Learning Algotithms Implementation</strong>
- This project is part of the course assignments for Cornell CS4756 (Robot Learning) and CS4789 (Introduction to Reinforcement Learning).
- I tackled demo tasks in OpenAI Gym environments, including Cartpole, LunarLander, and Fetch-Reach. I implemented several classic RL algorithms, such as Q-learning, DQN, Policy Gradient (REINFORCE), Actor-Critic (A2C, SAC), DDPG, and more. Additionally, I analyzed the performance of these algorithms.
- Through this project, I gained hands-on experience with Pytorch and Numpy, while also learning to identify common bugs and pitfalls in RL algorithm implementation.
</div>
</div>


<!-- # 💻 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Reinforcement Learning Algorithms
This is the course projects of Cornell CS4756 robot learning and CS4789 Introduction to Reinforcement Learning. 

- Quadropter Building -->




# 📖 Educations
- *2022.09 - now*, Zhejiang University, Junior, Major: Automation 
- *2025.01 - 2025.05*, Cornell University, Exchange student, Major: ECE

# 🎖 Honors and Awards
- *2023,2025* Second Prize Scholarship of Zhejiang University
- *2023.12* Second Prize of Theoretical Physics Competition for University Students in Zhejiang Province
- *2024.04* First Prize in Zhejiang University Robot Competition (Transport Vehicle Track) 


# 🔥 Hobbies
- Soccer
- Badminton

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->