---
abstract: Propositional model counting (#SAT), i.e., counting the number of satisfying
  assignments of a propositional formula, is a problem of significant theoretical
  and practical interest. Due to the inherent complexity of the problem, approximate
  model counting, which counts the number of satisfying assignments to within given
  tolerance and confi- dence level, was proposed as a practical alternative to exact
  model counting. Yet, approximate model counting has been studied essentially only
  theoretically. The only reported implementation of approximate model counting, due
  to Karp and Luby, worked only for DNF formulas. A few existing tools for CNF formulas
  are bounding model counters; they can handle realistic problem sizes, but fall short
  of providing counts within given tolerance and confidence, and, thus, are not approximate
  model counters. We present here a novel algorithm, as well as a reference implementation,
  that is the first scalable approximate model counter for CNF formulas. The algorithm
  works by issuing a polynomial number of calls to a SAT solver. Our tool, ApproxMC,
  scales to formulas with tens of thousands of variables. Careful experimental comparisons
  show that ApproxMC reports, with high confidence, bounds that are close to the exact
  count, and also succeeds in reporting bounds with small tolerance and high confidence
  in cases that are too large for computing exact model counts.
authors:
- Supratik Chakraborty
- Kuldeep S. Meel
- Moshe Y. Vardi
date: 2013-09-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Constraint Programming
  (CP)*
publication_types:
- '1'
selected: true
title: 'A Scalable Approximate Model Counter '
url_code: https://bitbucket.org/kuldeepmeel/approxmc/src/master/
url_pdf: http://www.comp.nus.edu.sg/~meel/Papers/CP2013.pdf
url_slides: files/slides/Talk_scalable.pdf
---

