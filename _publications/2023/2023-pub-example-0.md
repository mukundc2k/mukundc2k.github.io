---
title:          "Neural Models for Factual Inconsistency Classification with Explanations"
date:           2023-09-17 00:01:00 +0800
selected:       true
pub:            "ECML PKDD"
pub_date:       "2023"
abstract: >-
  Factual consistency is one of the most important requirements when editing high quality documents. It is extremely important for automatic text generation systems like summarization, question answering, dialog modeling, and language modeling. Still, automated factual inconsistency detection is rather under-studied. Existing work has focused on (a) finding fake news keeping a knowledge base in context, or (b) detecting broad contradiction (as part of natural language inference literature). However, there has been no work on detecting and explaining types of factual inconsistencies in text, without any knowledge base in context. In this paper, we leverage existing work in linguistics to formally define five types of factual inconsistencies. Based on this categorization, we contribute a novel dataset, FICLE (Factual Inconsistency CLassification with Explanation), with 8K samples where each sample consists of two sentences (claim and context) annotated with type and span of inconsistency. When the inconsistency relates to an entity type, it is labeled as well at two levels (coarse and fine-grained). Further, we leverage this dataset to train a pipeline of four neural models to predict inconsistency type with explanations, given a (claim, context) sentence pair. Explanations include inconsistent claim fact triple, inconsistent context span, inconsistent claim component, coarse and fine-grained inconsistent entity types. The proposed system first predicts inconsistent spans from claim and context; and then uses them to predict inconsistency types and inconsistent entity types (when inconsistency is due to entities). We experiment with multiple Transformer-based natural language classification as well as generative models, and find that DeBERTa performs the best. Our proposed methods provide a weighted F1 of 87% for inconsistency type classification across the five classes. We make the code and dataset publicly available.

cover:          /assets/images/covers/figure4.png
authors:
  - Tathagata Raha#
  - Mukund Choudhary
  - Abhinav Menon
  - Harshit Gupta
  - KV Aditya Srivatsa
  - Manish Gupta
  - Vasudeva Varma
links:
  Paper: https://link.springer.com/chapter/10.1007/978-3-031-43418-1_25
  GitHub: https://github.com/blitzprecision/FICLE
---
