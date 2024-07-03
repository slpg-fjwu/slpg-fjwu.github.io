---
layout: page
title: Sentence Simplification in Punjabi Language
description: Working on creating  Punjabi  Shahmukhi simplification corpus
img:  assets/img/sentence simplification.png
importance: 4
category: work
---

Introduction
In the domain of language simplification, creating aligned monolingual parallel
data sets tailored to specific linguistic dialects is a significant endeavor. In this
pursuit, we present the pioneering Punjabi Simplification (PUSIM) corpus, which
focuses on the Shahmukhi dialect.

Sentence Simplification 

Sentence simplification  refers to the process of making complex or intricate sentences easier to understand while retaining the original meaning. This is particularly useful for individuals who may have difficulty comprehending complex language, such as non-native speakers, individuals with learning disabilities, or those with limited literacy skills. Sentence simplification techniques may involve breaking down complex sentence structures, substituting difficult words with simpler synonyms, and rephrasing convoluted phrases to improve clarity and readability without altering the underlying message or content of the text. Simplified sentences are often employed in educational materials, instructional texts, and academic resources to facilitate comprehension and accessibility for a wider audience.

PUSIM corpus Creation 
Two annotators worked on corpus creation which took almost 500 man hours. Both were Punjabi natives with fluent proficiency with one being a linguist and Punjabi expert.This would be the first corpus in Punjanbi  which will release publically after the publication.

Goals and Objective
Our goal is to develop a sentence simplification system using the PUSIM language corpus that can be utilized in various natural language processing (NLP) tasks, such as machine translation. To achieve this, we have three objectives.

create a simplified corpus of Punjabi language while the meaning is preserved.
Produce further simplified versions of a complex sentence with simple vocabulary and sentence structure.
To produce the understandable content for the speakers and language learners.

Related Work 
assets/img/simplification_timeline_jpg



Corpus Evalution.

Sentence simplification may be evaluated in different ways, one by humans who look at things like grammatical correctness and maintaining the intended meaning of the original text, and the other by machines who use a variety of metrics to train and compare various models, as well as automatic readability. 

Human evaluation is time-consuming and costly, but it provides a more accurate measure of the quality of the output. 

Automatic evaluation, on the other hand, involves using metrics to measure the quality of the simplifications. BLEU (Papineni et al., 2002) and SARI (Alva, 2019) are two metrics that are commonly used for this purpose. 

For evaluating the quality and simplicity of our corpus, we performed human evaluation which were done by four different  speakers of 12 grade to 16 grade with two having an average grasp on the Punjabi language and  the other two who belong grade 14 and 16 have a good grasp in the Punjabi language.

Human Evaluation 

![image](https://github.com/slpg-fjwu/slpg-fjwu.github.io/assets/14946796/07a72048-1c5e-4d7a-9b09-91bbbeb48d4c)

Automatic Readability Metrics  for Evaluation Used in PUSIM

A text’s readability level is a useful indicator of its complexity and intended readership. 

In the PUSIM corpus, we used different automatic readability metrics.by modifying a few features to ensure that the readability of our corpus is increased. 

WE used FRE ,FKGL, SMOG , and ARI. 

 For  automatic system building we use BLEU  and SARI scores.

 Future WORK 

 In the domain of sentence simplification, the use of reference-less metrics for assessing generated outputs have shown potential in the realm of Quality Estimation research. This approach holds the promise of enhancing the efficiency and scope of automated assessment. Additional research is required to go deeper into this concept. From our perspective, it seems that just three criteria have been used in the assessment of human-based evaluations, namely grammatical accuracy, semantic coherence, and lucidity. Do these requirements meet the necessary criteria? If a change in perspective were made to consider objects at the document level, would they retain their utility? What methodologies may be used to ascertain the efficacy of the condensed version in terms of its relevance and usefulness to the target audience? etc.

