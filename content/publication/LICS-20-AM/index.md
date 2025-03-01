---
abstract: ' Given a CNF formula F on n variables, the problem of model counting, also
  referred to as #SAT, is to compute the number of models or satisfying assignments
  of F. Model counting is a fundamental but hard problem in computer science with
  varied applications. Recent years have witnessed a surge of effort towards developing
  efficient algorithmic techniques that combine the classical 2-universal hashing
  (from [Stockmeyer 1983]) with the remarkable progress in SAT solving over the past
  decade. These techniques augment the CNF formula F with random XOR constraints and
  invoke an NP oracle repeatedly on the resultant CNF-XOR formulas. In practice, the
  NP oracle calls are replaced by calls to a SAT solver and it is observed that runtime
  performance of modern SAT solvers (based on conflict-driven clause learning) on
  CNF-XOR formulas is adversely affected by the size of XOR constraints. However,
  the standard construction of 2-universal hash functions chooses every variable with
  probability p =1/2 leading to XOR constraints of size n/2 in expectation. Consequently,
  the main challenge is to design sparse hash functions, where variables can be chosen
  with smaller probability and lead to smaller sized XOR constraints, which can then
  replace 2-universal hash functions. In this paper, our goal is to address this challenge
  both from a theoretical and a practical perspective. First, we formalize a relaxation
  of universal hashing, called concentrated hashing, a notion implicit in prior works
  to design sparse hash functions. We then establish a novel and beautiful connection
  between concentration measures of these hash functions and isoperimetric inequalities
  on boolean hypercubes. This allows us to obtain tight bounds on variance as well
  as the dispersion index and show that p = O(log m /m ) suffices for the design of
  sparse hash functions from 2^n to 2^m belonging to concentrated hash family. Finally,
  we use sparse hash functions belonging to this concentrated hash family to develop
  new approximate counting algorithms. A comprehensive experimental evaluation of
  our algorithm on 1896 benchmarks with computational effort of over 20,000 computational
  hours demonstrates significant speedup compared to existing approaches. To the best
  of our knowledge, this work is the first study to demonstrate runtime improvement
  of approximate model counting algorithms through the usage of sparse hash functions,
  while still retaining strong theoretical guarantees (a la 2-universal hash functions). '
authors:
- " Kuldeep S. Meel ⓡ S. Akshay "
date: 2020-05-18 00:00:01
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of Logic in Computer science (LICS)*
publication_types:
- '1'
selected: true
title: 'Sparse Hashing for Scalable Approximate Model Counting: Theory and Practice'
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/lics20-ma.pdf
---

