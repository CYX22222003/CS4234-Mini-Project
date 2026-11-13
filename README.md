# Approximation Algorithms for Bin Packing

A CS4234 mini-project report at the National University of Singapore,
School of Computing, November 2026.

**[Read the report (PDF)](CS4234-Mini-Project-Writeup.pdf)**

The report studies the one-dimensional bin packing problem: packing items
into the fewest unit-capacity bins. It examines two classical approximation
algorithms and explains their construction, approximation guarantees, and
running times:

- **Fernández de la Vega–Lueker (1981):** an asymptotic polynomial-time
  approximation scheme using small-item elimination, linear grouping, and
  LP rounding.
- **Karmarkar–Karp (1982):** an algorithm combining geometric grouping,
  configuration LPs, and repeated packing of residual instances to achieve
  an additive guarantee of $O(\log^2(\mathrm{OPT}+1))$ beyond the optimum.

The report develops the supporting ideas through greedy packing algorithms,
configuration formulations, and a partial order on instances. Appendices
provide proofs, pseudocode, and illustrations of linear and geometric
grouping.
