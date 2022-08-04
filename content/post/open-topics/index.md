---
title: "Open topics for Master Thesis and Studienarbeit "
date: 2022-08-04T11:59:49.032Z
summary: Potential topics for **master's thesis** and **Studienarbeit** at
  Institut für Erdmessung. Master students from Leibniz University Hannover are
  welcome to reach out in case of interest.
draft: false
featured: false
authors:
  - admin
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
  caption: ""
---
As a research staff at[ Institut für Erdmessung (IfE)](https://ife.uni-hannover.de), I am offering opportunities for **master's thesis** and **Studienarbeit**. Students of the master's program *Geodesy and Geoinformation*, as well as other programs at Leibniz University Hannover are welcome to reach out in case of interest.

Currently, the following topics are open, which, nevertheless, are not necessarily predetermined and can be adapted to your own preferences and ideas. All the topics can be taken as either a master's thesis or adapted as a Studienarbeit.

This is a {{< hl >}}highlighted quote{{< /hl >}}.

Please note that I will only supervise **English-written** theses.

![© NASA/Hofmann](https://www.ife.uni-hannover.de/typo3temp/_processed_/1/c/csm_d225b504a2686f8f997ab064cbbb399822e166e9-fp-3-1-0-0_16f4aeaedf.jpg)

# Open Topics

The following topics are open:

 * *High-integrity GNSS/IMU localization using interval analysis* :scroll:
 * *Bounding the residual tropospheric error by interval analysis* :scroll:
 * *Overbounding GNSS/IMU/Odometer integration with applications to urban navigation* :scroll:

- - -

## Topic 1: High-integrity GNSS/IMU localization using interval analysis

#### **Supervisor**

Prof. Steffen Schön 

#### **Co-Supervisor**

Jingyao Su

#### Motivation

Reliable positioning is a key issue for intelligent vehicle navigation. Rather than the classical point estimations, interval-based positioning methods have shown to be capable of computing relevant confidence domains used for integrity monitoring in environments which are challenging for Global Navigation Satellite System (GNSS). GNSS measurements with constraints from 3D-maps, road lanes as well as digital elevation models have been studied by making use of interval analysis to solve the constraint satisfaction problem based on contractions and bisections. By applying the improved observation bounding method developed at IfE, this topic will investigate the uncertainty of nonlinearity of GNSS problems.  GNSS/IMU integration will be taken into consideration for the level of master's thesis. 

#### Tasks

1. Literature review of interval-based localization methods 
2. Understand the method of interval analysis (contraction, set inversion, SIVIA, thick SIVIA)
3. Implementation of SIVIA for GNSS localization
4. Implementation of SIVIA for GNSS/IMU localization
5. Assessment and validation of the results

#### Related Works

* Drevelle, V., & Bonnifait, P. (2011). A set-membership approach for high integrity height-aided satellite positioning. *GPS solutions*, 15(4), 357-368.
* Luc Jaulin, Benoît Desrochers, Simon Rohou, Jordan Ninin, Olivier Reynet. IAMOOC: Interval analysis with applications to parameter estimation and robot localization (url: https://www.ensta-bretagne.fr/jaulin/iamooc.html)

![[Drevelle, 2011] Bird’s eye view of the trajectory. Boxes are bounding boxes of nonrobust solution sets. Reference trajectory is in black](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs10291-010-0195-3/MediaObjects/10291_2010_195_Fig7_HTML.gif)

- - -

## Topic 2: Bounding the residual tropospheric error by interval analysis

#### Supervisor

Prof. Steffen Schön 

#### Co-Supervisor

Jingyao Su

#### Motivation

GNSS integrity monitoring requires proper bounding to characterize all ranging error sources. Unlike classical approaches based on probabilistic assumptions, our alternative integrity approach depends on deterministic interval bounds as inputs. The intrinsically linear uncertainty propagation with intervals is adequate to describe remaining systematic uncertainty, the so-called imprecision. The method of interval analysis can be used to derive the required intervals in order to quantify and bound the residual error for empirical troposphere models. To this end, long-term statistics against on-site measurements should be performed to estimate the interval bounds of meteorological parameters that are needed as input to the troposphere models.

#### Tasks

1. Literature review of troposphere delay, including different empirical models and the modeling methods for the residual tropospheric error. 
2. Statistical analysis of meteorological measurements (climate data, radiosonde data). How to model their uncertainty?
3. Implementation of the interval-based sensitivity analysis for MOPS, GPT2w and ESA tropospheric model.
4. Assessment and validation of the bounding results.

#### Related Works

* Su J., Schön S. (2021): [Bounding the residual tropospheric error by interval analysis](/publication/bounding-the-residual-tropospheric-error-by-interval-analysis/), *IAG 2021 - Scientific Assembly of the International Association of Geodesy*, June 28 - July 2, 2021, Beijing, China
* Rózsa, Szabolcs, et al. "An advanced residual error model for tropospheric delay estimation." *GPS Solutions* 24.4 (2020): 1-15.
* Mendes, V. B. "Modeling the neutral-atmospheric propagation delay in radiometric space techniques." *UNB geodesy and geomatics engineering technical report* (199) 10 (1999).

![](/publication/bounding-the-residual-tropospheric-error-by-interval-analysis/featured.png)

- - -

## Topic 3: Overbounding GNSS/IMU/Odometer integration with applications to urban navigation

#### Supervisor

Prof. Steffen Schön 

#### Co-Supervisor

Jingyao Su

#### Motivation

The integration of GNSS with Inertial Navigation Systems (INS) has the potential to achieve high levels of continuity and availability as compared to standalone GNSS and therefore to satisfy stringent navigation requirements. The integrity of GNSS/INS integration, measuring the trustworthy of navigation solutions, is still to be investigated. This information is very important for safety-critical applications such as civil aviation and autonomous driving. GNSS-alone integrity studies have been developing an overbounding method that bounds the error in range domain, and guarantees the overbound in the position domain. This topic is to apply this method in the analysis for receiver hardware noise and extend to inertial sensors (IMU) and odometer.

#### Tasks

1. Literature review of GNSS/IMU/Odometer uncertainty modeling and bounding methods, including the CDF overbounding, as well as Autocorrelation Function (ACF)/Power Spectral Density (PSD)/Allan Variance methods. What are the advantages and disadvantages for different sensors? 
2. Implementation of overbounding agorithms in MATLAB, such as CDF, ACF, PSD, Allan Variance methods.
3. Data analysis in terms of overbounding hardware noise of different GNSS receivers
4. Data analysis in terms of overbounding uncertainty of IMU/odometer
5. Implementation of a robust extended Kalman filter with augmented state estimation

#### Related Works

* Blanch, Juan, Todd Walter, and Per Enge. "Gaussian bounds of sample distributions for integrity analysis." *IEEE Transactions on Aerospace and Electronic Systems* 55.4 (2018): 1806-1815.
* Langel, Steve, Omar García Crespillo, and Mathieu Joerger. "Overbounding the effect of uncertain Gauss-Markov noise in Kalman filtering." *NAVIGATION, Journal of the Institute of Navigation* 68.2 (2021): 259-276.
* Gallon, Elisa, Mathieu Joerger, and Boris Pervan. "Development of Stochastic IMU Error Models for INS/GNSS Integration." *Proceedings of the 34th International Technical Meeting of the Satellite Division of The Institute of Navigation (ION GNSS+ 2021)*, St. Louis, MI, USA. 2021.

![Error bounding for Accelerometer ](data:image/jpeg;base64,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)