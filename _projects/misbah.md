---
layout: page
title: "Fake News Detection on Kashmir Issue Using Machine Learning Techniques"
description: "A machine learning approach to detect fake news during the revocation of Article 370 in Kashmir as a focusing event, using Twitter data and user profile parameters."
img: assets/img/flowchart%20(1).png
importance: 10
category: work
---
<div class="container text-justify">
<div class="row justify-content-center">
        <div class="text-justify">
<h2>Introduction</h2>
<p>Focusing events are sudden, high-impact occurrences that capture widespread public attention and direct it toward a specific problem. The revocation of Article 370 in Kashmir by the Indian government in August 2019 is one such event, generating an enormous volume of visual and textual discourse on social media, particularly Twitter. During such events, online fact-checkers are slow to respond, and internet communities become the primary source of news, enabling unchecked dissemination of both real and fake information. Existing research on fake news detection has largely focused on general-purpose datasets or long-term contexts such as elections and health crises, leaving a significant gap in real-time detection methods tailored to short-duration, high-impact political events. This study addresses that gap by applying traditional machine learning techniques to a small, event-specific Twitter dataset collected during the Kashmir conflict.</p>

<h2>Framework</h2>
<p>The proposed system automatically detects and evaluates the credibility of news tweets by capturing content from various Twitter sources and utilizing user profile parameters for classification. Data was collected between 20th August and 2nd September 2019, yielding an initial set of 6,570 general tweets. After preprocessing to remove redundancy, non-English content, and graphical data, a refined dataset of 402 news tweets was prepared for model training. Tweet credibility was verified using Google News, along with profile signals such as verified account status, follower and following counts, retweet counts, tweet creation date, and user engagement metrics. The pipeline covers data collection, preprocessing using tokenization, stop word removal, stemming, and lemmatization, followed by feature extraction using Term Frequency and TF-IDF methods, and finally classification using five machine learning models.</p>

<h2>Challenges and Solutions</h2>
<p>Detecting fake news during focusing events is particularly difficult because data is sparse, short-lived, and rapidly evolving. The Kashmir dataset spans only a few weeks, making it insufficient to train deep learning models that require large annotated corpora. Existing online fact-checkers primarily focus on American political content, making real-time verification of Kashmir-related news especially challenging. Class imbalance between true and false tweets, along with the high dimensionality of text features, further complicates the classification task.</p>
<p>To address these challenges, traditional machine learning models are employed as they perform reliably on small, structured datasets with limited computational resources. N-gram models and TF-IDF feature extraction are used to capture linguistic patterns distinguishing fake from real tweets. User profile attributes including follower ratio, retweet count, and verification status are combined with textual features to improve classification interpretability and robustness. Standardized hyperparameter configurations are applied across all models to ensure consistency and reproducibility of results.</p>

<h2>Evaluation and Performance</h2>
<p>Five classifiers were trained and evaluated using F1 score and accuracy: Random Forest, Logistic Regression, Support Vector Machine, Naïve Bayes, and Stochastic Gradient Descent. Random Forest and Logistic Regression achieved the highest performance with an F1 score of 74% and accuracy of 82%, outperforming all other models. SVM closely followed with a 73% F1 score and 79% accuracy, while Naïve Bayes achieved 71% F1 score. Stochastic Gradient Descent showed the weakest results at 64% F1 score. Tweet analysis revealed that Pakistan generated the highest proportion of relevant tweets at 24.52%, followed by India at 23.56%. Word cloud analysis identified dominant terms across fake and real tweet categories, with words like "Kashmir", "curfew", "IOK", and "developing" appearing prominently in both. The most retweeted content during the event period was a tweet about the Pakistani Envoy to the US, receiving 488 retweets, while engagement peaked between 23rd and 30th August 2019.</p>

<h2>Future Directions</h2>
<p>Future work will focus on expanding the dataset to include a broader time range and more diverse linguistic content to improve model generalizability. Incorporating additional feature selection methods and multilingual coverage will strengthen detection capabilities across different regions and languages. Employing deep learning techniques such as fine-tuned pretrained transformer models may further improve classification performance when larger datasets become available. The framework can also be extended to other focusing events such as natural disasters and social movements to validate its broader applicability.</p>

<h2>Conclusion</h2>
<p>This study demonstrates that traditional machine learning models are effective for fake news detection in focusing events, even under the constraint of a small and narrow dataset. Random Forest and Logistic Regression achieved the highest accuracy of 82%, confirming the viability of lightweight ML approaches for real-time, event-specific misinformation detection. The combination of user profile features and linguistic patterns provides both strong predictive performance and practical interpretability. The framework holds significant value for journalists, fact-checking organizations, and policy response teams seeking to monitor and counter misinformation during rapidly evolving political or crisis events.</p>
        </div>
    </div>
</div>