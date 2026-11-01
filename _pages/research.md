---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 3
---

<h2 class="research-group-title">Job Market Paper</h2>

<section class="research-section">
  <h3 class="research-title">Inference with Granular Instruments in Large Panels</h3>
  <p class="research-links"><a href="https://arxiv.org/abs/2607.02095">arXiv</a> · <a href="https://github.com/gokulgopalan/giv-large-panels-replication">Code</a></p>
  <p>I develop asymptotic theory for Granular Instrumental Variables (GIV) in large panels with both the cross section ($N$) and the time dimension ($T$) growing. The granular instrument is constructed from individual shocks that must be estimated from the panel. I show that this estimation has a first-order effect on the asymptotic variance of the GIV estimator. Existing methods do not account for this effect, leading to incorrect standard errors and invalid inference. I derive corrected standard errors that deliver valid inference. I show that instrument strength can change as the cross section grows. This yields strong, nearly-weak, and weak regimes for GIV. In particular, I identify a previously uncharacterized nearly-weak regime in which the instrument vanishes asymptotically, but GIV remains valid. In this regime, if the time dimension grows sufficiently fast relative to the cross section, the estimator remains consistent and asymptotically normal at a rate slower than $\sqrt{T}$. Further, I characterize the conditions where GIV exhibits standard weak-instrument behavior and provide Anderson&ndash;Rubin confidence intervals. I apply the theory to estimate short-run demand and supply elasticities for copper, natural gas, and crude oil. Across the six elasticities, accounting for instrument estimation changes standard errors by up to a fifth.</p>
</section>

<h2 class="research-group-title">Working Papers</h2>

<section class="research-section">
  <h3 class="research-title">Efficiency of Granular Instrumental Variables and Asymptotic Distributions with Estimated Factor Loadings (with Kenichi Nagasawa and Eric Renault)</h3>
  <p>We study efficiency and inference for granular instrumental variable estimators with a fixed number of cross-sectional units.
    Using optimal instrument results for conditional moment models, we show that the efficient instrument equals the share-weighted granular instrument of Gabaix and Koijen plus an additional term. Using the optimal instrument generally leads to efficiency gains relative to the share-weighted instrument. We also show that a broader class of weights identifies the parameter in the individual-level equations, providing an additional way to improve efficiency. When factor loadings are unknown, we provide conditions under which the loadings and the idiosyncratic error covariance matrix are identified while allowing for cross-sectional heteroscedasticity. We then propose GMM estimators whose inference accounts for the estimation of the factor structure. In an application to the global oil market, we find evidence of heteroscedastic idiosyncratic shocks. We provide estimates of oil demand and supply elasticities using estimators robust to heteroscedasticity.</p>
</section>

<section class="research-section">
  <h3 class="research-title">Interactive Fixed Effects with Heterogeneous Parameters (with Kenichi Nagasawa)</h3>
  <p>We study interactive fixed effects panel models with common time-series regressors whose slope coefficients vary across units. Such heterogeneity is common in applications: for example, a firm's investment response to interest rates may depend on its size or leverage. Identification is challenging because a common regressor with unit-specific slopes has the same form as an unobserved factor with heterogeneous loadings. Separating these components requires additional restrictions, particularly when the regressor is correlated with the latent factors. Existing estimators either impose common slopes or require additional structure to accommodate slope heterogeneity. We propose a computationally tractable semiparametric estimator based on kernel methods to separate the heterogeneous slopes from the factor structure. In this work in progress, we aim to derive the estimator's asymptotic distribution as both the cross section ($N$) and the time dimension ($T$) grow, and characterize how estimation error in the factor structure interacts with bandwidth choice.</p>
</section>


