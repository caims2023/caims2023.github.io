---
speakers:
  - Milan Klöwer
name: "Does it though? Periodic orbits in chaotic systems simulated at low precision"
categories:
  - Short Talks
hide: no
---
Non-periodic solutions are an essential property of chaotic dynamical systems. Simulations with deterministic finite-precision numbers, however, always yield orbits that are eventually periodic. With double-precision 64-bit floating-point numbers such periodic orbits are typically negligible due to very long periods. The emerging trend to accelerate simulations with low-precision numbers, such as 16-bit half-precision floats, raises questions on the fidelity of such simulations of chaotic systems. Here, we revisit the 1-variable logistic map and the generalised Bernoulli map with various number formats and precisions: floats, posits and logarithmic fixed-point. Simulations are improved with higher precision but stochastic rounding prevents periodic orbits even at low precision. For larger systems the performance gain from low-precision simulations is often reinvested in higher resolution or complexity, increasing the number of variables. In the Lorenz 1996 system, the period lengths of orbits increase exponentially with the number of variables. Moreover, invariant measures are better approximated with an increased number of variables than with increased precision. Extrapolating to large simulations of natural systems, such as million-variable climate models, periodic orbit lengths are far beyond reach of present-day computers. Such orbits are therefore not expected to be problematic compared to high-precision simulations but the deviation of both from the continuum solution remains unclear.
