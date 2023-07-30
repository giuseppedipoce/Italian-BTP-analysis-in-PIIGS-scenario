# Italian BTP analysis in PIIGS scenario 
<img src="https://github.com/giuseppedipoce/Italian-BTP-analysis-in-PIIGS-scenario/assets/114066138/85dc00a7-df95-48ee-9eb0-6542c8ab8c13" width=55% height=55% align="right">
In this repository you will find a compelling analysis about BTP italian bonds in the sovereign debt crisis of 2011.
There are Rmd code and HTML report attached.
Data are taken from Kaggle and are in the form of time series since 2012 to 2020.

## The project in a nutshell:

In this repository you will find a full Bayesian analysis about Italy prices and yields situation of BTP during sovereign debt crisis of 2011.
The project has been developed for the second part of Statistical Methods for Data Science course with professor Luca Tardella, a fully Bayesian course.
The project is divided in sections, analyzing in the specific just the italian scenario:
- BTP-BUND (SPREAD) analysis with *CHANGE POINT* bayesian models, to understand in what measure Quantitative Easing policy impact the spread;
- Prices Returns *VOLATILITY* analysis witth GARCH moldes;
- Frequentist brief comparison and forecasting.

## *Normals* vs *t-Student*
The aim of this work from a bayesian point of view is to highlight the fact that *GARCH* models are not suitable to model residuals that do not follow a standard normal distribuition.\
In this repo you will find a t-Student alternative approach to avoid this problem.\
The main idea is that in a GARCH model volatility of current time $t$ ($y_t$) is modeled as:\
$y_t=c+\epsilon_t=c+\sqrt{\sigma_t^2} z_t, \quad z_t \sim N(0,1)$\
where residuals $z_t$ are normally distribuited.




<img src="https://github.com/giuseppedipoce/Italian-BTP-analysis-in-PIIGS-scenario/assets/114066138/035a2d97-2e9d-44b9-b3ab-3dd92e27ade3" width=50% height=50% align="center">




As you can notice from the qq-plot above tails of $z_t$ are far from a normal distribution.\
Here we will apply a t-Student distribution to model residuals with a given number of degrees fo freedom.

Don't esitate to get in touch for clarifications and collaboration about it.
- Giuseppe Di Poce ([Linkedin](https://www.linkedin.com/in/giuseppe-di-poce-82a4ba14a/) - [Github](https://github.com/))

## Used technologies
![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
