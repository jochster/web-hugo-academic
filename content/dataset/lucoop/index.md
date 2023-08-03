---
title: LUCOOP - Leibniz University Cooperative Perception and Urban Navigation Dataset
date: 2023-08-03T08:00:00.000Z
draft: false
featured: false
authors:
  - admin
tags:
  - integrity
  - multi-sensor fusion
  - autonomous driving
  - cooperative perception
  - urban navigation
external_link: ""
links:
  - url: https://data.uni-hannover.de/dataset/lucoop-leibniz-university-cooperative-perception-and-urban-navigation-dataset
    name: Data
  - url: https://ieeexplore.ieee.org/abstract/document/10186693
    name: Paper
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Recently published datasets have been increasingly comprehensive with respect to their variety of simultaneously used sensors, traffic scenarios, environmental conditions, and provided annotations. However, these datasets typically only consider data collected by one independent vehicle. Hence, there is currently a lack of comprehensive, real-world, multi-vehicle datasets fostering research on cooperative applications such as object detection, urban navigation, or multi-agent SLAM. In this paper, we aim to fill this gap by introducing the novel LUCOOP dataset, which provides time-synchronized multi-modal data collected by three interacting measurement vehicles. The driving scenario corresponds to a follow-up setup of multiple rounds in an inner city triangular trajectory. Each vehicle was equipped with a broad sensor suite including at least one LiDAR sensor, one GNSS antenna, and up to three IMUs. Additionally, Ultra-Wide-Band (UWB) sensors were mounted on each vehicle, as well as statically placed along the trajectory enabling both V2V and V2X range measurements. Furthermore, a part of the trajectory was monitored by a total station resulting in a highly accurate reference trajectory. The LUCOOP dataset also includes a precise, dense 3D map point cloud, acquired simultaneously by a mobile mapping system, as well as an LOD2 city model of the measurement area. We provide sensor measurements in a multi-vehicle setup for a trajectory of more than 4 km and a time interval of more than 26 minutes, respectively. Overall, our dataset includes more than 54,000 LiDAR frames, approximately 700,000 IMU measurements, and more than 2.5 hours of 10 Hz GNSS raw measurements along with 1 Hz data from a reference station. Furthermore, we provide more than 6,000 total station measurements over a trajectory of more than 1 km and 1,874 V2V and 267 V2X UWB measurements. Additionally, we offer 3D bounding box annotations for evaluating object detection approaches, as well as highly accurate ground truth poses for each vehicle throughout the measurement campaign.
