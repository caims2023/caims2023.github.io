---
speakers:
  - Paul Muir
name: "Error Control Software with Event Detection for the Numerical Solution of PDEs"
categories:
  - Short Talks
hide: no
---
This talk will introduce, BACOLIKR, a new software package for the error-controlled numerical solution of 1D time-dependent PDEs that require event detection. For such applications, the user is interested in identifying an unknown time at which some condition involving the solution to the PDE is satisfied. Often, after the event time has been identified, the user is then interested in changing the PDE model and continuing the computation. 

BACOLIKR is based on a modification of the previously developed error-control PDE solver, BACOLI. Both solvers employ adaptive B-spline Gaussian collocation for the spatial discretization; the resultant ODEs in time are coupled with the boundary conditions to give a system of Differential Algebraic Equations (DAEs) which is solved using a DAE solver based on Backward Differentiation Formulas (BDFs). The DAE solver provides temporal error control through adaptive time-stepping and method order selection. The PDE solvers provide spatial error control based on a pair of interpolation-based spatial error estimation schemes. The spatial error control is implemented using adaptive spatial mesh refinement based on the spatial error estimates. The numerical solution for each time step is accepted only if the corresponding error estimates satisfy a user-defined tolerance.

In this talk, we briefly review the underlying algorithms employed in BACOLIKR and then provide numerical results demonstrating how the new software can accurately and efficiently solve PDEs that require event detection. 

