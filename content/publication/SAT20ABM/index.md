---
abstract: 'Given a Boolean formula F, the problem of model counting, also referred
  to as #SAT, is to compute the number of solutions of F. The hashing-based techniques
  for approximate counting have emerged as a dominant approach, promising achievement
  of both scalability and rigorous theoretical guarantees. The standard construction
  of strongly 2-universal hash functions employs dense XORs (i.e., involving half
  of the variables in expectation), which is widely known to cause degradation in
  the runtime performance of state of the art SAT solvers. Consequently, the past
  few years have witnessed an intense activity in the design of sparse XORs as hash
  functions. Such constructions have been proposed with beliefs to provide runtime
  performance improvement along with theoretical guarantees similar to that of dense
  XORs. The primary contribution of this paper is a rigorous theoretical and empirical
  analysis to understand the effect of the sparsity of XORs. In contradiction to prior
  beliefs of applicability of analysis for sparse hash functions to all the hashing-based
  techniques, we prove a contradictory result. We show that the best-known bounds
  obtained for sparse XORs are still too weak to yield theoretical guarantees for
  a large class of hashing- based techniques, including the state of the art approach
  ApproxMC3. We then turn to a rigorous empirical analysis of the performance benefits
  of sparse hash functions. To this end, we first design, to the best of our knowledge,
  the most efficient algorithm called SparseCount2 using sparse hash functions, which
  achieves at least up to two orders of magnitude performance improvement over its
  predecessor. Contradicting the current beliefs, we observe that SparseCount2 still
  falls short of ApproxMC3 in runtime performance despite the usage of dense XORs
  in ApproxMC3. In conclusion, our work showcases that the question of whether it
  is possible to use short XORs to achieve scalability while providing strong theoretical
  guarantees is still wide open. '
authors:
- Durgesh Agrawal
- Bhavishya
- Kuldeep S. Meel
date: 2020-05-19 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of the International Conference on Theory and Applications
  of Satisfiability Testing (SAT)*
publication_types:
- '1'
selected: true
title: On the Sparsity of XORs in Approximate Model Counting
url_dataset: http://doi.org/10.5281/zenodo.3792748
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/sat20-adm.pdf
---

