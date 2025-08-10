---
title: "Aerial manipulator: vision servo for aerial manipulator"
venue: "National Engineering Research Center of Robot Vision and Control"
date: "2021-06-01"
image: "/images/projects/aerial_manipulator/robot.png"
website: https://skywoodsz.github.io/projects/2021-aerial-manipualtor
collection: projects
excerpt: ""
---


## Autonomous removing foreign objects for power transmission line

The project considers a problem that visual servo control for an aerial manipulator removes foreign objects of power transmission lines. A position-based visual servoing (PBVS) combing a foreign objects locating method based on the point cloud with a hierarchical task-priority control method is employed to drive the aerial manipulator to remove the foreign object. Firstly, the RGB-D camera mounted on the drone obtains the point cloud of the environment, and the foreign object will be localized by the detection and localization algorithm. Then, a new visual servo error is proposed to decouple linear speed and angular speed, allowing the aerial manipulator to grasp accurately in the dangerous environment. In addition, the redundant characteristics of the aerial manipulator will be fully used by the hierarchical task priority control scheme. Finally, experimental results of a drone equipped with a 4-DOF delta manipulator removing foreign objects of power transmission line are provided to demonstrate the effectiveness of the control method.

[Paper](https://link.springer.com/article/10.1007/s10846-021-01482-3), [Video](https://www.bilibili.com/video/BV1f64y1k7WD/).

![remove](/images/projects/aerial_manipulator/remove.png)



## 6-DoF pose estimation for aerial manipulator grasping
Grasping objects in a large-scale area has been investigated extensively for mobile robots. But for unmanned aerial manipulator(UAM), this is still a challenging task. In order to solve the problem of accurate grasping in a large-scale area, we propose a novel detection and control framework for UAM, which consists of two stages: preliminary localization and precise localization. At the preliminary localization stage, the RGB-D sensor mounted on the end-effector of the manipulator scans to obtain the point cloud surrounding the UAM. By bringing the known target shape and processed point cloud parameters into our proposed loss function, we
select the highest priority area as the best potential region proposal, which can help the UAM to screen out the target for
precise localization from the obtained point cloud. At precise localization stage, after UAM reaches the best potential region,
the RGB-D sensor mounted on the drone uses the deep object pose estimation(DOPE) to estimate the 6D pose of the target. Through independently compensating for the disturbance of the UAV and manipulator, the UAM can accurately grasp the target with the estimated 6D pose.

[Paper](https://ieeexplore.ieee.org/document/9327306), [Video](https://www.bilibili.com/video/BV19U4y1H7of/).

![6D_pose](/images/projects/aerial_manipulator/6D_pose.png)