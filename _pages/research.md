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
  <p>The methodology of Granular Instrumental Variables (GIV) pioneered by Gabaix and Koijen (2024) has become a popular way to estimate causal relationships involving aggregate variables in macro-finance. I study the estimation of such relationships in panels where both the cross section and the time series are large ($N, T \to \infty$). I make two contributions. First, I show that the GIV estimators can consistently recover the parameters of two different equations of interest, and I provide the correct asymptotic theory. Second, I show that GIVs can be weak in the absence of dominant units (lack of granularity), while the parameter of interest remains recoverable.</p>
  <p>To characterize instrument strength when granularity is suspect, I model unit sizes $S_i$ as having a power-law tail, $\Pr(S_i>s)=c s^{-\mu}$, so that the tail index $\mu$ governs the prevalence of dominant units, and thus the strength of the GIV. Three regimes emerge. (i) When $\mu\in(0,1)$, tails are very thick and the instrument is strong: GIV is consistent and asymptotically normal at the standard $\sqrt{T}$ rate. (ii) When $\mu\in(1,2)$, identification is near-weak: validity requires $N/T\to 0$, and asymptotic normality obtains at the slower rate $\sqrt{T}/N^{\,1-1/\mu}$. (iii) When $\mu>2$, tails are too thin to sustain instrument strength and the GIV estimator is inconsistent. I propose weakness-robust inference using an Anderson-Rubin statistic in this regime.</p>
  <p>I apply this theory to estimate supply and demand elasticities in three markets: crude oil, copper, and natural gas. Copper and natural gas have dominant producers, yielding strong GIV. Crude oil has many small producers, leading to slightly weak GIV. All three yield inelastic estimates.</p>
</section>

<h2 class="research-group-title">Working Papers</h2>

<section class="research-section">
  <h3 class="research-title">Optimal Granular Instrumental Variables: Sequential Estimation of Long Panels with Finite Cross Section (with Kenichi Nagasawa and Eric Renault)</h3>
  <p>The methodology of Granular Instrumental Variables (GIV) pioneered by Gabaix and Koijen (2024) offers an exciting way to estimate structural parameters on endogenous variables. Our paper extends this literature to small panels ($N$ fixed and $T \to \infty$) with two main contributions regarding asymptotic inference. First, in the context of a known matrix of factor loadings, we set the general asymptotic theory of efficient GIV, by resorting to the theory of optimal instruments associated to conditional moment restrictions. Second, in the case of unknown factor loadings, we stress that in contrast with efficient estimation of standard conditional moment restrictions, a first step estimator of optimal instruments has an impact on the asymptotic distribution of estimators of structural parameters. We fully characterise this distribution for a GMM estimator and a PCA estimator.</p>
</section>

<section class="research-section">
  <h3 class="research-title">Interactive Fixed Effects with Heterogeneous Parameters (with Kenichi Nagasawa)</h3>
  <p>Bai's (2009) Interactive Fixed Effects estimator is a popular method to estimate parameters in panels with limited endogeneity, but it fails when the parameter of interest varies with individual units. We propose a new estimator that can handle individual heterogeneity using non-parametric estimation.</p>
</section>


