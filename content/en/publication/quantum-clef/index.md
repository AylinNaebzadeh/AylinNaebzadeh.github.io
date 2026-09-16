---
title: 'NICA at Quantum Computing CLEF Tasks 2024'
subtitle: ''
summary: ''
authors:
- Aylin Naebzadeh
- Sauleh Eetemadi
tags: []
categories: []
date: '2025-01-01'
lastmod: 2025-01-01T00:00:00-04:00
featured: false
draft: false

image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
publishDate: '2024-01-01T00:00:00Z'
publication_types:
- '1'

abstract: >
  <div class="justify-text">
  We present the models implemented by the NICA group for the Quantum Computing (QuantumCLEF) Shared
  Task at CLEF 2024. Our participation focused on Task 1A: Feature Selection (Information Retrieval Task). We
  propose a feature selection algorithm based on a quadratic unconstrained binary optimization (QUBO) problem,
  which selects a specified number of features considering their importance and redundancy. This task was solved
  using a real quantum computer provided by D-Wave on the MQ2007 and ISTELLA datasets. Our approach
  utilized “Shannon Entropy” to target the mutual information between each feature and the target value. In
  QuantumCLEF Task 1A, the organizers suggested training a LambdaMART model on the selected features and
  evaluating performance using the nDCG@10 metric. Our team achieved nDCG@10 scores of 0.4506 and 0.6211
  for the MQ2007 and ISTELLA datasets, respectively.
  </div>

publication: '*Proceedings of the Conference and Labs of the Evaluation Forum, Grenoble, France*'
links:
- name: PDF
  url: http://ceurspt.wikidata.dbis.rwth-aachen.de/Vol-3740/paper-302.pdf
---

<style>
  .justify-text {
    text-align: justify;
  }
</style>
