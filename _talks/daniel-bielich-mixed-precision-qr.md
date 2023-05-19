---
speakers:
  - Daniel Bielich
name: "Mixed Precision QR"
categories:
  - Short Talks
hide: no
---
Mixed precision has been a growing tool to improve performance and increase productivity. Much work has been put forth to decrease the computation time to compute expensive factorizations, such as the QR factorization. In terms of this orthogonalization process, our main interest pertains to what operations or steps can be computed in lower precision while still maintaining an accurate solution. We investigate the use of (simulated) lower precision and its impact to accuracy (backward/forward errors) in solutions to Linear Least Squares. The method to improve a degraded solution from low precision, for this talk, is extra precise iterative refinement. We investigate how low precision impacts the refinement step, as well as the maintained level of orthogonality and representation.
