 # Panel Data Hausman Test Monte Carlo Simulation
 Trough a Monte Carlo simulation study I try to investigate the performance under misspecification [Heteroskedasticity(on the individual specific error term and on the remainder error term) and serial correlation] of the Durbin-Wu-Hausman test (and its robust formulation, found in Wooldridge 2002) for correlated effects with panel data.
 ## 1 - DGP of the Variable X
I generate the explanatory variable X as the sum of a between (or cross–sectional or permanent) component 

<math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
  <mi>x</mi>
  <mo>=</mo>
  <mrow class="MJX-TeXAtom-ORD">
    <mfrac>
      <mrow>
        <mo>&#x2212;<!-- − --></mo>
        <mi>b</mi>
        <mo>&#x00B1;<!-- ± --></mo>
        <msqrt>
          <msup>
            <mi>b</mi>
            <mn>2</mn>
          </msup>
          <mo>&#x2212;<!-- − --></mo>
          <mn>4</mn>
          <mi>a</mi>
          <mi>c</mi>
        </msqrt>
      </mrow>
      <mrow>
        <mn>2</mn>
        <mi>a</mi>
      </mrow>
    </mfrac>
  </mrow>
  <mo>.</mo>
</math>
