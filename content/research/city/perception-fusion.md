---
title: "Perception Fusion"
weight: 1
type: docs
description: >
  Infrastructure-assisted perception fusion for autonomous vehicles.
---

### **VIPS: Real-Time 3D Perception Fusion for Infrastructure-Assisted Auto-Driving**
![](/images/research/perception-fusion.png)
Infrastructure-assisted autonomous driving is an emerging paradigm that expects to significantly improve the driving safety of autonomous vehicles. The key enabling technology for this vision is to fuse LiDAR results from the roadside infrastructure and the vehicle to improve the vehicle's perception in real time. In this work, we propose VIPS, a novel lightweight system that can achieve decimeter-level and real-time (up to 100ms) perception fusion between driving vehicles and roadside infrastructure. The key idea of VIPS is to exploit highly efficient matching of graph structures that encode objects' lean representations as well as their relationships, such as locations, semantics, sizes, and spatial distribution. Moreover, by leveraging the tracked motion trajectories, VIPS can maintain the spatial and temporal consistency of the scene, which effectively mitigates the impact of asynchronous data frames and unpredictable communication/compute delays. We implement VIPS end-to-end based on a campus smart lamppost testbed. 


<video width="80%" controls>
    <source src="/video/VIPS.mp4" type="video/mp4">
</video>



