---
title: Propaganda Detection and Categorisation
date: 2024-05-28
external_link: https://github.com/anuoluwatuyi/propaganda-detection-3

tags:
  - NLP
  - BERT
  - Text Classification
featured: true
---

This research focuses on the detection of propaganda within text, a crucial task for ensuring information integrity across various media platforms. Our study establishes a baseline using Support Vector Machines (SVM) combined with TF-IDF vectors, followed by more sophisticated models incorporating Word2Vec embeddings and BERT sequence classification. The SVM model with Word2Vec targets contextual word similarities while the BERT sequence classification model aims for comprehensive semantic analysis. We assessed the performance of each model based on precision, recall, and F1-score metrics. The findings demonstrate that the BERT sequence classification model surpasses the TF-IDF-SVM and Word2Vec-SVM combinations. Although the latter two models achieved comparable F1-scores of 0.68 and 0.69 respectively on the detection task, they were less effective in classifying propaganda techniques. BERT excelled in both tasks, achieving F1-scores of 0.94 in propaganda detection and 0.78 in propaganda categorization, offering enhanced detection capabilities for complex propaganda techniques. This suggests that BERT-based models are more effective in the nuanced identification of propaganda, promoting more reliable and precise text classification.

<!--more-->