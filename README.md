---
title: "Panel Data Hausman Test Monte Carlo Simulation"
author: "Carlos Brás"
date: "16 juillet 2018"
output: html_document
---
```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```




Trough a Monte Carlo simulation study I try to investigate the performance under misspecification [Heteroskedasticity(on the individual specific error term and on the remainder error term) and serial correlation] of the Durbin-Wu-Hausman test (and its robust formulation, found in Wooldridge 2002) for correlated effects with panel data.

1 - DGP of the Variable X

I generate the explanatory variable X as the sum of a between (or cross–sectional or permanent) component 


