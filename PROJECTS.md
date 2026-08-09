# Project-by-Project Technical Summary

## Assignment 1 — Numerical Curve Methods

Implemented piecewise-constant interpolation with controlled extrapolation, exact interval integration, and analytic derivatives with respect to curve ordinates. The notebook compares closed-form gradients with bump-and-revalue results.

**Evidence of skill:** numerical methods, vectorized NumPy, boundary handling, sensitivity derivation, numerical validation.

## Assignment 2 — RFR Swap Construction

Converted market conventions and date schedules into fixed and compounded overnight cash-flow streams, then composed the legs into an RFR swap. Also implemented a reusable option-strategy registry and arithmetic composition interface.

**Evidence of skill:** fixed-income product modeling, schedule conventions, configuration-driven registries, object-oriented design.

## Assignment 4 — Product Reporting

Applied visitor and single-dispatch patterns to produce consistent tabular reports for bullet cash flows, fixed-accrual cash flows, overnight cash flows, RFR swaps, and nested portfolios.

**Evidence of skill:** design patterns, typed dispatch, recursive structures, separation of domain and presentation logic.

## Assignment 5 — PCA Hedging

Built PCA directly from covariance eigendecomposition for 1Y–30Y swap-rate changes. Retained three dominant factors explaining more than 99% of sample variation and solved hedge positions by least squares.

**Evidence of skill:** statistical risk modeling, eigendecomposition, factor interpretation, hedge optimization, residual-risk analysis.

## Assignment 6 — Overnight Basis Swap

Extended the framework with a SOFR/Fed Funds basis-swap product, public construction API, valuation registration, PV and cash aggregation, par-spread calculation, PV01, and cash-flow reporting.

**Evidence of skill:** multi-leg rate products, curve-based valuation, par analytics, state-variable sensitivities, portfolio reporting.

## Assignment 7 — Black-76 and Bachelier Analytics

Implemented European call/put prices, forward delta, gamma, vega, implied-volatility inversion, and price-equivalent conversion between normal and lognormal volatility quotes.

**Evidence of skill:** stochastic-model formulas, probability distributions, numerical root finding, Greek validation.

## Assignment 8 — SABR Distribution Analytics

Implemented alpha/ATM-volatility conversion, SABR parameter sensitivities, option-implied density extraction, negative-density diagnostics, correlated Euler–Maruyama simulation, and quantile mapping.

**Evidence of skill:** volatility modeling, finite differences, stochastic simulation, distribution diagnostics, empirical mapping.

## Assignment 9 — SOFR Caplet/Cap and SABR Risk

Added RFR caplet and cap products, SABR parameter-surface access, two-dimensional interpolation gradients, lifecycle-aware valuation, and cap-level aggregation. Propagated curve and volatility sensitivities into first-order risk reports and compared them with bump-and-revalue calculations.

**Evidence of skill:** rate-option architecture, volatility surfaces, lifecycle valuation, chain-rule risk propagation, model validation.
