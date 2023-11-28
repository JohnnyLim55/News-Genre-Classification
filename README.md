# News Genre Classification: A Comparative Analysis using Support Vector Machine and Random Forest Models on Indonesian News Texts
## Overview
This repository encompasses a comprehensive approach to news genre classification, employing advanced text mining techniques. Prior to text classification, an initial preprocessing step is undertaken. The goal of this preliminary process is to generate a vector set from cleaned text data, devoid of symbols, hashtags, "https," or ".com." The entire text is converted to lowercase, the vector size is set at 50, and word frequency is considered, with a minimum count of 3. Vectors are generated based on training results, using input words and target output contexts, excluding stopwords.
## Initial Process
- Text Cleaning: Eliminate symbols, hashtags, "https," and ".com" from the text.
- Lowercasing: Convert the entire text to lowercase.
- Vectorization: Generate a vector set with a size of 50, considering words with a minimum frequency of 3.
- Training: Utilize the cleaned and processed data for training, focusing on input words and target output contexts. Exclude stopwords during this training phase.
## Machine Learning Models
Two machine learning algorithms, Support Vector Machine (SVM) and Random Forest, are employed for initial news content prediction. Both algorithms utilize two text representation methods.
## Prediction and Comparison
1. Support Vector Machine (SVM):
- Text Representation TF-IDF
- Text Representation CountVectorizer
2. Random Forest:
- Text Representation TF-IDF
- Text Representation CountVectorizer
Comparative Analysis
## Evaluate the performance of SVM and Random Forest models with respect to:
- Accuracy
- Precision
- Recall
- F1 Score

Explore the nuances and strengths of both methods in predicting and classifying Indonesian news text content. The comparison aims to provide insights into the effectiveness of each algorithm and text representation method in the context of news genre classification.
