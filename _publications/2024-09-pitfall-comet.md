---
title: "Pitfalls and Outlooks in Using COMET"
collection: publications
venue: WMT 2024 Research Track
permalink: /publications/2024-09-pitfall-comet
paperurl: https://aclanthology.org/2024.wmt-1.121/
---
Authors: Vilém Zouhar\*, Pinzhen Chen\*, Tsz Kin Lam, Nikita Moghe, Barry Haddow


[paper](https://aclanthology.org/2024.wmt-1.121/) [code](https://github.com/PinzhenChen/sacreCOMET) [video](https://youtu.be/jDMvueySuPo) [poster](https://github.com/PinzhenChen/sacreCOMET/blob/main/misc/poster.png)

```
pip install sacrecomet
```

The COMET metric has blazed a trail in the machine translation community, given its strong correlation with human judgements of translation quality.Its success stems from being a modified pre-trained multilingual model finetuned for quality assessment.However, it being a machine learning model also gives rise to a new set of pitfalls that may not be widely known. We investigate these unexpected behaviours from three aspects:1) technical: obsolete software versions and compute precision; 2) data: empty content, language mismatch, and translationese at test time as well as distribution and domain biases in training; 3) usage and reporting: multi-reference support and model referencing in the literature. All of these problems imply that COMET scores are not comparable between papers or even technical setups and we put forward our perspective on fixing each issue.Furthermore, we release the sacreCOMET package that can generate a signature for the software and model configuration as well as an appropriate citation.The goal of this work is to help the community make more sound use of the COMET metric.
