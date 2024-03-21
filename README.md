# Spam Email Performance Comparison with SVM and Naive Bayes

---
## :heavy_check_mark: Overview 

With an exponential increase in the volume of **spam emails**, ensuring effective email communication is becoming a significant challenge. This drives the necessity for robust spam email classification. In this project, we evaluate and compare two potent machine learning algorithms - **Support Vector Machine (SVM)** and **Naive Bayes** in the task of spam email classification.

### The Algorithms 
- **Support Vector Machine (SVM)**: It is a supervised machine learning algorithm commonly used for classification problems. SVM attempts to find the optimal hyperplane in an N-dimensional space (N being the number of features) that distinctly classifies the data points.

- **Naive Bayes**: Naive Bayes is a probabilistic classifier that applies Bayes' theorem, but with a strong assumption of independence between features. Despite its simplicity and the strong independence assumption, it is highly effective on high-dimensional datasets.

We enhance the algorithms by tuning parameters using **Default Parameters**, **Grid Search**, and **Bayesian Optimization**.

---

## :file_folder: Dataset 

The dataset used in this project can be accessed from [Kaggle- Spam Email Classification](https://www.kaggle.com/datasets/ashfakyeafi/spam-email-classification). The dataset chiefly consists of two columns - 'Label' and 'Text': 

- **Label**:
  - 'Spam': Indicative of the email being classified as spam.
  - 'Ham': Represents a legitimate email. 

- **Text**: It contains the actual content of the email messages.

## :bar_chart: Results

| Model | Accuracy | Precision | Recall | F1 Score | Specificity |
| --- | --- | --- | --- | --- | --- |
| Support Vector Machine (SVM) | 98.4753% | 99.2537% | 89.2617% | 93.9929% | 99.8965% |
| Naive Bayes | 98.3857% | 97.1223% | 90.6040% | 93.7500% | 99.5859% |
| Bayes Optimized SVM | 98.8341% | 99.2754% | 91.9463% | 95.4704% | 99.8965% |
| Bayes Optimized Naive Bayes | 98.4753% | 97.1429% | 91.2752% | 93.7500% | 99.5859% |
| Grid Support Vector Machine (SVM) | 98.4753% | 99.2537% | 89.2617% | 93.9929% | 99.8965% |
| Grid Naive Bayes | 98.3857% | 97.1223% | 90.6040% | 93.7500% | 99.5859% |
