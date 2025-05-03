# NLP-Driven SMS Spam Classification

## 📌 Project Overview
This project evaluates the performance of Natural Language Processing (NLP)-driven Machine Learning (ML) models for detecting spam in SMS messages. It focuses on preprocessing, feature engineering, vectorization, and the comparative analysis of multiple classification algorithms to determine the most effective spam detection strategy.


## 🧠 Problem Statement
With the rising use of SMS, spam messages have become a significant issue, impacting user trust and privacy. This project aims to:
- Explore effective data cleaning and text preprocessing methods.
- Engineer features that enhance classification.
- Compare ML models to find the best-performing algorithm.

## 📊 Dataset
- **Source**: [UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)
- **Total Messages**: 5,574  
- **Spam**: 747 (13.4%)  
- **Ham**: 4,825 (86.6%)

Each message is labeled as either **"spam"** or **"ham"**.

## 🔧 Data Processing
- **EDA**: Frequency plots, word clouds, and pattern analysis
- **Cleaning**: Duplicate removal, missing value treatment, outlier filtering
- **Text Preprocessing**: Tokenization, stop-word removal, lemmatization

## 🧱 Feature Engineering
- Extracted features: presence of URLs, phone numbers, capital words, symbols
- Text length and keyword frequency analysis
- Visualization through bar charts and box plots

## 🧮 Vectorization
- **TF-IDF**: Captures term relevance across messages
- **Binary Encoding**: Flags presence of spam-related elements (URLs, numbers, etc.)
- Evaluated models with and without binary features

## 🤖 Model Development
- **Algorithms Tested**: Naive Bayes, SVM, Decision Trees, Random Forest
- **Performance Metrics**: Accuracy, Precision, Recall, F1-Score
- **Handling Imbalance**: SMOTE, class weight adjustments

## 🏆 Results
- Enhanced accuracy with feature engineering
- Best performance from [Insert Best Model Here] with high spam recall and balanced precision
- Binary encoding significantly boosted model effectiveness

## 📌 Conclusion
- NLP + ML effectively detect SMS spam
- Feature extraction (URLs, symbols) is crucial
- Handling class imbalance improves reliability

## 🚀 Future Scope
- Integrate real-time detection
- Experiment with transformers or deep learning models

---

Feel free to contribute or suggest enhancements.
