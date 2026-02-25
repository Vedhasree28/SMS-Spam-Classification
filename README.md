# **SMS Spam Classification System**
## **Overview**
* This project implements an end-to-end SMS Spam Classification system using Natural Language Processing (NLP) and supervised machine learning techniques. The objective is to automatically classify SMS messages as Spam or Ham (legitimate messages) based on textual content.
* The solution follows a structured ML workflow including data preprocessing, feature engineering, model training, evaluation, and real-time prediction.

## **Problem Statement**
Unsolicited spam messages are a major issue in digital communication. This project builds a machine learning pipeline capable of identifying spam messages with high accuracy using text-based features.

## **Project Workflow**
### **1. Data Preprocessing**
* Removal of special characters and numbers
* Lowercasing text
* Tokenization
* Stopword removal
* Lemmatization using WordNet
* These steps reduce noise and normalize text data for better feature extraction.

### **2. Feature Engineering**
* Text vectorization using:
* Bag of Words (BoW)
* TF-IDF (Term Frequency–Inverse Document Frequency)
* This converts raw text into numerical feature vectors suitable for ML algorithms.

### **3. Model Training**
The following models can be used:
* Naive Bayes
* Decision Tree


### **4. Model Evaluation**
Performance is evaluated using:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## **Features**
* Complete NLP preprocessing pipeline
* Text vectorization using TF-IDF
* Supervised machine learning implementation
* Performance evaluation metrics
* Prediction for custom SMS inputs

## **Technologies Used**
* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib / Seaborn (for visualization)

## **Conclusion**
This project demonstrates the practical implementation of NLP and machine learning techniques for text classification. It provides a scalable and structured approach to solving real-world spam detection problems and serves as a strong foundation for more advanced NLP applications.

## **Author**
Developed as part of a machine learning and NLP practice project.
