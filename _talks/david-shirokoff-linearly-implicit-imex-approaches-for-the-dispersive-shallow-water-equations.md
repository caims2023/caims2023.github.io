---
speakers:
  - David Shirokoff
name: "Linearly Implicit IMEX Approaches for the Dispersive Shallow Water Equations"
categories:
  - Short Talks
hide: no
---
This talk will focus on developing time integration strategies for the dispersive shallow water equations (DSWE)—which are fluid models, applicable to coastal regions that include additional physics (such as dispersion) to the well-known shallow water equations. The DSWEs contain nonlinear, "mixed" space and time derivatives that create computational challenges in the numerical time integration of the equations. We devise a constant coefficient preconditioner that may be used to handle the time integration of the mixed derivative terms in the DSWE via preconditioned Krylov methods.  A key feature of the approach is that the results may be applied to varying bottom topographies.  Concepts from the preconditioner also enable the development of computationally advantageous IMEX approaches that treat some terms in the time integration implicitly (Im) and others explicitly (Ex).
