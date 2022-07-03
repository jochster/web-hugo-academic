---
title: Talk at iLoc workshop of IEEE IV 2022
abstract: "Invited paper at the iLoc workshop: *Deterministic approaches for
  bounding GNSS uncertainty: A comparative analysis*"
location: Aachen, Germany
date: 2022-06-05T08:30:03.212Z
date_end: 2022-06-05T21:00:00.000Z
all_day: false
event: The 1st iLoc workshop of 33rd IEEE Intelligent Vehicles Symposium
event_url: https://sites.google.com/view/iloc-2022/
publishDate: 2022-06-05T17:15:03.224Z
draft: false
featured: false
authors:
  - admin
tags:
  - integrity
  - workshop
  - i.c.sens
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: ""
---
Uncertainty modeling and bounding are of vital importance for high-integrity GNSS applications. Classical approaches are mostly developed in a stochastic manner with probabilistic assumptions. However, the exact error distribution is often unknown, and remaining systematics may persist, so that a purely stochastic modeling of all error sources will not be adequate, and alternative uncertainty bounding and propagation should be studied. 

This paper introduces two deterministic approaches for GNSS uncertainty bounding and compares them with the conventional least-squares method theoretically and experimentally with simulated and real measurements. Both methods use  deterministic intervals to denote observation uncertainty, subsequently following a linear uncertainty propagation instead of quadratic one. The interval extension of least-squares transfers the uncertainty into the position domain in the form of zonotope and further bound the stochasticity by the extended point confidence domain. As a comparison, the other method takes advantage of geometrical constraints and convex optimization, leading to a polytopic solution set and zonotopic confidence region. We show their theoretical similarities and highlight different interpretations in practice. Nevertheless, both are sufficient to account for both random and systematic components of uncertainty.