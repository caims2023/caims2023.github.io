---
speakers:
  - Scott MacLachlan
name: "Monolithic Multigrid Preconditioners for High-Order Discretizations of the Navier-Stokes Equations"
categories:
  - Short Talks
hide: no
---
Recent years have seen substantial interest in the development of high-order spatial discretizations for the Navier-Stokes equations, using either Scott-Vogelius elements (on suitable meshes) or H(div)-conforming elements to achieve high-order discretizations that strongly enforce the incompressibility constraint. For time-dependent problems, a further complication comes from achieving similar higher-order accuracy for an implicit time-stepping scheme while maintaining optimal cost per time-step, roughly proportional to the number of spatial degrees of freedom. In this talk, we present simulation results using Firedrake for an H(div)-conforming spatial discretization and Irksome for fully implicit Runge-Kutta temporal discretizations, using PETSc’s PCPatch to define an effective block relaxation scheme for monolithic multigrid applied to the Jacobians of the resulting time-stepping scheme. We show that the scheme is robust in order, and discuss how the cost-per-timestep changes with spatial and temporal resolutions and discretization orders.
