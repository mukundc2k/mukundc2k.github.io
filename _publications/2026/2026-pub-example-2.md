---
title:          "Last Translation Benchmark"
date:           2026-09-05
selected:       true
pub:            "arXiv"
pub_date:       "2026"

abstract: >-
  machine translation feels solved to a lot of NLP but is unusable in a lot of real life scenarios. this gap is annoying and with LLMs, it should've been easier to close. turns out, evaluation was messed up in some ways and it couldn't do somethings before, that we can do now. this framework crowdsources a lot of real multimodal, multilingual MT examples with verification rules that users submit to point out pain points with the translation after seeing state-of-the-art responses that failed. i realised that MQM, BLEU, et al. were all targeted towards comparing outputs to gold, but a lot of the fun linguistic trickery can be predicted from the source sentence too, so i used all of that information to come up with a taxonomy of where MT systems found it difficult to translate instead of where human translators fail and MT errors just slotted into them.
cover:        /assets/images/covers/ltb.svg
authors:
  - Vilém Zouhar#
  - Niyati Bafna
  - Mukund Choudhary
  - Maike Züfle
  - Sara Rajaee
  - Pinzhen Chen
  - ...
links:
  Paper: https://arxiv.org/abs/2609.04173
  GitHub: https://github.com/zouharvi/last-translation-benchmark
---
