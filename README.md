# Panel_Data_Hausman_Test_Simulation
Trough a Monte Carlo simulation study I try to investigate the performance under misspecification [Heteroskedasticity(on the individual specific error term and on the remainder error term) and serial correlation] of the Durbin-Wu-Hausman test (and its robust formulation, found in Wooldridge 2002) for correlated effects with panel data.

1 - DGP of the Variable X

I generate the explanatory variable X as the sum of a between (or cross–sectional or permanent) component 


---
title: "Panel Data Monte Carlo Simulation"
author: "Carlos Brás"
date: "16 juillet 2018"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
