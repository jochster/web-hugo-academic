---
title: "Open topics for Master Thesis and Studienarbeit "
date: 2022-08-04T11:59:49.032Z
summary: Potential topics for **master's thesis** and **Studienarbeit** at
  Institut für Erdmessung. Master students from Leibniz University Hannover are
  welcome to reach out in case of interest.
draft: true
featured: false
authors:
  - admin
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
As a research staff at Institut für Erdmessung (IfE), I am offering opportunities for **master's thesis** and **Studienarbeit**. Students of the master's program *Geodesy and Geoinformation*, as well as other programs at Leibniz University Hannover are welcome to reach out in case of interest.

Currently, the following topics are open, which, nevertheless, are not necessarily predetermined and can be adapted to your own preferences and ideas. 

Please note that I will only supervise English-written theses.

![](https://www.ife.uni-hannover.de/typo3conf/ext/luh_website/Resources/Public/Images/Logo/luh_logo.svg)

# Topics

## Topic 1: High-integrity GNSS/IMU localization using interval analysis

#### **Supervisor**

Prof. Steffen Schön 

#### **Co-Supervisor**

Jingyao Su

#### Motivation



#### Tasks



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