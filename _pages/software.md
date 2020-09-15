---
layout: archive
title: "Software development"
permalink: /software/
author_profile: true
---

### Growth at Risk: Density Forecasting via Quantile Regressions and Parametric Fit
* [Github link](https://github.com/IMFGAR/GaR)
* Python package and Excel tool to estimate the Growth-at-Risk model, which is a
  density forecasting model based on quantile regressions and parametric fit

    * Developped at the International Monetary Fund, from the seminal paper of
    Adrian et al. (2019) *Vulnerable Growth*, American Economic Review 

### Distributional GaRCH model to design VaR-based FX Interventions for Central Banks
* [Github link](https://github.com/romainlafarguette/varfxi)
* Python module to estimate conditional densities from a GaRCH model and design
  VaR-based intervention FX interventions areas for central banks
  
  *  The paper  uses  a Python  package  that I  have  written, DistGARCH,  also
  available on  my Github page,  with the public  FX intervention data  from the
  Banco Mexico. DistGARCH is based on the ARCH package of Kevin Sheppard.
  
  * You  can use the  code for  non-commercial applications, providing  that you
  cite the  IMF Working Paper  Lafarguette, R.  and Veyrune, R.  (2020) "Foreign
  Exchange Interventions Rules  for Central Banks: A  Risk-Based Framework", IMF
  Working Paper

### Quantile Local Projections
* [Github link](https://github.com/romainlafarguette/quantileproj)  
* Python module to estimate quantile local projections, and produce useful
  outputs for economists
  
  * Based on the QuantileReg package from statsmodels and my conditional quantile
  sampling module (https://github.com/romainlafarguette/cqsampling)

    * The quantile uncrossing part is based on either:
        * Chernozhukov et al. (2010) Quantile and Probability Curves Without Crossing, Econometrica
        * Schmidt and Zhu (2016), Quantile Spacings: A Simple Method for the Joint Estimation of Multiple Quantiles Without Crossing








