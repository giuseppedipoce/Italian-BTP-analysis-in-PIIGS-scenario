# Italian BTP analysis in PIIGS scenario 

In this repository you will find a compelling analysis about BTP italian bonds in the sovereign debt crisis of 2011.
There are Rmd code and HTML report attached.
Data are taken from Kaggle and are in the form of time series since 2012 to 2020.

<img src="https://github.com/giuseppedipoce/Italian-BTP-analysis-in-PIIGS-scenario/assets/114066138/85dc00a7-df95-48ee-9eb0-6542c8ab8c13" width=55% height=55% align="right">

## The project in a nutshell:

In this repository you will find a full Bayesian analysis about Italy prices and yields situation of BTP during sovereign debt crisis of 2011.
The project has been developed for the second part of Statistical Methods for Data Science course with professor Luca Tardella, a fully Bayesian course.
The project is divided in sections, analyzing in the specific just the italian scenario:
- BTP-BUND (SPREAD) analysis with *CHANGE POINT* bayesian models, to understand in what measure Quantitative Easing policy impact the spread;
- Prices Returns *VOLATILITY* analysis witth GARCH moldes;
- Frequentist brief comparison and forecating.

## Comments about results
The aim of this work from a bayesian point of view is to highlight the fact that *GARCH* models are not suitable to model residuals that do not follow a standard normal distribuition.
In this repo you will find a t-Student alternative approach to avoid this problem.
Thhe main idea is that in a GARCH(1,1) model:

$y_t=c+\epsilon_t=c+\sqrt{\sigma_t^2} z_t, \quad z_t \sim N(0,1)$

Don't esitate to get in touch for clarifications and collaboration about it.

## Used technologies
![RStudio](https://img.shields.io/badge/RStudio-4285F4?style=for-the-badge&logo=rstudio&logoColor=white)
![R](https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white)
