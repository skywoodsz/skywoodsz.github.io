---
title: "legged_slam: a SLAM framework for legged robot"
excerpt: "State Key Laboratory of Robotics and System, China 
<br/>
<img src='/images/projects/legged_slam/b1_slope.gif' />
"
collection: projects
date: 2023-05-01
---

## Quadruped State Estimation

The repository includes a state estimator and a terrain estimator for quadruped robots. The state estimator uses Linear Kalman to estimate the position and velocity of the quadruped. The terrain estimator estimates the normal vector of the ground. The algorithm is validated on the real robot Aliengo and can be deployed to other quadruped robots.

[Code](https://github.com/skywoodsz/Quadruped-State-Estimation)

![aliengo](/images/projects/legged_slam/aliengo.jpg)

## LVI-SAM with legged odometry
The repository fuses leg odometry to LVI-SAM, robustly estimating states of quadruped robots in degraded scenarios.

[Code](https://github.com/skywoodsz/LVI-SAM-Quadruped)

![lvi_sam_robot](/images/projects/legged_slam/lvi_sam_robot.png)
![lvi_sam_result](/images/projects/legged_slam/lvi_sam_result.png)