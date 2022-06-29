---
title: "Deterministic approaches for bounding GNSS uncertainty: A comparative
  analysis"
abstract: Talk at NAVITEC 2022, awarded best student presentation of the track.
location: Virtual, Noordwijk, The Netherlands
date: 2022-04-06T12:20:35.227Z
date_end: 2022-04-06T12:32:00.000Z
all_day: false
event: NAVITEC 2022
event_url: https://atpi.eventsair.com/navitec-2022/
publishDate: 2022-04-07T09:35:35.238Z
draft: false
featured: false
tags:
  - GNSS
  - integrity
  - uncertainty moodeling
  - error bounding
  - zonotope
  - polytope
  - interval mathematics
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
Uncertainty modeling and bounding are of vital importance for high-integrity GNSS applications. Classical approaches are mostly developed in a stochastic manner with probabilistic assumptions. However, the exact error distribution is often unknown, and remaining systematics may persist, so that a purely stochastic modeling of all error sources will not be adequate, and alternative uncertainty bounding and propagation should be studied. 

This paper introduces two deterministic approaches for GNSS uncertainty bounding and compares them with the conventional least-squares method theoretically and experimentally with simulated and real measurements. Both methods use deterministic intervals to denote observation uncertainty, subsequently following a linear uncertainty propagation instead of quadratic one. The interval extension of least-squares transfers the uncertainty into the position domain in the form of zonotope and further bound the stochasticity by the extended point confidence domain. As a comparison, the other method takes advantage of geometrical constraints and convex optimization, leading to a polytopic solution set and zonotopic confidence region. We show their theoretical similarities and highlight different interpretations in practice. Nevertheless, both are sufficient to account for both random and systematic components of uncertainty.