## Overview

This repository is being used to share how to use the BERT model.
Before starting to learn how to use the BERT model, you should understand the following concepts.


### 1. Basic concept

**Transfer Learning**
Transfer learning is a machine learning technique where a pre-trained model trained on a large dataset is used as a starting point for a new task. Instead of starting the training from scratch, the pre-trained model is fine-tuned on a smaller dataset for a specific task, which allows for better performance with less training data and time.

**Feature Base Vs Fine-Tuning**

**Feature-based** is methods involve using pre-trained model to extract informative features from text data. These features can be used as inputs to a separate classification model, such as a support vector machine (SVM) or logistic regression.
For example, let's say you have a text classification task where you want to classify movie reviews as positive or negative. You can use a pre-trained language model like BERT to extract informative features from each movie review, such as the contextual embeddings of each word in the review. You can then use these features as inputs to a separate classification model, like an SVM, to make the final classification decision.


