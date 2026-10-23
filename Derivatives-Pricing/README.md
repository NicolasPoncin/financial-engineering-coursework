# Derivatives Pricing and Dynamic Replication

- **School:** Louvain School of Management (LSM)
- **Programme:** Master in Financial Engineering
- **Course:** Derivatives Pricing
- **Professor:** Frédéric Vrins
- **Teaching assistant:** Rodolphe Vanderveken
- **Academic year:** 2025–2026 (M1)
- **Authors:** Nicolas Poncin and Basile Houriez


## Overview

This project studies the pricing, sensitivity analysis, replication and hedging of two volatility-sensitive payoff structures:

\\[\\psi\_T^a = |S\_T-K|\\]

and

\\[\\psi\_T^q = (S\_T-K)^2.\\]

The absolute payoff corresponds to a straddle and grows linearly with the distance from the strike. The quadratic payoff is more strongly convex and provides greater exposure to large movements in the underlying asset.

## Main Methods

- Monte Carlo pricing under the Black–Scholes framework.
- Numerical integration using the lognormal distribution of the terminal asset price.
- Analytical pricing of the absolute and quadratic payoffs.
- Sensitivity analysis with respect to \\(S\_0\\), \\(K\\), \\(T\\), \\(\\sigma\\), and \\(r\\).
- Analytical Delta calculations.
- Dynamic Delta hedging and replication.
- Hedging-error analysis under discrete rebalancing.
- Transaction-cost analysis.
- Delta–Gamma hedging and adaptive rebalancing extensions.

## Main Findings

The quadratic payoff has a substantially higher theoretical premium because of its stronger convexity and sensitivity to large price movements. However, this same convexity produces larger Delta changes, higher hedging errors and significantly greater transaction costs.

Under the assumptions considered in the project, the absolute payoff provides a more efficient compromise between theoretical exposure, replication accuracy, transaction costs and operational simplicity.

## Repository Content

- `report.pdf`: final project report.
- `Derivatives_Pricing_code.ipynb`: Python notebook handed to the professor containing the pricing, sensitivity and hedging analyses as well as stylised plots. 
- `extension.ipynb`: Python notebook proposing an extension of the work. 

## Contribution

This was a group project completed with Basile Houriez in August 2026. The work was collaborative, and the repository should not be interpreted as entirely individual work.

## Note on AI Assistance

AI tools were used in a limited supporting role for Python implementation, language correction and presentation. The mathematical developments, modelling choices, financial reasoning, analysis and conclusions were developed and reviewed by the authors.
