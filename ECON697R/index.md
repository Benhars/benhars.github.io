---
layout: page
title: Advanced Studies in Counterfactual Analysis
---

**ECON 697R · Emory University, Spring 2025**

[**Modules**](/ECON697R/modules/){: style="font-size: 1.1em;"}

---

## About

This Directed Study is designed to be an intensive reading in econometrics on a topic not covered in a regular course at Emory University. This course explores a variety of topics in counterfactual analysis with applications in causal inference literature. The course is based on student presentations and discussions among participants (students and faculty invited).

## Course Description

This reading study session explores the theoretical foundations, methodological advancements, and practical applications of counterfactual analysis in causal inference in depth. The course builds from the basic principles to advanced topics, incorporating sensitivity analyses, handling nonstationary data, and implementing counterfactual models.

## Content

### Topic 1: The Journey of Counterfactual Analysis

- Conceptual basis of causality from structural and potential outcomes traditions
- Perspectives of Pearl (2009) and Imbens and Rubin (2015)
- The role of thought experiments in econometric causality
- The problem of missing counterfactuals, selection bias, and confounding
- Broad overview of major causal inference designs

### Topic 2: From Causal Inference to Dynamic Systems and an Introduction to Synthetic Control

- Potential-outcomes framework for dynamic systems
- Dynamic causal effects and impulse response functions
- Conditions under which these objects admit a causal interpretation
- Synthetic control methods for aggregate interventions with limited overlap
- Basic setup, estimation, empirical implementation, and placebo-based inference

### Topic 3: Counterfactual Imputation under Predictable Errors

- Limitations of traditional SCM: poor pre-treatment fit, overfitting, nonstationarity, dependence
- The Artificial Counterfactual (ArCo) estimator for high-dimensional panel time-series data
- Predictable imputation errors: serial correlation, cross-sectional dependence, model misspecification
- Practical Unbiased Predictors (PUP/PLUP) for correcting nonspherical error structures
- Comparisons to FarmTreat, ArCo, and extensions based on VAR and factor-augmented models

### Topic 4: Research Proposal — Extending Synthetic Control to Dynamic Treatment Effects

- Limitations of traditional SCM for estimating dynamic causal effects of one-time interventions
- Panel-data framework for estimating how effects of a one-time shock propagate over time
- Identification through counterfactual imputation
- Two-stage estimation strategy with latent factors and autoregressive dynamics
- Consistency and asymptotic normality under iid and correlated error structures
- Empirical motivation from natural disasters and macroeconomic stimulus shocks

### Topic 5: Difference-in-Differences with Multiple Time Periods

- Canonical 2 × 2 DiD framework: potential outcomes, no-anticipation, and parallel trends
- Event-study and staggered-adoption designs
- Limitations of two-way fixed effects estimators under heterogeneous treatment effects
- Callaway and Sant'Anna framework: group-time average treatment effects ATT(g, t)
- Identification under alternative comparison groups, role of covariates
- Aggregation schemes, estimation, and inference

## References

- Abadie, A. & Gardeazabal, J. (2003). The economic costs of conflict: A case study of the Basque Country. *American Economic Review*, 93(1), 113–132.
- Abadie, A., Diamond, A., & Hainmueller, J. (2010). Synthetic control methods for comparative case studies. *JASA*, 105(490), 493–505.
- Angrist, J. D., Jordà, Ò., & Kuersteiner, G. M. (2018). Semiparametric estimates of monetary policy effects: String theory revisited. *JBES*, 36(3), 371–387.
- Ballinari, D. & Wehrli, A. (2024). Semiparametric inference for impulse response functions using double/debiased machine learning. *arXiv:2411.10009*.
- Gonçalves, S. & Ng, S. (2024). Imputation of counterfactual outcomes when the errors are predictable: Rejoinder. *JBES*, 42(4), 1140–1142.
- Heckman, J. & Pinto, R. (2024). Econometric causality: The central role of thought experiments. *Journal of Econometrics*, 105719.
- Imbens, G. W. & Rubin, D. B. (2015). *Causal Inference in Statistics, Social, and Biomedical Sciences*. Cambridge University Press.
- McDonald, R. P. (2002). Review of Pearl's *Causality*. *Psychometrika*, 67(2), 321–322.
- Medeiros, M. C. (2024). Counterfactual imputation. *JBES*, 42(4), 1128–1132.
- Pearl, J. (2009). *Causality*. Cambridge University Press.

## Acknowledgments
I thank Prof.[David Jacho-Chávez](https://www.davidjachochavez.org/){:target="_blank"}for his guidance and for serving as Faculty Sponsor in developing this course.
