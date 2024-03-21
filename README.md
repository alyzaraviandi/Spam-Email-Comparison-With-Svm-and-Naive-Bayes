# Spam Email Performance Comparison With SVM and Naive Bayes

## Background
Spam detection is a common application of Machine Learning, and Naive Bayes (NB) and Support Vector Machines (SVM) are popular algorithms for this purpose[^1^][10][^2^][11]. The goal of this project is to compare the performance of these two algorithms in classifying emails as spam or not spam (ham).

## Algorithms

### Support Vector Machines (SVM)
SVM is a powerful machine learning algorithm used for linear or nonlinear classification, regression, and even outlier detection tasks[^3^][1]. It works by mapping data points in space and finding a hyperplane that maximizes the distance between the two categories[^3^][1]. This is called a linear classifier. If the data points are not linearly separable in the original space, SVM can efficiently perform a non-linear classification using the so-called kernel trick[^3^][1].

### Naive Bayes (NB)
Naive Bayes is a probabilistic machine learning algorithm that can be used in a wide variety of classification tasks[^4^][16]. It leverages Bayes’ theorem, calculating the probability of a text belonging to a particular class based on the individual probabilities of its constituent words appearing in that class[^4^][16]. The "naive" aspect lies in its assumption that word occurrences are independent of each other within a class[^5^][17].

## Parameters
For both SVM and NB, we used three different methods for parameter tuning:
- Default parameters[^6^][12]
- Grid Search[^7^][7][^8^][8]
- Bayesian Optimization[^1^][10][^2^][11]

## Dataset
The dataset used for this project is the Spam Email Classification dataset available on Kaggle[^9^][4]. The dataset contains two columns:
- `label`: This column indicates whether the email is classified as spam ('Spam') or not spam ('Ham').
- `text`: This column contains the actual content of the email messages.

## References
[^3^][1]: [Support Vector Machine (SVM) Algorithm - GeeksforGeeks](https://www.geeksforgeeks.org/support-vector-machine-algorithm/)
[^1^][10]: [Comparing Naïve Bayes and SVM for Text Classification | Baeldung on Computer Science](https://www.baeldung.com/cs/naive-bayes-vs-svm)
[^2^][11]: [Naive Bayes vs. SVM for Text Classification - GeeksforGeeks](https://www.geeksforgeeks.org/naive-bayes-vs-svm-for-text-classification/)
[^6^][12]: [sklearn.naive_bayes.GaussianNB — scikit-learn 1.4.1 documentation](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html)
[^4^][16]: [How Naive Bayes Algorithm Works? (with example and full code) | ML+](https://www.machinelearningplus.com/predictive-modeling/how-naive-bayes-algorithm-works-with-example-and-full-code/)
[^5^][17]: [Naive Bayes Classifiers - GeeksforGeeks](https://www.geeksforgeeks.org/naive-bayes-classifiers/)
[^9^][4]: [Spam email classification | Kaggle](https://www.kaggle.com/datasets/ashfakyeafi/spam-email-classification)
[^7^][7]: [Comparison of Naive Bayes and SVM Classification in Grid-Search Hyperparameter Tuned and Non-Hyperparameter Tuned Healthcare Stock Market Sentiment Analysis](https://thesai.org/Publications/ViewPaper?Volume=13&Issue=12&Code=IJACSA&SerialNo=13)
[^8^][8]: [scikit learn - How to perform grid search on multinomial naive Bayes ...](https://thesai.org/Downloads/Volume13No12/Paper_13-Comparison_of_Naive_Bayes_and_SVM_Classification.pdf)
