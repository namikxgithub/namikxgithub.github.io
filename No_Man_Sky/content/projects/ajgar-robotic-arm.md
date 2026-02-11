---
title: "A.J.G.A.R — The Robotic Arm"
draft: false
description: "6-DOF robotic arm with autonomous object manipulation, computer vision, and teleoperation capabilities."
tags: ["ROS", "MoveIt", "manipulation", "computer-vision"]
showDate: false
showAuthor: false
showReadingTime: false
weight: 4
---

## Overview

A 6 Degrees-of-Freedom robotic arm built at [A.T.O.M Robotics Lab](https://github.com/atom-robotics-lab/robotic-arm-atom) for autonomous object manipulation and teleoperation. The system integrates computer vision for perception-driven pick-and-place and supports remote operation.

## Key Features

- **Autonomous Pick-and-Place** — Vision-guided object detection and grasping using YOLOv8 and depth sensing
- **Motion Planning** — MoveIt-based trajectory planning with collision avoidance in cluttered workspaces
- **Teleoperation** — Remote control interface for manual arm operation
- **Simulation** — Full Gazebo environment with custom gripper plugins for virtual testing
- **Modular Architecture** — Seven specialized ROS packages covering control, description (URDF), hardware drivers, perception, planning, simulation, and plugins

## Tech Stack

`ROS Noetic` · `MoveIt` · `Gazebo` · `OpenCV` · `YOLOv8` · `Arduino` · `Raspberry Pi` · `Python` · `C++`

