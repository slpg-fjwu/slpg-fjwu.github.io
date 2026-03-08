---
layout: page
title: Exploring Transfer Learning and Domain Data Selection for Bio-medical Translation
description: A comprehensive study applying transfer learning and selective data training to improve Neural Machine Translation quality for the bio-medical domain, using Information Retrieval to select domain-relevant training data for English-French translation.
img: assets/img/noor-e-hira.png
importance: 15
related_publications: abdul2019exploring

category: work
---

## Introduction

This paper presents a series of experiments applying transfer learning and selective data training for the Bio-medical shared task of WMT19. The study focuses on Neural Machine Translation (NMT) between English and French in both directions, incorporating domain adaptation techniques to improve translation quality in the medical domain.

Despite NMT's strong performance on large corpora, translation quality for low-resource languages and specialized domains remains a significant challenge. Domain mismatch between training and testing data leads to rapid performance degradation, making targeted data selection strategies essential.

Information Retrieval (IR) was used to selectively choose related sentences from out-of-domain data, which were then incorporated as additional training data using transfer learning. The study also investigates the effect of tokenization on NMT system performance.

---

## Methodology and Training

For the English-French translation pipeline, in-domain and general domain corpora were combined using selective data training. The News Commentary corpus was used as the general domain source for IR-based data selection, with Medline titles as queries.

Key corpora used:

| Corpus | English | French |
|---|---|---|
| EMEA (in-domain) | 12.3M | 14.5M |
| Medline Abstracts | 1.4M | 1.7M |
| Medline Titles | 6.0M | 6.7M |
| Books (out-domain) | 2.71M | 2.76M |
| News Commentary | 4.9M | 5.9M |

Training was done using OpenNMT-py with the following parameters:

| Parameter | Value |
|---|---|
| Architecture | 2-layer RNN encoder-decoder |
| LSTM Units | 500 per layer |
| Learning Rate | 0.001 |
| Batch Size | 64 → 128 |
| Optimizer | Adam |
| Validation | Every 10,000 steps |

Two data selection pipelines were executed — one using English queries (`ncSDE`) and one using French queries (`ncSDF`) — to investigate the effect of query language on translation performance.

---

## Results and Performance

Transfer learning combined with selective data training consistently outperformed baseline systems. Key findings include:

- IR-based selective data training outperformed adding the entire out-of-domain News Commentary corpus, despite being smaller in size
- The best model (M8) achieved **21.97 BLEU**, an improvement of **17.44 BLEU points** over the out-domain books baseline (4.53)
- Tokenization proved critical — models trained on tokenized data outperformed untokenized counterparts by an average of **4 BLEU points**
- No significant difference was observed between English vs. French query language for data selection

---

## Future Directions

Future research in bio-medical NMT should focus on:

- Expanding in-domain parallel corpora for medical sub-domains
- Exploring more advanced domain adaptation techniques beyond IR-based selection
- Investigating the effect of subword tokenization schemes on specialized domain translation
- Applying zero-shot and few-shot learning for extremely low-resource medical language pairs

---

## Conclusion

This study demonstrates the effectiveness of combining transfer learning with IR-based selective data training for bio-medical Neural Machine Translation. Data selective training, even with a smaller corpus, yields better domain adaptation results than using the full out-of-domain corpus.


Tokenization was confirmed as a critical pre-processing step, significantly improving NMT system performance. Overall, the cascaded transfer learning approach proved highly effective, achieving substantial BLEU score improvements across all experimental configurations.

