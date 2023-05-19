---
speakers:
  - Giacomo Rosilho de Souza
name: "Multirate explicit stabilized method in mixed-precision arithmetic"
categories:
  - Short Talks
hide: no
---
In recent years, there has been a resurgence of low-precision arithmetic supported by hardware, with an increase in the number of CPUs and GPUs supporting half-precision fp16 and bfloat16 floating-point formats, in addition to the traditional float (single) and double.
This allows us to develop mixed-precision algorithms that combine low- and high-precision arithmetic calculations to take advantage of the performance gains of reduced precision while preserving the same accuracy as a method entirely in high precision.
Explicit stabilized methods (e.g. RKC) are particularly well-suited for an adaptation in mixed precision. These are explicit schemes whose stability domain grows quadratically with the number of function evaluations. Thus, most of the computational effort is devoted to increasing stability rather than precision.
In this work, we design RKC methods in mixed precision, where high precision (double) is used only to maintain the order of convergence, and low precision (half-precision) is used for stability. We present an RKC method and a multirate RKC scheme. At each time step, these schemes perform only one function evaluation in high precision, necessary to maintain the order of convergence, while the rest of the calculations, needed for stability, are performed in low precision.
We prove that these methods are essentially as cheap as their fully low-precision equivalent, but they maintain the stability and order of convergence of their high-precision counterpart. Indeed, numerical experiments confirm that these schemes are as accurate as the corresponding high-precision method.
