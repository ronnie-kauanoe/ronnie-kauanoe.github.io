---
layout: project
type: project
image: 
title: Implementing HTC Vive Tracking and Controller Input into Destiny-Class and Innovator-Class CyberCANOEs
permalink: projects/vive-cybercanoe
# All dates must be YYYY-MM-DD format!
date: 2019-08-15
labels:
  - Hybrid Reality
  - CyberCANOE
  - Vive
  - Motion Tracking
  - VRPN
summary: My first project working for LAVA to update the CyberCANOEs' tracking.
---

The Cyber-enabled Analysis, Navigation, and Observation Environment (CyberCANOE) is a hybrid reality environment developed by Dr. Jason Leigh in the Laboratory for Advanced Visualization and Applications (LAVA) at the University of Hawaii at Manoa. When I joined LAVA, my first project was to collaborate with Dr. Leigh and integrate Vive tracking into the Destiny-Class CyberCANOE housed in the lab. First, I exposed the data from a Vive Tracker and two Vive Pro controllers using a modified Virtual Reality Peripheral Network (VRPN). Second, I used Unity's ClusterInput classes to retrieve the exposed data and mapped the position, rotation, and controller input to the tracker (head and camera tracking) and controllers (left/right hands). Third, I assigned one of Destiny's eight computer nodes as the master and used the master to distribute the exposed data to its subordinates. This allows the view from each computer's screen array to be synchronized and produces a seemless 270° view. 

Click here to view the [CyberCANOE wiki](https://github.com/uhmlavalab/CyberCANOE/wiki).

Click here to view the [LAVA homepage](https://www.lavaflow.info/).

Click here to view the [modified VRPN](https://gitlab.com/karlun/vrpn-openvr) developed by Dr. Karljohan Palmerius.
