---
abstract: "Given a boolean formula F and a weight function $\rho$, the problem of\
  \ discrete integration seeks to compute the weight of $F$, defined as the sum of\
  \ the weights of satisfying assignments. Discrete integration, also known as weighted\
  \ model counting, is a fundamental problem in computer science with wide variety\
  \ of applications ranging from machine learning and statistics to physics and infrastructure\
  \ reliability. Given the intractability of the exact variant, the problem of approximate\
  \ weighted model counting has been subject to intense theoretical and practical\
  \ investigations over the years. The primary contribution of this paper is to investigate\
  \ development of algorithmic approaches for discrete integration. Our framework\
  \ allows us to derive two different algorithms, which can be seen as dual to each\
  \ other: \textsf{WISH}, which was already discovered by Ermon et al~\\cite{EGSS13c},\
  \ and a new algorithm: \textsf{SWITCH}.We argue that these algorithms can be seen\
  \ as dual to each other, in the sense that their complexities differ only by a permutation\
  \ of certain parameters. Indeed we show that, for $F$ defined over $n$ variables,\
  \ a weight function $\rho$ that can be represented using $p$ bits, and a confidence\
  \ parameter $\\delta$, there is a function $f$ and an NP oracle such that \textsf{WISH}\
  \ makes $\\mathcal{O} \\left(f(n,p,\\delta)\right)$ calls to NP oracle while \t\
  extsf{SWITCH} makes $\\mathcal{O}\\left(f(p,n,\\delta)\right)$ queries. We find\
  \ $f(x,y,\\delta)$ polynomial in $x$, $y$ and $1/\\delta$, more specifically $f(x,y,\\\
  delta) = x\\log(y)\\log(x/\\delta)$. We first focus on striking similarities of\
  \ both the design process and structure of the two algorithms but then show that\
  \ despite this quasi-symmetry, the analysis yields time complexities dual to each\
  \ other. Another contribution of this paper is the use of 3-wise property independence\
  \ of XOR based hash functions in the analysis of WISH and SWITCH. To the best of\
  \ our knowledge, this is the first usage of 3-wise independence in deriving stronger\
  \ concentration bounds."
authors:
- Alexis Colnet
- Kuldeep S. Meel
date: 2019-07-20 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of International Conference on Constraint Programming
  (CP)*
publication_types:
- '1'
selected: true
title: 'Dual Hashing-based Algorithms for Discrete Integration  '
url_pdf: https://www.comp.nus.edu.sg/~meel/Papers/cp19-dm.pdf
---

