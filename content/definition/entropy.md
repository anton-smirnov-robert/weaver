---
title: "entropy"
date: 2022-12-06
draft: false
tags:
- definition
---

For a given phase space and Hamiltonian, entropies quantifies the number of micro-states available, for a given energy.

#### Details 

In the Gibbs (canonical) ensemble (NVT), the partition function reads $$ Z = \sum_i e^{-\beta E_i} $$an with the probability of the micro-state $i$  being  $p_i=e^{-\beta E_i} / Z$, we have 
$$ S_G=-k_B \sum_i p_i \log(p_i) $$

For a fixed energy, in the micro-canonical ensemble (NVE), the energy is fixed and we get $$ \Omega = \sum_i 1 $$ and Boltzmann's entropy  $$ S_B = k_B \log(\Omega )$$They are equal by restricting the sum for a given energy $E$ in the summation of the (NVT) ensemble. It gives $Z=e^{-\beta E}\Omega$ and $S_G = S_B$.
