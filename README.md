# Sentiment Analysis - Greek Elections

This project involves developing multiple sentiment classifiers for a Twitter dataset related to the Greek general elections. The classifiers employ various machine learning and deep learning techniques to analyze the sentiment expressed in the tweets.

## Files Breakdown

1. **sentiment_classifier.ipynb**
   - **Description**: A simple sentiment classifier using Logistic Regression.
   - **Techniques**: 
     - Text preprocessing (tokenization, stopword removal)
     - Feature extraction using TF-IDF
     - Sentiment classification with Logistic Regression

2. **sentiment_classifier_nn.ipynb**
   - **Description**: A sentiment classifier using Deep Neural Networks with PyTorch and word2vec word embeddings.
   - **Techniques**:
     - Text preprocessing
     - Word embeddings using word2vec
     - Sentiment classification using a Deep Neural Network (DNN) with PyTorch

3. **sentiment_classifier_rnn.ipynb**
   - **Description**: A sentiment classifier using bidirectional stacked RNNs with LSTM/GRU.
   - **Techniques**:
     - Text preprocessing
     - Word embeddings
     - Sentiment classification using bidirectional stacked Recurrent Neural Networks (RNNs) with LSTM/GRU units

4. **sentiment_classifier_bert.ipynb**
   - **Description**: A sentiment classifier using fine-tuned models GREEK-BERT and DistilGREEK-BERT, offered by HuggingFace.
   - **Techniques**:
     - Text preprocessing
     - Fine-tuning pre-trained BERT models (GREEK-BERT and DistilGREEK-BERT)
     - Sentiment classification using BERT models
