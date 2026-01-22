---
layout: page
title: Real-Time Phone Object Detection
description: End-to-end ROS 2 pipeline using phone camera and YOLOv5.
img: assets/img/2.jpg
importance: 1
category: work
---

**Technology Stack:** ROS 2, YOLOv5, OpenCV, Android Sensor Bridge

Developed an end-to-end **real-time object detection pipeline** integrating a mobile phone camera with ROS 2.

- **Mobile Integration:** Streamed live video from an Android device to ROS 2 using `ros2-android-sensor-bridge`.
- **YOLOv5 Inference:** Processed video streams with a `yolo_ros` node for object detection.
- **Image Transport:** Handled efficient compression and decompression (compressed to raw) for smooth transmission.
- **Visual Feedback:** Built a custom Python node using **OpenCV** and `cv_bridge` to draw bounding boxes and visualize detections in real-time on `rqt_image_view`.
