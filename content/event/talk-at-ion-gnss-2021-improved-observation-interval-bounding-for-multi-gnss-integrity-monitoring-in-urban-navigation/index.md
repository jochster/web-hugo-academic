---
title: Improved Observation Interval Bounding for Multi-GNSS Integrity
  Monitoring in Urban Navigation
abstract: Talk at ION GNSS+ 2021, awarded best presentation of the track.
location: Virtual, St. Louis, MO, US
date: 2021-09-24T13:00:59.901Z
date_end: 2021-09-24T14:00:00.000Z
all_day: false
event: ION GNSS+ 2021
event_url: https://www.ion.org/gnss/index.cfm
publishDate: 2021-09-24T16:00:59.940Z
draft: false
featured: false
links:
  - url: https://www.ion.org/gnss/index.cfm
    name: Conference
    icon_pack: fas
    icon: book
#  - url: ''
#    name: Slides
#    icon_pack: fas
#    icon: file-powerpoint
#  - url: ''
#    name: Video
#    icon_pack: fas
#    icon: video
  - url: https://doi.org/https://doi.org/10.33012/2021.18078
    name: Publication
    icon_pack: fas
    icon: book-open
projects:
  - icsens
authors:
  - admin
  - Steffen Schön
tags:
  - GNSS
  - integrity
  - interval mathematics
  - urban navigation
  - error bounding
  - uncertainty modeling
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Reference trajectory in the i.c.sens measurement compaign
---
Integrity monitoring is of great importance for Global Navigation Satellite Systems (GNSS) applications. Unlike classical approaches based on probabilistic assumptions, the alternative interval-based integrity approach depends on deterministic interval bounds as inputs. Different from a quadratic variance propagation, the interval approach has intrinsically a linear uncertainty propagation which is adequate to describe remaining systematic uncertainty. 

In order to properly characterize all ranging error sources and determine the improved observation interval bounds, a processing scheme is proposed in this contribution. We validated for a first time how the sensitivity analysis is feasible to determine uncertainty intervals for residual ionospheric errors and residual tropospheric errors, taking advantage of long-term statistics against reference data. Transforming the navigation problem into a convex optimization problem, the interval bounds are propagated from the range domain to the position domain. 

We implemented this strategy for multi-GNSS positioning in an experiment with static data from International GNSS Service (IGS) station Potsdam (POTS) and an experiment with kinematic data from a measurement campaign conducted in the urban area of Hannover, Germany, on August 26, 2020.
