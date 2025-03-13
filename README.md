# Stablecoin Portfolio Optimization using Hierarchical Risk Parity (HRP)
## Overview
This project applies Hierarchical Risk Parity (HRP), as introduced by Marcos López de Prado, to optimize a stablecoin basket allocation. HRP improves upon traditional portfolio allocation methods (e.g., Mean-Variance Optimization, Equal-Weight, or Risk Parity) by clustering assets based on correlation structures and dynamically distributing risk across independent groups.

By using HRP, this model minimizes systemic risk while ensuring stable and robust allocations across multiple stablecoins.

## Key Features
- Hierarchical Clustering of Stablecoins: Groups stablecoins based on correlation patterns.
- Risk-Based Allocation: Assigns weights to minimize over-exposure to highly correlated assets.
- No Inversion of Covariance Matrix: Works well even with highly correlated stablecoins.
- Dynamic Portfolio Adjustments: Can rebalance allocations as stablecoin correlations change.
