---
speakers:
  - Saifuddin Syed
name: "Scalable Bayesian Inference with Non-Reversible Parallel Tempering"
categories:
  - Prize Lectures
hide: no
---
Markov chain Monte Carlo (MCMC) methods are the most widely used tools in
Bayesian statistics for making inferences from complex posterior distributions. For
challenging problems where the posterior is high-dimensional with well-separated modes,
MCMC algorithms can get trapped exploring local regions of high probability. Parallel
tempering (PT) tackles this problem by delegating the task of global exploration to a
tractable reference distribution (e.g. prior), which communicates to the target (e.g.
posterior) through a sequence of parallel MCMC algorithms targeting distributions of
increasing complexity to the target.

The classical approach to designing PT algorithms relied on a reversibility assumption,
making PT challenging to tune and even deteriorating performance when introducing too
many parallel chains. This talk will introduce a new non-reversible paradigm for PT that
dominates its reversible counterpart while avoiding the performance collapse endemic to
reversible PT methods. We will then establish near-optimal tuning guidelines, an efficient
black-box methodology scalable to GPUs.
