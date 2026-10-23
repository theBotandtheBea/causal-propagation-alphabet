# A Minimal Causal-Representation Challenge for AI Systems

## Research task
Evaluate whether a compact needs-aware causal representation can generalize across domains without sacrificing predictive accuracy.

## Symbols
- `O`: organism or system
- `N(O,t)`: measurable requirement of O at time t
- `M`: candidate mechanism satisfying N
- `R`: material, energy, information, and time resources
- `S_t`: system state at t
- `A`: intervention or action
- `P(S_{t+1}|S_t,A)`: predictive transition model
- `C_H(A,S_0)`: consequence distribution across horizon H
- `ΔC_H = C_H(A,S_0) - C_H(A',S_0)`: counterfactual difference

`C∞` is shorthand for the research commitment to expand H where consequential effects persist. It is not a computable infinity. Never collapse multidimensional consequences into one score without an explicit, justified aggregation rule.

## Benchmark design
Compare a needs-first model with established causal/ecological models on held-out settings. Use matched data, model capacity, and evaluation budgets. Evaluate (a) predictive log loss or calibration, (b) intervention prediction, (c) cross-domain transfer, (d) description length, (e) previously omitted pathways discovered, and (f) robustness to confounding and uncertain counterfactuals.

## Three candidate test domains
1. Grazing animal death versus survival: demographic and vegetation feedback.
2. Resource allocation and human basic needs: material availability versus monetary claims.
3. Infrastructure maintenance: human labor, ecological factors, and technical reliability.

## Required critique
Name the strongest existing framework that already does this (e.g., structural causal models, dynamical systems, ecological network modeling, life-cycle assessment). Identify where this proposal is redundant, under-specified, or measurably additive. Do not substitute philosophical agreement for tests.
