---
speakers:
  - Raymond Spiteri
name: "The future of rounding is stochastic"
categories:
  - Short Talks
hide: no
---
The concept of rounding is introduced in early elementary
school. The well-known model that is taught is formally known as
"round to nearest". For example, when rounding to integers, all
decimal fractions 0.5 and above round up to the next integer, and
everything below 0.5 rounds down. As much as this model feels natural
and somehow "the right thing to do", it has drawbacks, most notably
the phenomenon of "stagnation", whereby the cumulative effect of
relatively small increments to a given quantity is lost. This
phenomenon has important implications in floating-point
arithmetic.

Enter stochastic rounding. Stochastic rounding is like the wild west of rounding methods. It’s unpredictable, it’s risky, but it just might work! In stochastic rounding, decimal fractions are rounded with probability in inverse proportion to their distance to their closest rounded numbers. For example, 0.7 would round up to 1 with probability 0.7 but round down with probability 0.3. Stochastic rounding does not suffer from stagnation, and the expected values of common linear algebra operations (such as inner products or matrix-vector multiplication) are the exact solution. In practice, these features usually translate into the ability to achieve results of a given quality using lower precision (e.g., single precision vs. double precision). Hence computations can be performed with less time, memory, and energy. In this presentation, we cover the basics of stochastic rounding and use the Julia programming language to peer into what the future of floating-point computation might look like.
