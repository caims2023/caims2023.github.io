---
speakers:
  - Gautam Luhana
name: "Block Preconditioners for the Implicit-in-Time Immersed Boundary Method"
categories:
  - Short Talks
hide: no
---
The Immersed Boundary (IB) method is a popular method for simulating fluid-solid interactions. The IB method was initially designed by Charles S. Peskin to simulate fibrous heart valves, and has since evolved into a general-purpose method for simulating various types of solid dynamics immersed within a fluid. The key idea, and the reason for its popularity, is to keep the solid and fluid variables on two separate, Lagrangian and Eulerian, domains. The two grids communicate forces and velocities via integral operators with Dirac Delta kernels. This allows for simplicity in the code as well as avoids the problem of regeneration of the mesh resulting from deformations and movements of the solid structure.

Implicit schemes for the IB method have been around for a while but the real challenge has been to develop a scheme that is computationally competitive with the explicit schemes. The usual approach for the implicit IB method is to either eliminate the Lagrangian variables and solve the fully Eulerian system or vice versa. The first approach leads to a familiar 2x2 block Saddle-Point system that is difficult to solve efficiently due to the eulerian structural force term. 

We propose an alternative approach of solving the full 3x3 block Double Saddle-Point system and present efficient and scalable preconditioners based on recent work on Double Saddle-Point systems. The preconditioners are based on LDU block factorizations and we present efficient approximations for the resulting Schur Complements.
