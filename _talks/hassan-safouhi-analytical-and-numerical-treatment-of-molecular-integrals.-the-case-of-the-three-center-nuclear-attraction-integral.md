---
speakers:
  - Hassan Safouhi
name: "Analytical and Numerical Treatment of Molecular Integrals. The Case of the Three-Center Nuclear Attraction Integral"
categories:
  - Short Talks
hide: no
---
It is well known that in any ab initio molecular orbital (MO) calculation, the major task involves the computation of molecular multi-center integrals, which are needed for the computation of different energy components, such as kinetic energy, nuclear attraction energy and electron-electron repulsion energy. A large number of these integrals is required for molecular calculations even for small molecules. As the molecular system gets larger, computation of these integrals becomes one of the most laborious and time consuming steps in molecular structure calculation.

The most popular functions used in ab initio calculations are Gaussian type functions (GTFs). Unfortunately, these GTFs fail to satisfy the mathematical conditions for atomic electronic distributions. A large number of GTFs have to be used in order to achieve acceptable accuracy and this increases the computational cost. Exponential type functions (ETFs) are more suitable than GTFs to represent electron wave functions near the nucleus and at long range; this implies that a smaller number of ETFs is needed for comparable accuracy. Unfortunately, molecular ETF-integrals are difficult to evaluate rapidly and reliably to a chemically significant accuracy. Despite the efforts of many scientists, no efficient algorithms were proposed for their numerical evaluation. However, with the recent advances in computer technology and the development of more sophisticated numerical methods, many researchers hope that the next generation of ab initio programs will be based on ETFs, such as ADF.
