# Data Mining
 
Given the TII-SSRC-23 dataset, which contains network traffic data designed for Research and Development of Intrusion Detection Systems (IDS), this project focuses on analyzing large-scale network data, perform dimensionality reduction, and implement machine learning models to classify network traffic as normal or malicious.

# 1st Question
The first phase of the project involves a deep dive into the TII-SSRC-23 dataset to establish a clear understanding of its structure. This includes identifying the semantic meaning and data types of each column, followed by calculating fundamental aggregate statistics to summarize the data. Furthermore, the analysis utilizes graphical representations to reveal underlying patterns and distributions in ordr to discover significant relationships between various features and their statistical metrics.

# 2nd Question
The second phase focuses on managing the large volume of the TII-SSRC-23 dataset while preserving essential information. This involves reducing dimensionality by removing or combining features based on previous findings, followed by shrinking the number of rows through two distinct methods: random sampling and data compression using two selected clustering techniques. The process concludes with the creation of three representative datasets to be used for model training.

# 3rd Question 
The final phase utilizes the reduced datasets to train machine learning models for intrusion detection. Specifically, Neural Network and SVM classifiers are implemented to perform binary classification (Normal vs. Malicious traffic) and multi-class classification (Traffic Type). The models are evaluated and compared using standard classification metrics to determine the most effective approach for each dataset.

