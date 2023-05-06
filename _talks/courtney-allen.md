---
speakers:
  - Courtney Allen
name: "Comparing a de novo implementation of the Anaerobic Digestion Model 1 with existing implementations challenges assumptions about computational speed"
categories:
  - MS
hide: no
---
The Anaerobic Digestion Model 1 was created by an International Water Association task group in 2002 and is the quasi industry standard for modelling anaerobic digestion. It was initially written as a system of 35 ordinary differential equations (ODEs), but a differential algebraic equation (DAE) form was created to decrease computation time. We compare a de novo Julia-based implementation of the ODE form of ADM1 against existing DAE implementations in Java and Python. This comparison shows that the Julia ODE form of ADM1 outperforms the existing DAE versions, and indicates that the differences in computational speed depends on more than just whether the system is in DAE or ODE form.
