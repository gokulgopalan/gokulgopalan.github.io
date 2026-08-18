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
  <h3 class="research-title">Granular Instrumental Variables in Large Panels: Identification and Inference Across Strong, Nearly Weak, and Weak GIV</h3>
  <p class="research-links"><a href="https://arxiv.org/abs/2607.02095">arXiv</a></p>
  <p>The methodology of Granular Instrumental Variables (GIV) pioneered by Gabaix and Koijen (2024) has become a popular way to estimate causal relationships involving aggregate variables in macro-finance. I study the estimation of such relationships in panels where both the cross section and the time series are large ($N, T \to \infty$). I make two contributions. First, I show that the GIV estimators can consistently recover the parameters of two different equations of interest, and I provide the correct asymptotic theory. Second, I show that GIVs can be weak in the absence of dominant units (lack of granularity). I provide the conditions under which we can recover the parameter of interest, even with a weak GIV.</p>
  <p>I find three distinct regimes associated with the strength of the GIV. First, when a few units dominate the aggregate, the instrument is strong. The GIV estimator is consistent and asymptotically normal at the standard $\sqrt{T}$ rate. Second, when large units stand out but do not dominate, the instrument weakens. But if the sample size ($T$) is larger than the cross-section ($N$), then the GIV estimator remains consistent and asymptotically normal, now at a rate slower than $\sqrt{T}$. Finally, when units are comparable in size and none stands out, the instrument is weak in the standard sense. Here the relative growth of $T$ and $N$ decides the outcome. If $N$ grows in proportion to $T$, the GIV estimator is inconsistent and has a non-standard distribution.</p>
  <p>Across all three regimes, the first-stage construction of the GIV has a first-order effect on the asymptotic variance of the estimator. Standard error that do not account for this first-order effect can under-cover or over-cover. I apply this theory to estimate supply and demand elasticities in three markets: crude oil, copper, and natural gas. Copper and natural gas have dominant producers, yielding strong GIV. Crude oil has many small producers, leading to slightly weak GIV. All three yield inelastic estimates. Across the six elasticities the correction moves standard errors by up to a fifth, in both directions.</p>
</section>

<h2 class="research-group-title">Working Papers</h2>

<section class="research-section">
  <h3 class="research-title">Optimal Granular Instrumental Variables: Sequential Estimation of Long Panels with Finite Cross Section (with Kenichi Nagasawa and Eric Renault)</h3>
  <p>The methodology of Granular Instrumental Variables (GIV) pioneered by Gabaix and Koijen (2024) offers an exciting way to estimate structural parameters on endogenous variables. Our paper extends this literature to small panels ($N$ fixed and $T \to \infty$) with two main contributions regarding asymptotic inference. First, in the context of a known matrix of factor loadings, we set the general asymptotic theory of efficient GIV, under the theory of optimal instruments associated to conditional moment restrictions. Second, in the case of unknown factor loadings, we find that in contrast with efficient estimation of standard conditional moment restrictions, a first step estimator of optimal instruments has an impact on the asymptotic distribution of estimators of structural parameters. We fully characterise this distribution for a GMM estimator and a PCA estimator.</p>
</section>

<section class="research-section">
  <h3 class="research-title">Interactive Fixed Effects with Heterogeneous Parameters (with Kenichi Nagasawa)</h3>
  <p>Bai's (2009) Interactive Fixed Effects estimator is a popular method to estimate parameters in panels with limited endogeneity, but it fails when the parameter of interest varies with individual units. We propose a new estimator that can handle individual heterogeneity using non-parametric estimation.</p>
</section>


