---
speakers:
  - Siqi Wei
name: "Qualitative Property Preservation of High-Order Operator Splitting for the SIR Model"
categories:
  - Short Talks
hide: no
---
Qualitative properties such as positivity and monotonicity of variables are desired in the solution of  some mathematical models such as the  susceptible-infected-recovered (SIR) model . When solving a system of differential equations with numerical methods such as Runge--Kutta methods and operator splitting methods, there is no guarantee that the desired properties are preserved in the numerical solutions.  In this talk, we will discuss qualitative property preservation with high-order operator splitting methods. High-order operator splitting methods require backward-in-time integrations which can cause issues with preserving positivity and monotonicity. However, we will see that if we split the system carefully and integrate the sub-integrators exactly, we could preserve positivity and monotonicity of desired variables. Moreover, if we choose to approximate the sub-integrators with Runge--Kutta methods, the desired properties can still be achieved with proper step-size restriction.
