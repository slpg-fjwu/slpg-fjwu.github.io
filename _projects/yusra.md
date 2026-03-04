---
layout: page
title: "Automatic Sentence Simplification in Low Resource Settings for Urdu"
description: "The first monolingual parallel Urdu corpus for sentence simplification, combining lexical and syntactic simplification methods with human evaluation and automatic metric comparison."
img: assets/img/yusra.png
importance: 12
category: work
---
<div class="container text-justify">
<div class="row justify-content-center">
        <div class="text-justify">
<h2>Introduction</h2>
<p>Complex sentences are always hard to understand for humans as well as automated applications. Sentence complexity often hinders proper communication of intended meaning and creates a bottleneck in learning pipelines. Simplified sentences have been proven especially useful for foreign speakers, language learners, children, people with lower literacy, and those with cognitive impairments such as dyslexia and autism spectrum disorder. For Urdu specifically, this gap is growing day by day, as literary texts often include complex words and composite sentence structures. With English increasingly taking over as an official language and code-mixing becoming prevalent, natives are inclined to use simpler language and often find it difficult to understand the level of Urdu used in traditional literature. This study presents the first monolingual parallel Urdu corpus for sentence simplification, developed using lexical and syntactic methods, along with automatic and human evaluation of simplification quality.</p>

<h2>Framework</h2>
<p>The corpus was developed from 69 short, philosophical and thought-provoking Urdu stories written by Ashfaq Ahmad, sourced from the Urdu library. These stories use complex sentence structures with typical Urdu literary vocabulary. Simplification was carried out at two levels: Lexical Simplification (LS), where complex words and phrases are replaced with simpler synonyms using the Online Urdu Lughat dictionary, and Syntactic Simplification (SS), where grammatical complexity is reduced through operations including deletion, insertion, reordering, splitting, and merging of words and phrases. A complex-to-simple word and phrase lexicon of 490 dictionary entries, including 270 word-level and 220 phrase-level entries, was also developed during the corpus creation process. Phrase-based Machine Translation using the Moses toolkit was used to build automatic text simplification models trained on three parallel corpus groups: original to lexical, lexical to syntactic, and a concatenation of both.</p>

<h2>Challenges and Solutions</h2>
<p>Urdu is a low-resource language with no prior work on sentence simplification, making it necessary to build everything from scratch including both the corpus and evaluation framework. The literary nature of the source texts adds difficulty because classical Urdu vocabulary and composite sentence structures are far more complex than everyday language. Additionally, verifying simplification quality required expert linguistic judgment, and ensuring consistency in annotation across two levels of simplification was a significant challenge.</p>
<p>To address these challenges, language professionals were consulted to properly identify complex sentences in literature before simplification began. Simplified corpora were rechecked by language experts to remove any anomalies. A 3-scale human evaluation scheme was adopted over 5-scale criteria to improve inter-annotator consistency, measuring fluency, adequacy, and simplicity. Cohen's Kappa score was used to measure inter-annotator agreement. For automatic evaluation, BLEU and SARI scores were used to compare performance across systems trained on different corpus configurations.</p>

<h2>Evaluation and Performance</h2>
<p>The final corpus contains 1220 simplified sentences based on 610 complex sentences, with both lexical and syntactic versions. Human evaluation was conducted by two native Urdu speakers aged 35 to 42, achieving inter-annotator agreement Kappa scores of 0.82 for lexical simplification and 0.84 for syntactic simplification, indicating strong agreement. The most frequent simplification operation in lexical simplification was rewording, accounting for 77.61% of cases, while deletion was the dominant syntactic operation at 84% of cases. Average words per sentence in original, lexically simplified, and syntactically simplified versions were 13.87, 13.51, and 10.33 respectively, confirming meaningful reduction in sentence length. The automatic simplification system built on the SimUR corpus achieved the highest BLEU score of 50.736 with a SARI score of 26.036 for the original to lexical group, outperforming systems built on other available corpora including OneStopEnglish, SimPA, PWKP, Simpliki, and PaCCSS-It. The lexical simplification system achieved an excellent BLEU score compared to the other two systems, and the SARI scores across all systems ranged between 24 and 29.</p>

<h2>Future Directions</h2>
<p>Increasing the corpus size with more diverse literary and everyday Urdu content will significantly improve the power of automatic simplification models. Future work can explore more advanced neural and transformer-based simplification architectures as larger Urdu corpora become available. Extending the simplification lexicon with broader vocabulary coverage and incorporating additional feature-based operations such as verbal features and sentence type classification can further improve system output. The framework also has strong potential for application in improving many other NLP tasks for Urdu such as text summarization, machine translation, and question generation.</p>

<h2>Conclusion</h2>
<p>This study introduces the first monolingual parallel Urdu corpus for sentence simplification, providing a foundational resource for developing automatic simplification systems for a low-resource language. The corpus contains 1220 simplified sentences with both lexical and syntactic levels, accompanied by a complex-to-simple lexicon of 490 entries. Human evaluation confirmed strong inter-annotator agreement and the quality of the simplification operations applied. The automatic simplification system built on the SimUR corpus achieved the best BLEU scores compared to systems built on other language corpora translated to Urdu, demonstrating that effective simplification systems can be built for Urdu even with small amounts of parallel data. This work lays the groundwork for future research in Urdu text simplification and accessibility-focused NLP.</p>
        </div>
    </div>

</div>

