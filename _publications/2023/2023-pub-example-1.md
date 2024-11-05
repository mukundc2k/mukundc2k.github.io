---
title:          "CoPara: The First Dravidian Paragraph-level n-way Aligned Corpus"
date:           2023-09-07 00:01:00 +0800
selected:       true
pub:            "RANLP: DravidianLangTech"
pub_date:       "2023"
abstract: >-
  We present CoPara, the first publicly available paragraph-level (n-way aligned) multilingual parallel corpora for Dravidian languages. The collection contains 2856 paragraph/passage pairs between English and four Dravidian languages. We source the parallel paragraphs from the New India Samachar magazine and align them with English as a pivot language. We do human and artificial evaluations to validate the high-quality alignment and richness of the parallel paragraphs of a range of lengths. To show one of the many ways this dataset can be wielded, we finetuned IndicBART, a seq2seq NMT model on all XX-En pairs of languages in CoPara which perform better than existing sentence-level models on standard benchmarks (like BLEU) on sentence level translations and longer text too. We show how this dataset can enrich a model trained for a task like this, with more contextual cues and beyond sentence understanding even in low-resource settings like that of Dravidian languages. Finally, the dataset and models are made available publicly at CoPara to help advance research in Dravidian NLP, parallel multilingual, and beyond sentence-level tasks like NMT, etc.

cover:          /assets/images/covers/figure3.png
authors:
  - E Nikhil#
  - Mukund Choudhary
  - Radhika Mamidi
links:
  Paper: https://aclanthology.org/2023.dravidianlangtech-1.12.pdf
  GitHub: https://github.com/ENikhil/CoPara
---
