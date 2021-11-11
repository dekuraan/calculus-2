# 11.7 Strategy for Testing Series
Series of the form:
- $\sum\frac{1}{n^p}$ it is a [p series](power_series.md) 
  - convergent if p > 1
  - divergent if p <= 1
- $\sum ar^{n-1}$ or $\sum ar^{n}$
  - converges if |r| < 1
  - diverges if |r| >= 1
- series similar to p-series or geometric series use comparison test
  - asd
- if at a glance $\lim_{n\rightarrow\infin} a_n\ne 0$ then test for divergence should be used
- series that do factorials or constant raised to nth power should be tested with ratio test
- if $a_n$ is of the form $(b_n)^n$ then the root test would be userful
- if $a_n = f(n)$ where $\int_1^\infin f(x)dx$ is easily evaluated then the [[integral_test]] is effective