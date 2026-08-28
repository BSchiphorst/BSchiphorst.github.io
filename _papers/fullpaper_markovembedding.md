---
title: "Continuous-time embedding algorithms for absorbing Markov chains."
collection: papers
category: manuscripts
permalink: /paper/markov_chain_embedding
excerpt: ' '
keywords: "embedding problem, absorbing Markov chain, survival probabilities, expectation-maximization, Kullback-Leibler divergence"
Abstract: 'Continuous-time Markov chain (CTMC) models are useful in a wide range of disciplines such as engineering, medical sciences, and finance. However, practitioners instead often only have access to a discrete-time model. In that case, embedding algorithms can be used to find an approximate continuous-time embedding. Ideally, this embedding preserves the available discrete-time information that is most relevant for the application of the model. However, existing embedding algorithms typically rely on generic embedding error metrics that assign equal importance to all state transitions and ignore how errors in short-term transition probabilities aggregate over longer time horizons. To address this, we propose a flexible framework for constructing embedding algorithms based on generalized geometric and divergence-based embedding error metrics. Our framework is designed such that it can construct hybrid algorithms that strike a balance in optimizing a combination of multiple error metrics. We showcase this framework by developing new specialized embedding algorithms for absorbing Markov chains that aim to preserve the term structure of survival probabilities. Numerical experiments on empirical credit rating transition matrices highlight that optimizing for a specific embedding error metric comes at the cost of overall performance. Crucially, we demonstrate that our hybrid approaches achieve a robust balance between preserving survival times and fitting short-term state transitions.'
date: 2026-02-20 
venue: '(Under review)'
paperurl: '/files/MarkovEmbeddingPaper.pdf'
---