---
abstract: Constrained-random verification (CRV) is widely used in industry for validating
  hardware designs. The effectiveness of CRV depends on the uniformity of test stimuli
  generated from a given set of constraints. Most existing techniques sacrifice either
  uniformity or scalability when generating stimuli. While recent work based on random
  hash functions has shown that it is possible to generate almost uniform stimuli
  from constraints with 100,000+ variables, the performance still falls short of today's
  industrial requirements. In this paper, we focus on pushing the performance frontier
  of uniform stimulus generation further. We present a random hashing-based, easily
  parallelizable algorithm, UniGen2, for sampling solutions of propositional constraints.
  UniGen2 provides strong and relevant theoretical guarantees in the context of CRV,
  while also offering significantly improved performance compared to existing almost-uniform
  generators. Experiments on a diverse set of benchmarks show that UniGen2 achieves
  an average speedup of about 20X over a state-of-the-art sampling algorithm, even
  when running on a single core. Moreover, experiments with multiple cores show that
  UniGen2 achieves a near-linear speedup in the number of cores, thereby boosting
  performance even further.
authors:
- Supratik Chakraborty
- Daniel J. Fremont
- Kuldeep S. Meel
- Sanjit A. Seshia
- Moshe Y. Vardi
date: 2015-04-01 00:00:00
highlight: true
image_preview: ''
math: true
publication: In *Proceedings of Tools and Algorithms for the Construction and Analysis
  of Systems (TACAS)*
publication_types:
- '1'
selected: true
title: On Parallel Scalable Uniform SAT Witness Generator
url_code: https://bitbucket.org/kuldeepmeel/unigen/src/master/
url_pdf: http://www.comp.nus.edu.sg/~meel/Papers/Tacas15.pdf
url_slides: files/slides/Talk_TACAS.pdf
---

