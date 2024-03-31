---
layout: page
title: "AutoBot"
description: Autonomous Four-Wheel Drive.
img: assets/img/Roomba.png
importance: 1
category: work
---

The project involved designing and developing an autonomous driving robot from scratch utilizing the Qualcomm RB5 robotics platform and mBot hardware kit. The system leveraged the Robot Operating System (ROS) architecture implemented in Python to effectively integrate sensor data from cameras, lidar, and encoders and control the robot's movements in real-time. Custom ROS packages were created to enable environmental perception, localization, mapping, path planning and control.

The robot leveraged computer vision and deep learning for landmark detection, allowing for accurate pose estimation within indoor environments. This facilitated completely autonomous navigation between waypoints while avoiding obstacles. Additionally, an Extended Kalman Filter algorithm was implemented for Simultaneous Localization and Mapping (SLAM) to continuously improve the robot's awareness of its surroundings and build maps for navigation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/embed/C6VU2g32pOI?si=zQZOvPlNbkhyjqw8" class="img-fluid rounded z-depth-1" width="560" height="560" %}
    </div>
</div>
