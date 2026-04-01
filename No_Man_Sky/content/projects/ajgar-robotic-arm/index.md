---
title: "A.J.G.A.R — The Robotic Arm"
draft: false
description: "6-DOF robotic arm with autonomous object manipulation, computer vision, and teleoperation capabilities."
tags: ["ROS", "MoveIt", "manipulation", "computer-vision"]
showDate: false
showAuthor: false
showReadingTime: false
showSummary: true
summary: "6-DOF robotic arm with YOLOv8 vision-guided pick-and-place, MoveIt motion planning, and teleoperation."
weight: 4
---

<div style="display:grid; grid-template-columns:1fr 280px; gap:1.5rem; align-items:start; max-width:none; width:calc(100% + 300px); margin-right:-300px;">
<div>

## Overview

A 6 Degrees-of-Freedom robotic arm built at [A.T.O.M Robotics Lab](https://github.com/atom-robotics-lab/robotic-arm-atom) for autonomous object manipulation and teleoperation. The system integrates computer vision for perception-driven pick-and-place and supports remote operation.

## Key Features

- **Autonomous Pick-and-Place** — Vision-guided object detection and grasping using YOLOv8 and depth sensing
- **Motion Planning** — MoveIt-based trajectory planning with collision avoidance in cluttered workspaces
- **Teleoperation** — Remote control interface for manual arm operation
- **Simulation** — Full Gazebo environment with custom gripper plugins for virtual testing
- **Modular Architecture** — Seven specialized ROS packages covering control, description (URDF), hardware drivers, perception, planning, simulation, and plugins

</div>
<div style="position:sticky; top:1rem;">
<video autoplay loop muted playsinline style="width:100%; border-radius:12px;">
  <source src="/ajgar_demo.mp4" type="video/mp4">
</video>
</div>
</div>

## Tech Stack

`ROS Noetic` · `MoveIt` · `Gazebo` · `OpenCV` · `YOLOv8` · `Arduino` · `Raspberry Pi` · `Python` · `C++`

