# statrs  
  
[![Build Status](https://travis-ci.org/boxtown/statrs.svg?branch=master)](https://travis-ci.org/boxtown/verto)  
  
A work-in-progress port of the Math.NET Numerics distributions package to Rust.  
All unit tests are borrowed from the Math.NET source when possible and filled in  
when not.  

## Planned for v 0.1.0

| Distribution      | Implemented | Doc Comments |
|-------------------|:-----------:|:------------:|
| Bernoulli         | yes         | no           |
| Binomial          | yes         | no           |
| Chi               | yes         | no           |
| ChiSquared        | yes         | no           |
| ContinuousUniform | yes         | no           |
| DiscreteUniform   | yes         | no           |
| Exponential       | yes         | no           |
| Gamma             | yes         | no           |
| LogNormal         | yes         | no           |
| Normal            | yes         | no           |
| Poisson           | yes         | no           |
| StudentT          | yes         | no           |
| Triangular        | yes         | no           |
| Weibull           | yes         | no           |

## Planned for v 0.1.1
| Distribution      | Implemented | Doc Comments |
|-------------------|:-----------:|:------------:|
| Beta              | no          | no           |

Tests for special functions:
- [ ] ln_beta
- [ ] beta
- [ ] beta_reg
- [ ] erf
- [ ] erf_inv
- [ ] erfc
- [ ] erfc_inv
- [ ] polynomial
- [ ] series
- [ ] factorial
- [ ] ln_factorial
- [ ] binomial
- [ ] ln_binomial
- [ ] ln_gamma
- [ ] gamma
- [ ] gamma_ui
- [ ] gamma_li
- [ ] gamma_ur
- [ ] gamma_lr
- [ ] digamma
- [ ] exp_minus_one

## Future roadmap
- [ ] Categorical
- [ ] Cauchy
- [ ] Dirichlet
- [ ] Erlang
- [ ] FisherSnedecor
- [ ] HyperGeometric
- [ ] InverseGamma
- [ ] InverseWishart
- [ ] Laplace
- [ ] Multinomial
- [ ] NegativeBinomial
- [ ] NormalGamma
- [ ] Pareto
- [ ] Rayleigh
- [ ] Stable
- [ ] Wishart
- [ ] Zipf
