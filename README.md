# Detecting Sarcasm with RoBERTa Embeddings and XGBoost

By Ivan T. Ivanov, Lisamaria Cutrone & Jennifer Passarelli

A Program Comprehensive Assessment for Probability and Statistics 201-HTH-05

Submitted to Ivan T. Ivanov, Mathematics Department, Vanier College, December 2024:

## Abstract
This project aims to develop a model capable of distinguishing between sarcastic and non-sarcastic text in article headlines. A Kaggle dataset of sarcastic headlines from The Onion and non-sarcastic headlines from HuffPost was used. RoBERTa, a transformer-based language model, was used to embed the headlines to capture semantic relationships between the headlines and converting them into numerical vectors. These embeddings were then used to train an XGBoost classifier.

The results demonstrate that the model is effective in detecting sarcasm with high precision, recall, and F1-scores above 0.8. This indicates the model's accurate identification of sarcastic headlines while minimizing false positives and negatives. This model can have applications in social media content moderation and sentiment analysis, aiding in tasks like detecting hate speech or flagging inappropriate content and predicting the emotional tone of text.

While the model exhibits high accuracy, potential improvements include experimenting with other embedding models such as BERT, XLNet, or ELMo, and expanding the dataset for broader sarcastic expression detection.
