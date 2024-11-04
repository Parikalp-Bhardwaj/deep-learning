# Sentiment Analysis Using Recurrent Neural Networks

This project contains Jupyter notebooks that demonstrate how to perform sentiment analysis using Recurrent Neural Networks (RNNs). The notebooks cover various approaches, from simple implementations to more advanced models for faster and multi-class sentiment analysis.

## Notebook Descriptions

## 1. Sentiment_Analysis_Simple.ipynb
Description: Introduces the basics of sentiment analysis using a simple RNN model. It walks through data preprocessing, model building, training, and evaluation for binary sentiment classification (positive or negative).


### Key Features:
- Data loading and text preprocessing
- Tokenization and sequence padding
- Building a simple RNN using Keras
- Model training and accuracy evaluation


## 2. RNN_Faster_Sentiment_Analysis_.ipynb
Description: Builds upon the simple model to create a faster and more efficient RNN for sentiment analysis. This notebook explores techniques to optimize training time and improve model performance.

### Key Features:
- Implementation of embedding layers for word representations
- Use of optimized RNN architectures like LSTM or GRU
- Techniques for accelerating training (e.g., batch normalization, dropout)
- Performance comparison with the simple RNN model


## 3. RNN_Multi_class_Sentiment_Analysis.ipynb
Description: Extends sentiment analysis to a multi-class classification problem. Instead of just positive or negative, the model predicts multiple sentiment categories (e.g., very negative, negative, neutral, positive, very positive).

### Key Features:
- Handling and preprocessing multi-class labeled data
- Modifying the RNN architecture for multi-class output
- Use of appropriate loss functions and activation layers (e.g., softmax)
- Evaluation using metrics like precision, recall, and F1-score for multi-class classification
