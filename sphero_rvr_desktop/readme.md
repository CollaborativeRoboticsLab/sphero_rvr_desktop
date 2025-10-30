# sphero_rvr_desktop

[![ROS2 Jazzy](https://img.shields.io/badge/ROS2-Jazzy-blue)](http://wiki.ros.org/noetic/Installation/Ubuntu)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This package provides a desktop interface for controlling the Sphero RVR. It is primarily used to launch rviz.

## Launching RViz with URDF Preview

You can launch RViz with a preview of the Sphero RVR URDF model using the following command:

```bash
ros2 launch sphero_rvr_desktop urdf_preview.launch
```

## View robot in RViz

You can launch RViz directly to view the robot using the following command:

```bash
ros2 launch sphero_rvr_desktop display.launch
```
