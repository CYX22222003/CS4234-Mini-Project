# 0. Intro

# 1. Prelimnaries: define notations, 

1. Notations: maybe we just follow the Karmarkar paper
- Bin Packing Problem instance itself
- Multiset representation of the bins
- Bin configuration
 
2. greedy proof:
- OPT(I) = 2 SIZE(I) + 1.
- Since the sum of the item sizes is a lower bound on OPT, m − 1 < 2OPT, i.e., m ≤ 2OPT (see Notes for a better analysis).
- Theorem 9.2 For any ε > 0, there is no approximation algorithm having a guarantee of 3/2 − ε for the bin packing problem, assuming P = NP.

3. Introduce the relaxed BP: state formulation of ILP, state relaxed LP, explain the rounding, present the deflation, analyze the approximate gurantee and time complexity (show that the problem is polynomial of the instance)

# 2. De La Vega-Luekar algorithm

- About 3 PAGES

- Eliminiation and linear grouping => how to choose the threshold, and how to do the grouping

- Compare two rounding methods => round up / principal + residual

- Small items repacking => Proof of the the approximate gurantee => start from two claims => leads to final approiximate gurantee

- State the final time complexity

# 3. Karmarkar-Karp

- About 3 PAGES

- Proof of some lemmas and corollaries

- Introduction of geometric grouping

- Presentation of algorithm (apply the geometric grouping => reduce it to the relaxed BP => solve it, but it different rounding) => rewrite in a detailed and more comprehensive psudocode

- Proof of approximation

# 4. Conclusion


# Side Notes

How to do the proof?

1. reorganize => start clearly from assumptions => show the intermediate steps
2. express intermediate steps
3. simplify