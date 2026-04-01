---
title: "MR. Robot — ModulaR Robot"
draft: false
description: "Autonomous modular navigation robot for transportation, sanitation, and multi-purpose field deployment."
tags: ["ROS", "navigation", "modular"]
showDate: false
showAuthor: false
showReadingTime: false
showSummary: true
summary: "Modular autonomous robot with SLAM, navigation, and swappable payloads for transportation and sanitation."
weight: 5
---

<div style="display:grid; grid-template-columns:1fr 280px; gap:1.5rem; align-items:start; max-width:none; width:calc(100% + 300px); margin-right:-300px;">
<div>

## Overview

[MR. Robot](https://github.com/atom-robotics-lab/MR-Robot) is a modular autonomous robot built at A.T.O.M Robotics Lab, capable of mapping, navigation, transportation, and sanitation tasks. Its modular design allows swapping payloads and sensor configurations for different deployment scenarios.

## Key Features

- **Autonomous Navigation** — SLAM-based mapping with move_base and AMCL for localization and path planning
- **Modular Design** — Swappable payload modules for transportation, sanitation, and custom applications
- **Multi-sensor Support** — Configurable launch with camera, LiDAR, and Kinect depth camera
- **3D Mapping** — Octomapping support via the point-cloud navigation branch for volumetric environment representation
- **Simulation-first** — Full Gazebo simulation with custom worlds for development and testing before hardware deployment

</div>
<div style="position:sticky; top:1rem;">
<img src="feature.jpg" alt="MR. Robot" style="width:100%; border-radius:12px;" />
</div>
</div>

## Tech Stack

`ROS Noetic` · `Gazebo` · `OpenCV` · `Raspberry Pi` · `ESP32` · `Python` · `Blender`

