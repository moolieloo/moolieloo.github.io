---
layout: post
title: Classifying human written text from GPT-2 generated text with LR, CNN and BERT
---

This [paper](https://www.dropbox.com/s/7lfvjjkv90bfnwr/final_text_classification_report.pdf?dl=0) explores how three different models handled a binary text classification task.

Abstract:

In the field of Natural Language Processing (NLP), there has been a dramatic shift towards utilizing pre-trained deep language models. To perform text classification, this study uses state-of-the-art neural network models, Bidirectional Encoder Representations of Transformers (BERT) and convolutional neural networks (CNN), as well as a non-neural classifier, Logistic Regression (LR), as baseline.
Specifically, the task is to distinguish human-generated text from fake text generated by the GPT-2 language model. 

Results show BERT beat the baseline, achieving 90.34% F-score compared to LR’s F-score of 88.23%. BERT and LR both outperformed CNN, which attained an F-score of 80.41%. In the error analysis, this
study further confirms previous research’s finding that sequence length affects neural network models performance. For example, any truncation in the input documents has a detrimental influence on the
effectiveness of BERT. The primary contribution of this study is to introduce a simple but effective model in the field of fake text detection.
