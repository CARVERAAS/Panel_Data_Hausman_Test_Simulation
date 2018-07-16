 # Panel Data Hausman Test Monte Carlo Simulation
 Trough a Monte Carlo simulation study I try to investigate the performance under misspecification [Heteroskedasticity(on the individual specific error term and on the remainder error term) and serial correlation] of the Durbin-Wu-Hausman test (and its robust formulation, found in Wooldridge 2002) for correlated effects with panel data.
 ## 1 - DGP of the Variable X
I generate the explanatory variable **X** as the sum of a between (or cross–sectional or permanent) component <a href="http://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;\xi_{i}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;\xi_{i}" title="\LARGE \xi_{i}" /></a> and a within (or time series or time varying) component <a href="http://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;\xi_{it}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;\xi_{it}" title="\LARGE \xi_{it}" /></a>. We suppose that the between component <a href="http://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;\xi_{i}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;\xi_{i}" title="\LARGE \xi_{i}" /></a> is itself the sum of an exogenous sub-component <a href="http://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;\xi_{i}^{e}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;\xi_{i}^{e}" title="\LARGE \xi_{i}^{e}" /></a> and a correlated on <a href="http://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;\xi_{i}^{c}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;\xi_{i}^{c}" title="\LARGE \xi_{i}^{c}" /></a>  (i.e., correlated with the individual effect <a href="http://www.codecogs.com/eqnedit.php?latex=\inline&space;\LARGE&space;\alpha_{i}" target="_blank"><img src="http://latex.codecogs.com/gif.latex?\inline&space;\LARGE&space;\alpha_{i}" title="\LARGE \alpha_{i}" /></a> in the regression model). And we have:


Name | Lunch order | Spicy      | Owes
------- | ---------------- | ---------- | ---------:
Joan  | saag paneer | medium | $11
Sally  | vindaloo        | mild       | $14
Erin   | lamb madras | HOT      | $5









