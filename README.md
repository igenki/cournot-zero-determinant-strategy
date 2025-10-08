# Simulation codes for “Autocratic strategies in Cournot oligopoly games”

This repository contains all simulation codes used in the paper:

> *Autocratic strategies in Cournot oligopoly games*,  
> [arXiv:2506.16038](https://arxiv.org/abs/2506.16038)

The simulations explore how *autocratic (zero-determinant)* strategies operate in repeated Cournot competition with different numbers and types of opponents.  
Each Jupyter notebook corresponds to one or more figures in the paper.

---

## Repository Structure

| File name | Corresponding figure | Description |
|------------|----------------------|--------------|
| **`linear_relationship_fixed_opponent.ipynb`** | **Fig. 1** | Simulates the linear payoff relationship enforced by a ZD (autocratic) player against a fixed-quantity (memory-0) opponent in the repeated Cournot oligopoly. |
| **`random_memory1_opponent.ipynb`** | **Fig. 2** | Tests the same ZD condition against many randomly generated memory-1 opponents, confirming that the expected payoffs still lie on a straight line. |
| **`duopoly_adaptation.ipynb`** | **Fig. 3 & SI1** | Simulates adaptive learning in a duopoly where the ZD player interacts with one adaptive opponent. Shows how the opponent's strategy evolves and how both players' payoffs change over time. |
| **`triopoly_adaptation.ipynb`** | **Fig. 4** | Extends the adaptive learning scenario to a triopoly (three firms). Two adaptive players interact with one autocratic (fair-ZD) player. The results illustrate that cooperation (collusion) does not emerge as easily as in the duopoly. |
| **`triopoly_grim_trigger.ipynb`** | **Fig. SI2** | Simulation in which two adaptive players employ **Grim/Trigger** strategies in the triopoly setting. |
| **`two_adaptive_players.ipynb`** | **Fig. SI3** | Control case **without any autocratic player**: only two adaptive players compete and co-evolve their strategies. |
| **`plot_results_analysis.ipynb`** | — | Aggregates data from simulation results and generates all plots of strategies and average payoffs used in the main and supplementary figures. |

---
