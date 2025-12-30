---
title:          "Neural Models for Factual Inconsistency Classification with Explanations"
date:           2023-09-17
selected:       true
pub:            "ECML PKDD"
pub_date:       "2023"
abstract: >-
  factual consistency is crucial for all kinds of language generation tasks: summarization, QA, dialogue, LMs, etc. but detecting why something is factually off, without any external knowledge base, is still barely studied. we fix that by defining five concrete types of factual inconsistencies using linguistic theory, and contribute FICLE, an 8K-sample dataset of claim-context pairs annotated with inconsistency type, span, and entity mismatches (both coarse and fine). we train a four-part neural pipeline to detect inconsistent spans, identify the type, and flag the exact entity issues, if any. DeBERTa leads the pack with 87% weighted F1 on type prediction. the takeaway: not only can we catch factual errors without a KB, we can explain how they are bad, making factuality checks more usable and interpretable.

cover:          /assets/images/covers/figure4.png
authors:
  - Tathagata Raha#
  - Mukund Choudhary
  - Abhinav S Menon
  - Harshit Gupta
  - KV Aditya Srivatsa
  - Manish Gupta
  - Vasudeva Varma
links:
  Paper: https://link.springer.com/chapter/10.1007/978-3-031-43418-1_25
  GitHub: https://github.com/blitzprecision/FICLE
---
