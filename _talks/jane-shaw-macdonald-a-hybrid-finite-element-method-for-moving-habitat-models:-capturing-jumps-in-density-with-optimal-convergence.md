---
speakers:
  - Jane Shaw MacDonald
name: "A Hybrid Finite Element Method for Moving-Habitat Models: Capturing Jumps in Density with Optimal Convergence"
categories:
  - Short Talks
hide: no
---
Moving-habitat models lend insight into the mechanisms promoting a species’ persistence in the face of climate change. We focus on advancing our understanding of such mechanisms by extending the spatial domain to two dimensions and developing a reaction-diffusion system that tracks the species’ density in time over the whole space. The suitable habitat, defined by a positive intrinsic growth rate, is bounded by a closed curve, called the interface, which shifts in time. Across the interface, there is a jump in density resulting from the consideration of habitat-dependent dispersal rates and habitat bias. We introduce a mixed weak formulation for this system, where a dual variable acts as a Lagrange multiplier. For this problem, we construct a finite element method. We prove well-posedness for continuous and discrete cases. In the no-shift case, that is when the suitable habitat is stationary, we derive a priori error estimates for the primal variable. With numerical experiments, we show that even with a non-zero shift, we achieve optimal convergence. For the 1-dimensional system, validated numerical solutions are available. With a 2-dimensional analogue, we validate our numerical solutions against these solutions for a wide set of parameter values. With simulations, we illustrate the strength of our method in furthering the understanding of the impact of climate change on species abundance and persistence.
