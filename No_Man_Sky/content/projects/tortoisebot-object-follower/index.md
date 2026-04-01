---
title: "TortoiseBot Object Follower"
draft: false
description: "ROS and OpenCV-based object following package for TortoiseBot by RigbetelLabs, using color filtering and contour detection."
tags: ["ROS", "OpenCV", "computer-vision"]
showDate: false
showAuthor: false
showReadingTime: false
showSummary: true
summary: "ROS + OpenCV object following package for TortoiseBot. Uses color filtering and contour detection to track and follow colored objects."
weight: 11
---

<div style="display:grid; grid-template-columns:1fr 280px; gap:1.5rem; align-items:start; max-width:none; width:calc(100% + 300px); margin-right:-300px;">
<div>

## Overview

An object following package for the TortoiseBot by [RigbetelLabs](https://rigbetellabs.com/). The package uses ROS and OpenCV to detect and follow colored objects in real time. The TortoiseBot and the playground arena are created and developed by RigbetelLabs.

## How It Works

1. **Color Filtering** — The camera image feed is converted into a binary image using HSV color space thresholding for specific color bounds
2. **Contour Detection** — Contours are detected on the binary image to locate the position and bounding area of the colored object
3. **Tracking & Following** — The object's position in the frame is used to generate velocity commands, steering the TortoiseBot to follow the target

## Key Features

- **Real-time Detection** — Processes live camera feed for responsive object tracking
- **Color-based Filtering** — Configurable HSV bounds to target different colored objects
- **Velocity Control** — Proportional control mapping object position to angular and linear velocity commands
- **Simulation & Hardware** — Works in both Gazebo simulation and on the physical TortoiseBot platform

</div>
<div style="position:sticky; top:1rem;">
<video autoplay loop muted playsinline style="width:100%; border-radius:12px;">
  <source src="/projects/tortoisebot-object-follower/feature.mp4" type="video/mp4">
</video>
</div>
</div>

## Tech Stack

`ROS` · `OpenCV` · `Python` · `Gazebo`
