---
layout: archive
title: "Codes"
permalink: /codes/
author_profile: true
sitemap: false
---


I  design  open-source  Python  statistical packages  for  central  banks  and
economists in general, in the area  of forecasting and financial modeling. One
of my most  recent packages, based on  Adrian et al. (AER  2019) on estimating
Growth-at-Risk, is used by more than twenty central banks in the world.

The packages  are freely available  through Github. Please cite  the companion
working paper when using the tools.

**Disclaimer**: Reuse  of these tools  does not  imply any endorsement  of the
research and/or  product.  Any  research presented should  not be  reported as
representing the views of the IMF, its Executive Board, or member governments.


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


### Conditional Density Projection via Quantile Regressions, Resampling and Multifit Models
* [Github repo](https://github.com/romainlafarguette/gar)

* Python module to project a conditional density using quantile regressions,
  resampling and different density fit strategies (Resampling, Kernel,
  Gaussian Mixtures, etc.)
  
* Working paper coming out soon


### Robust Density with Over-Parametrized Models
* [Github repo](https://github.com/romainlafarguette/robustdensity)

* Estimate a Conditional Skew Normal using robust estimators (Theil-Sen and Firth Logistic Regressions) and an over-parametrized model.

* Useful for small and/or noisy observational samples

* Working paper to arrive soon

### Partial Least Squares Wrapper for Data Reduction based on Scikit
* [Github repo](https://github.com/romainlafarguette/plswrapper)

* A wrapper based on Scikit to use a Partial Least Square estimator to conduct
  data reduction. 
  
* Includes new functionalities such as variable influence in the projection
  computation, selection on top contributors and a few charting tools


### Granular Instrumental Variables from Gabaix and Koijen (2020)
* [Github repo](https://github.com/romainlafarguette/granulariv)
* Python module to estimate the Granular Instrumental Variables from Gabaix
  and Koijen (2020)
  
* The panel regressions are based on linearmodels from Kevin Sheppard

### Quantile Spacing from Schmidt and Zhu (2016)
* [Github repo](https://github.com/romainlafarguette/quantilespacing)
* Python module to estimate Quantile Spacing from Schmidt and Zhu (2016)

### Cluster Analysis Wrapper with Performance Metrics and Visualization Tools
* [Github repo](https://github.com/romainlafarguette/clusterwrapper)
* Python wrapper to conduct data clustering, with performance metrics and
  visualization tools. Based on Scikit









