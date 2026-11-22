---
title: "General Motors"
collection: teaching
excerpt: "ROS 2 motion planning and perception for UR and FANUC cobots on NVIDIA Jetson: MoveIt 2 / OMPL / Pilz / cuRobo planning server, real-time voxel mapping, vision-guided pick-and-place with learned perception, and automated robot-cell configuration."
type: "Robotics Software Engineer – Motion Planning (via Insight Global)"
permalink: /experience/gm-motion-planning/
date: 2026-01-01
period: "Jan 2026 – Present"
location: "Warren, Michigan"
---

* Built from scratch a modular ROS 2 motion planning server for UR and FANUC cobots on NVIDIA Jetson Thor, wrapping MoveIt 2 OMPL, Pilz, and NVIDIA cuRobo planning pipelines behind custom action/service APIs for planning, execution, and scene management, delivering lower latency and a smaller runtime footprint than `move_group`.
* Integrated OctoMap and nvblox voxel-mapping pipelines into the planning server, filtering and fusing wrist- and scene-mounted depth-camera point clouds into occupancy/ESDF maps in real time on Jetson Thor for collision-aware and obstacle-avoidance planning.
* Automated URDF/SRDF and MoveIt 2 configuration package generation from YAML cell definitions covering any UR/FANUC arm across 2 camera mounts, 3 grippers, and 3 finger extensions; configured 8+ production cells in minutes, replacing per-robot MoveIt Setup Assistant runs.
* Built motion planning that consumes grasp poses from learned segmentation and grasping models for vision-guided pick-and-place.
* Developed a Jetson AGX Orin ROS 2 data-collection package pairing a wrist-mounted RealSense D405 with FANUC controller joint states over EtherNet/IP (CIP) and HSPO, capturing ground truth without touching the existing production workflow; YAML-configured, zstd rosbag2, ~4 GB/min sustained.
