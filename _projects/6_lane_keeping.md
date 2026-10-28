---
layout: page
title: Autonomous Lane-Keeping Perception System
description: ROS 2 perception node using UFLD for real-time lane detection.
img: assets/img/1.jpg
importance: 9
category: work
---

**Technology Stack:** ROS 2, PyTorch, UFLD, OpenCV

Developed a **ROS 2 perception node** by integrating the **Ultrafast Lane Detection (UFLD)** model to accurately identify lane boundaries from real-world video feeds.

This project focused on high-speed, real-time inference suitable for autonomous driving scenarios. The system processes video streams, performs inference using the pre-trained UFLD model, and publishes lane coordinates and visualization markers to ROS 2 topics for downstream control and navigation tasks.

- **Edge deployment:** Re-implemented the model on the **NVIDIA Jetson Orin Nano** with **TensorRT FP16**, reaching **19 ms inference latency** while cutting GPU utilisation from **60% to 20%**.
- Paired with a **Stanley controller** for lateral control in the autonomous BAJA stack.
- Repository: [ros2-ultrafast-lane-detection](https://github.com/ShahazadAbdulla/ros2-ultrafast-lane-detection)
