# Sentiment Analysis of Tamil-English and Tulu-English Code-Mixed Text

This repository contains the complete codebase for our research on sentiment analysis of Tamil-English and Tulu-English code-mixed social media text. The study compares machine learning (ML) and deep learning (DL) approaches to classify sentiments in low-resource Dravidian languages.

## 📌 Research Overview
- **Title**: Sentiment Analysis of Tamil-English and Tulu-English Code-Mixed Text Using Machine Learning and Deep Learning Approaches  
- **Paper Link**: [Provide link if available]  
- **Authors**: [Your Name(s)]  
- **Abstract**:  
  Code-mixed texts, which is particularly prevalent in multilingual communities, pose unique challenges for natural language processing (NLP) tasks such as sentiment analysis. This paper explores two distinct methodologies—one based on traditional machine learning (ML) and the other on deep learning (DL)—to classify sentiments in code-mixed Tamil-English and Tulu-English texts. Preprocessing involved transliterating code-mixed scripts into English, followed by feature extraction through TF-IDF for ML and FastText embeddings for DL. A logistic regression classifier was employed in the ML approach, while the DL model utilized a BiLSTM with an attention mechanism for contextual learning. Through comparative analysis, we observe that the ML approach outperforms the DL model in terms of accuracy and macro F1 score, likely due to the limited size of the labeled dataset. This study highlights the importance of selecting appropriate methodologies for code-mixed NLP tasks based on the available dataset, with potential applications in social media monitoring, customer sentiment analysis, and multilingual conversational AI.

## 📊 Results Summary
ML Model (TF-IDF + Logistic Regression):
- Tamil Macro F1 Score: 0.46
- Tulu Macro F1 Score: 0.60

DL Model (FastText + BiLSTM + Attention):
- Tamil Macro F1 Score: 0.43
- Tulu Macro F1 Score: 0.48

## 🔍 Key Findings
- The ML approach performed better than the DL approach, especially for Tulu due to its smaller dataset size.

- The DL model struggled with data scarcity, highlighting the challenges of deep learning for low-resource languages.

- Future work should explore transformer-based models (e.g., mBERT, XLM-R) and data augmentation techniques.
