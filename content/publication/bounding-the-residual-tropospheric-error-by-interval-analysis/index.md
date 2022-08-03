---
title: Bounding the residual tropospheric error by interval analysis
publication_types:
  - "1"
authors:
  - admin
  - schoen
publication: submitted to *International Association of Geodesy Symposia*
abstract: >-
  GNSS integrity monitoring requires proper bounding to characterize all ranging
  error sources. Unlike classical approaches based on probabilistic assumptions,
  our alternative integrity approach depends on deterministic interval bounds as
  inputs.  The intrinsically linear uncertainty propagation with intervals is
  adequate to describe remaining systematic uncertainty, the so-called
  imprecision. 


  In this contribution, we make a proposal on how to derive the required intervals in order to quantify and bound the residual error for empirical troposphere models. We revise and refine the alternative approach based on interval analysis. The sensitivity analysis of the troposphere models is first implemented via interval arithmetic. The resulting sensitivities, together with carefully estimated uncertainties of model influence factors, are used to construct deterministic intervals. To this end, long-term statistics against on-site measurements are performed to estimate the interval bounds of meteorological parameters that are needed as input to the troposphere models. 


  Following this strategy, we evaluated the Saastamoinen model with a priori ISO standard atmosphere. For comparison, results with on-site measurements as inputs are also assessed. To this end, experiments using meteorological data from IGS and Deutscher Wetterdienst (DWD) stations are conducted. We obtain consistent and complete enclosure of residual ZPD errors w.r.t IGS ZPD products. Thanks to the DWD dense network, interval maps for meteorological parameters and residual ZPD errors are generated for Germany as by-products. These experimental results and products are finally validated, taking advantage of the high-quality tropospheric delays estimated by the Vienna Ray Tracer. Overall, the results indicate that our strategy based on interval analysis is feasible for the bounding of tropospheric model uncertainty. This will contribute to a realistic uncertainty assessment of GNSS-based single point positioning.
draft: false
featured: true
tags:
  - troposphere
  - residual tropospheric delay
  - GNSS
  - integrity
  - interval mathematics
  - sensitivity analysis
  - uncertainty modeling
  - error bounding
projects:
  - icsens
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: Distribution of interval bounds for different meteorological parameters
    in Germany
summary: We make a proposal on how to derive the required intervals in order to
  quantify and bound the residual error for empirical troposphere models. We
  revise and refine the alternative approach based on interval analysis. This
  will contribute to a realistic uncertainty assessment of GNSS-based single
  point positioning.
date: 2021-07-01T19:05:41.986Z
links:
  - name: Conference
    url: ""
    icon_pack: fas
    icon: book
  - name: PDF request
    icon_pack: fas
    icon: envelope
    url: mailto:suj@ife.uni-hannover.de
  - name: ResearchGate
    url: ""
    icon_pack: ai
    icon: researchgate
---
