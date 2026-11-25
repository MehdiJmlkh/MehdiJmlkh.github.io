---
title: "Toward Test-Time Adaptation for Emergent Language under Complexity Shifts"
collection: publications
category: none
permalink: /publication/2015-10-01-paper-title-number-3
date: 2026-11-01
venue: 'IEEE Access'
authors: M. Samiei, M. Jamalkhah, M. Soleymani
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11783370'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Emergent communication research has achieved high coordination in referential games, inducing discrete protocols that resemble language-like symbol systems. Despite extensive work across diverse emergent-language settings, a key gap remains: what happens when test instances demand finer distinctions or far more confusable distractors than in training? In emergent-language setups, however, the sender policy is fixed after training, leaving it unable to produce a more informative message when test instances become more complex, despite the expectation we place on the flexibility and adaptability of language. To address this deployment-time mismatch, we introduce a sender-side test-time adaptation framework that optimizes message generation using only the sender’s internal self-play objective. While this concept represents a general framework, we specifically instantiate and evaluate it using a Vector-Quantized Emergent Languag (VQ-EL) architecture, enabling variable-length descriptions using inference-time optimization without extra interaction rounds. Our experiments demonstrate that, across more complex inputs and more challenging candidate sets, our method consistently improves communication accuracy and, when needed, benefits from more descriptive messages. Our findings position test-time adaptation as a practical mechanism for making emergent languages robust to increased deployment-time complexity, offering a novel approach to adapting agents for real-world referential settings where the required message specificity is unpredictable.
