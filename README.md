# Reinforcement Learning for Real-Time Decision-Making in Autonomous Vehicles
Overview
This repository contains the seminar paper, supporting figures, and code (if applicable) related to the study "Reinforcement Learning for Real-Time Decision-Making in Autonomous Vehicles" by Muhammad Hamza Rao (mur5582) for the Summer 2025 semester.

The paper explores how reinforcement learning (RL) algorithms can enhance the decision-making capabilities of autonomous vehicles (AVs) in complex urban environments. A comparative analysis of key RL algorithms (DQN, DDPG, PPO, SAC, TD3) is conducted using criteria such as safety, adaptability, and real-time response.

Contents
Scientific_Seminar_mur5582.pdf: Full seminar paper with literature review, methodology, experiments, and discussion.

(Optional folders/files for simulation scripts, models, or visualizations if added later.)

Key Topics
Traditional decision-making systems vs. RL in AVs

Sensor integration (Camera, LiDAR, Radar) and simulation tools (CARLA, SUMO)

Challenges of urban driving: unpredictability, safety, latency

Comparative performance of RL algorithms on:

Lane keeping

Intersection handling

Lane changing

Obstacle avoidance

Main Findings
SAC and TD3 consistently outperform other algorithms in complex, dynamic environments due to their robustness and ability to handle continuous control.

PPO provides stable, general performance and is effective in multi-agent and high-dimensional scenarios.

Real-time AV decision-making using RL requires balancing safety and efficiency, low-latency inference, and strong generalization capabilities.

Limitations
Simulated environments (CARLA, SUMO) used for experimentation may not fully capture real-world complexities.

Computational limitations impacted the scope of hyperparameter tuning and deployment analysis.

Integration with perception and control stacks is left for future work.

Future Directions
Bridging the sim-to-real gap through domain adaptation and safe RL.

Incorporating multi-agent modeling and social behavior prediction.

Exploring hybrid approaches combining RL with symbolic or rule-based reasoning.
