---
title: "How to determine uncertainty interval: Practice in GNSS and LiDAR"
abstract: Talk at 13th Summer Workshop on Interval Methods (SWIM)
location: Hannover, Germany
date: 2022-07-19T19:25:19.826Z
date_end: 2022-07-21T15:00:00.000Z
all_day: true
links:
  - url: https://swim.de
    name: Conference
    icon_pack: fas
    icon: book
  - url: https://konferenz.uni-hannover.de/event/53/attachments/40/72/13th_SWIM_Book_of_Abstracts.pdf
    name: Book of Abstract
    icon_pack: fas
    icon: book-open
event: 13th Summer Workshop on Interval Methods
event_url: https://swim.de
publishDate: 2022-06-24T19:25:19.869Z
draft: false
featured: false
authors:
  - admin
  - Steffen Schön
  - Yuehan Jiang
  - Bernado Wagner
tags:
  - interval mathematics
  - uncertainty modeling
  - GNSS
  - LiDAR
projects:
  - integrity-and-collaboration-in-dynamic-sensor-networks-i-c-sens
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: © Daniel Vogl / LUH
---
\##Introduction

**Intervals** can be seen as a natural way to bound observation uncertainty in navigation systems such as Global Navigation Satellite System (GNSS), Inertial Measurement Units (IMU) or optical sensors like LiDAR, since they are in principle free of any assumption about probability distributions and can thus describe adequately remaining systematic effects \[1]. Transferring the uncertainty from the observation domain to the state domain, such as the position and pose, the uncertainty is represented as a set-value, e.g., polytope \[2,3], zonotope \[1,3], and interval box \[4,8]. This is applicable in navigation integrity monitoring as an alternative approach for error bounding \[5], in contrast to the conventional stochastic handling.

The critical issue is ***how to determine the observation uncertainty interval properly***. Some researchers constructed intervals based on the confidence level, which is unavoidably associated with probabilistic distributions. In this contribution, we report methods that we have applied in the context of GNSS range-based positioning and LiDAR localization and show examples of uncertainty intervals due to different error sources in GNSS signal propagation and LiDAR measuring process.

\##Methodology

\#GNSS:

The measurement result after correcting recognized systematic effects is still only an estimate for the measurand value because of the uncertainty arising from random effects and imperfect correction of the results for systematic effects \[6]. Thus, the overall uncertainty of the pseudorange observation has contributions from all influence factors of the applied correction models.

The absolute values of the partial derivatives are used to linearly transfer the interval-described uncertainty of the vector of influences parameters into an uncertainty interval of the pseudorange. This method is used for modeling residual tropospheric errors and residual ionospheric errors which are two major components of the pseudorange uncertainty.

The upper bounds of multipath error on pseudorange measurements are typically represented by a multipath error envelope, dependent on the signal modulation and extra path delay. In this situation, we can construct interval values in a straight-forward way.

\#LiDAR

The error sources of the 3D LiDAR measurements on a moving vehicle consist of imperfect measuring of the laser beam \[7] and the ego-motion of the sensor base. An interval error model is proposed for 3D LiDAR to account for systematic errors like range offset, beam divergence and beam footprint \[8]. To acquire a coherent point cloud relative to a fixed coordinate frame, the general technique is to utilize the rotation estimation from the IMU with linear interpolation \[9], assuming continuous change in the angular velocity which yields an interpolation error to the measurements. Thus, the interpolation error is considered as an additional contribution to the interval.

\##Acknowledgement
This work was supported by the German Research Foundation and German Academic Exchange Service (DAAD) as part of the Research Training Group 2159: Integrity and Collaboration in Dynamic Sensor Networks (i.c.sens).

\##Reference

Schön, S., & Kutterer, H. (2006). Uncertainty in GPS networks due to remaining systematic errors: the interval approach. *Journal of Geodesy*, *80*(3), 150-162.

Dbouk, H., & Schön, S. (2020). Reliable bounding zones and inconsistency measures for GPS positioning using geometrical constraints. *Acta Cybernetica*, *24*(3), 573-591.

Su, J., & Schön, S. (2022). Deterministic approaches for bounding GNSS uncertainty: A comparative analysis, *2022 10th ESA Workshop on Satellite Navigation Technologies and European Workshop on GNSS Signals and Signal Processing (NAVITEC)*, 2022.

Drevelle, V., & Bonnifait, P. (2009, September). High integrity GNSS location zone characterization using interval analysis. In *Proceedings of the 22nd International Technical Meeting of the Satellite Division of The Institute of Navigation (ION GNSS 2009)* (pp. 2178-2187).

Su, J., & Schön, S. (2021, September). Improved Observation Interval Bounding for Multi-GNSS Integrity Monitoring in Urban Navigation. In *Proceedings of the 34th International Technical Meeting of the Satellite Division of The Institute of Navigation (ION GNSS+ 2021)* (pp. 4141-4156).

DeCleene, B. (2000, September). Defining pseudorange integrity-overbounding. In *Proceedings of the 13th International Technical Meeting of the Satellite Division of The Institute of Navigation (ION GPS 2000)* (pp. 1916-1924).

JCGM(2008). Evaluation of measurement data - Guide to the expression of uncertainty in measurement (GUM 1995 with minor corrections), JCGM 100:2008.

Skrzypczynski, P. (2008, September). How to recognize and remove qualitative errors in time-of-flight laser range measurements. In *2008 IEEE/RSJ International Conference on Intelligent Robots and Systems* (pp. 2958-2963). IEEE.

Voges, R., & Wagner, B. (2021). Interval-based visual-LiDAR sensor fusion. *IEEE Robotics and Automation Letters*, *6*(2), 1304-1311.

Zhang, J., & Singh, S. (2017). Low-drift and real-time lidar odometry and mapping. *Autonomous Robots*, *41*(2), 401-416.

Jekeli, C. (2012). Inertial navigation systems with geodetic applications. In *Inertial Navigation Systems with Geodetic Applications*. de Gruyter.