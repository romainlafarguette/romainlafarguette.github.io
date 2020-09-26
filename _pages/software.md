---
layout: archive
title: "Statistical Software Development"
permalink: /software/
author_profile: true
sitemap: false
---


I design open-source Python statistical packages for central banks and economists in
general, in the area of forecasting and financial modeling. One of my most recent packages, on estimating
Growth-at-Risk, is used by more than twenty central banks in the world. 

The packages are freely available through Github. Please cite the companion working
paper when using the tools. 


### Growth at Risk: Density Forecasting via Quantile Regressions and Parametric Fit (with Changchun Wang)
* [Github repo](https://github.com/IMFGAR/GaR)
* Python package and Excel tool to estimate the Growth-at-Risk model, which is a
  density forecasting model based on quantile regressions and parametric
  fit. Changchun Wang (also at the IMF) designed the Excel-Python interface

    * Developped at the International Monetary Fund, from the seminal paper of
    Adrian et al. (2019) *Vulnerable Growth*, American Economic Review. I have
    incorporated a significant number of improvements to make GaR applicable
    to a wide range of countries, including emerging markets and countries
    with data limitations. 
    
    * Used by more than twenty central banks in the world (either the Excel
      tool developped by Changchun or the pure Python scripts I wrote)

    * Please cite our working paper presenting the toolkit and applications Growth-at-Risk: Concept and Application in
      IMF Country Surveillance (2019), [IMF Working Paper No. 19/36](https://www.imf.org/en/Publications/WP/Issues/2019/02/21/Growth-at-Risk-Concept-and-Application-in-IMF-Country-Surveillance-46567)


### Distributional GaRCH model to design VaR-based FX Interventions for Central Banks
* [Github repo](https://github.com/romainlafarguette/varfxi)
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
* [Github repo](https://github.com/romainlafarguette/quantileproj)  
* Python module to estimate quantile local projections, and produce useful
  outputs for economists
  
  * Based on the QuantileReg package from statsmodels and my conditional quantile
  sampling module (https://github.com/romainlafarguette/cqsampling)

  * The quantile uncrossing part is based on either:
      * Chernozhukov et al. (2010) Quantile and Probability Curves Without Crossing, Econometrica
      * Schmidt and Zhu (2016), Quantile Spacings: A Simple Method for the Joint Estimation of Multiple Quantiles Without Crossing








