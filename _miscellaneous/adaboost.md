---
title: "Boosting for Time Series and an Application to Value at Risk Forecasting"
authors: Abdou Hamid Alagbe, Rasmane Bamogo and Cédric Beaulac
collection: miscellaneous
permalink: /miscellaneous/adaboost
status : Accepted
date: 2026-05-26
---

Abstract:

*We introduce BlockBoost1, a boosting algorithm for time series forecasting with provable generalization
guarantees. Standard boosting algorithms inherit the i.i.d. assumption of the PAC
learning framework, which temporal dependence violates by design. BlockBoost addresses this
at the algorithmic level by replacing instance-wise weight updates with block-wise updates over
contiguous temporal segments, constraining the weight sequence to a block-constant subspace
of the probability simplex. We prove that this modification drives the block-wise empirical
risk to zero, introduces implicit regularization against noise memorization, and yields a generalization
bound for stationary β-mixing sequences. We further prove that locally stationary
processes – a class encompassing most financial return series – can be approximated in L2 by
a strictly stationary β-mixing process under mild regularity conditions, extending the learning
guarantees to this broader setting. A regression variant, BlockBoost.R2, is derived and applied
to Value at Risk forecasting on four equity indices across three markets: the WAEMU
regional exchange, the CAC 40, and the S&P 500. Evaluated over 2014–2026 via standard
backtesting procedures, BlockBoost achieves superior unconditional coverage at the 5% confidence
level across all markets, with the advantage most pronounced in frontier markets where
parametric distributional assumptions are misspecified. At the 1% level, GARCH models with
heavy-tailed innovations retain an edge, attributable to their capacity to extrapolate into the
extreme tail from limited data. These results establish BlockBoost as a theoretically grounded
and empirically competitive alternative to the GARCH family for financial risk measurement.*

Télécharger [ici](http://cedricbeaulac.github.io/files/Adaboosting_TimeSeries.pdf)
