---
title: Towards integrity for GNSS-based urban navigation - challenges and
  lessons learned
publication_types:
  - "1"
authors:
  - Steffen Schön
  - Kai-Niklas Baasch
  - Lucy Icking
  - Ali KarimiDoona
  - Qianwen Lin
  - Fabian Ruwisch
  - Anat Schaper
  - admin
publication: In *Proceedings of the 33rd IEEE Integelligent Vehicles Symposium*
publication_short: In *IEEE IV 2022*
abstract: ""
draft: false
featured: true
links: 
- name: Conference
  url: https://www.iv2022.com
  icon_pack: fas
  icon: book
- name: PDF request
  icon_pack: fas
  icon: envelope
  url: mailto:suj@ife.uni-hannover.de
- name: ResearchGate
  url: https://www.researchgate.net/publication/360938638_Towards_Integrity_for_GNSS-based_urban_navigation_-_challenges_and_lessons_learned
  icon_pack: ai
  icon: researchgate
tags:
  - urban navigation
  - GNSS
  - integrity
  - autonomous driving
  - Multipath effect
  - interval mathematics
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: In the framework of the Research Training Group i.c.sens, various
    collaborative positioning experiments were carried out in the urban
    environment around the campus.
  alt_text: ""
summary: For safety critical applications like autonomous driving, high trust in
  the reported navigation solution is mandatory. This trust can be expressed by
  the navigation performance parameters, especially integrity. Multipath errors
  are the most challenging error source in GNSS since only partial correction is
  possible. In order to ensure high integrity of GNSS-based urban navigation,
  signal propagation mechanisms and the potential error sources induced by the
  complex measurement environment should be sufficiently understood.
date: 2022-06-05T18:00:35.596Z
---
For safety critical applications like autonomous driving, high trust in the reported navigation solution is mandatory. This trust can be expressed by the navigation performance parameters, especially integrity. Multipath errors are the most challenging error source in GNSS since only partial correction is possible. In order to ensure high integrity of GNSS-based urban navigation, signal propagation mechanisms and the potential error sources induced by the complex measurement environment should be sufficiently understood. 

In this contribution, we report on recent progress on this topic in our group. We conducted various experiments in urban areas and investigated the behavior and magnitude of GNSS signal propagation errors. To this end, ray tracing algorithms combined with 3D city models are implemented to identify propagation obstructions and quantify propagation errors. A Fresnel zone-based criterion is exploited to determine the occurrence and magnitude of diffraction. GNSS Feature Maps are proposed to visualize the analyses and to predict situations with potential loss of integrity. 

To measure the integrity of urban navigation, we developed alternative set-based approaches in addition to the classical stochastic approach. Based on interval mathematics and geometrical constraints, they are sufficient to bound remaining systematic uncertainty and feasible for integrity applications.
