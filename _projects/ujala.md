---
layout: page
title: "Forecasting Political Unrest: Machine Learning Approach for Predicting Early Warning Signs Through Data Analytics"
description: "A comprehensive study comparing 13 machine learning frameworks for forecasting early warning signs of political violence using multilingual news data and the ACLED dataset."
img: assets/img/ujala.png
importance: 1
category: work
---
<div class="container text-justify">
<div class="row justify-content-center">
        <div class="text-justify">
<h2>Introduction</h2>
<p>Political violence refers to violent acts driven by political motives or objectives, and its consequences on communities and societies have been severe. Global studies show that countries experiencing civil wars and international disputes are considerably more prone to political violence, causing sudden damage to civilians, infrastructure, and governance. The increasing trend of violent outbursts has underlined the need for models that can forecast such events and enable timely interventions. This study presents a methodology that compares multiple machine learning frameworks for forecasting early warning signs of political violence based on news data, using the Armed Conflict Location Event Data Project (ACLED) dataset spanning 2010 to 2020.</p>

<h2>Framework</h2>
<p>The political violence prediction framework follows a structured pipeline covering data preprocessing, feature extraction, and machine learning based prediction of political events such as protests, battles, and violence against civilians. The process begins with data cleaning to remove redundant entries and missing values. Key features are then identified including event types, sub-event types, locations, fatality rates, and news sources. TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert textual data into meaningful numerical feature vectors. To analyze political narratives across languages, a multilingual classification strategy is introduced where both Urdu and English news data are considered. The framework is illustrated in a full pipeline covering data collection, preprocessing, feature engineering, and model building using both traditional and deep learning techniques.</p>

<h2>Challenges and Solutions</h2>
<p>Forecasting political violence is inherently difficult due to complex socio-political dynamics that are hard to quantify, including ethnic tensions, socio-economic disparities, and historical grievances. Class imbalance in the dataset, where certain event types are significantly overrepresented, poses a major challenge for deep learning models, leading to biased predictions and poor generalization. Multilingual classification adds further complexity, particularly for low-resource languages like Urdu.</p>
<p>To address these challenges, the study evaluates 13 different machine learning models ranging from traditional supervised learning methods to advanced transformer-based architectures. Standard preprocessing techniques including stemming, lemmatization, stopword removal, and text normalization are applied consistently. For cross-lingual modeling, English text is translated into Urdu using the Google Translate API, with 500 samples manually reviewed by human annotators to maintain translation quality. Hyperparameter tuning is applied to deep learning models to improve accuracy and reduce overfitting.</p>

<h2>Evaluation and Performance</h2>
<p>Models are evaluated using accuracy, precision, recall, and F1 score across both English and Urdu datasets. Traditional models such as Logistic Regression and Decision Tree achieved the highest performance at 98% accuracy, with Logistic Regression recording a precision of 0.90, recall of 0.73, and F1 score of 0.77. These models outperformed deep learning architectures due to their robustness with structured and imbalanced datasets. LSTM achieved 93% accuracy but showed lower precision and recall due to class imbalance and feature sparsity. Transformer-based models presented mixed results; RoBERTa with ADAM optimizer reached 97% accuracy, while BERT configurations with LAMB and ADAFACTOR optimizers degraded severely to 4–5% accuracy, highlighting the critical role of optimizer selection. Multilingual BERT performed poorly across both Urdu and English datasets with only 2–3% accuracy, despite being pre-trained on over 100 languages. A real-time case study using 57,700 tweets about the Kashmir conflict showed Logistic Regression achieving the best classification accuracy of 55%, predicting a 69% likelihood of government action to restore Article 370 based on public sentiment trends.</p>

<h2>Future Directions</h2>
<p>Future work should integrate real-time data streams to improve prediction accuracy and expand datasets to enhance generalization. Predictions will be extended to cover countries across South Asia, with news collected through online sources and web scraping techniques. Addressing class imbalance and improving fairness in model outputs remain important priorities. Hybrid approaches combining traditional machine learning with transformer-based techniques are expected to offer a more balanced solution for political violence forecasting.</p>

<h2>Conclusion</h2>
<p>This study demonstrates that traditional machine learning models like Logistic Regression and Decision Tree are highly effective for forecasting political violence when applied to structured datasets like ACLED, outperforming more complex deep learning architectures. The BERT-Multilingual framework showed promise for multilingual classification but requires further refinement to handle low-resource languages effectively. The real-time Twitter case study further validates the framework's ability to detect political trends and anticipate government actions. These findings provide actionable insights for policymakers to enhance preparedness and response to political violence threats, while setting a new benchmark for advanced analytics in conflict forecasting.</p>
        </div>
    </div>
</div>