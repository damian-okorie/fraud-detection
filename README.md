
# Fraud Detection with Supervised Learning
This repository features a project dedicated to financial fraud detection employing supervised learning algorithms. The project incorporates and compares various machine learning models, including Gradient Boosted Trees, K-Nearest Neighbors, and Multi-Layer Perceptron (MLP) implemented in both scikit-learn and Keras. The models were trained and evaluated on datasets exhibiting class imbalance, a common issue in fraud detection, which was handled through the application of random undersampling techniques.

# Project Overview
The primary challenge of fraud detection in machine learning is the significant class imbalance present in the data, where the instances of fraud are typically much less frequent than legitimate transactions. This discrepancy can result in a model bias towards the majority class, leading to a high number of undetected fraudulent transactions.

To alleviate this issue, we applied a random undersampling technique to balance the classes, subsequently improving the model's ability to learn and predict the minority (fraudulent) class.

# Model Evaluation and Comparison
Four popular models were evaluated and compared: Gradient Boosted Trees, K-Nearest Neighbors, and two variants of Multi-Layer Perceptron, one implemented using Scikit-Learn (MLP-Scilearn), and the other with Keras (MLP-Keras). Each model was assessed in its baseline form, followed by optimization to investigate the potential of improvement in fraud detection performance.

# Results
The optimized Gradient Boosted Tree model emerged as the top performer, demonstrating superior results across all evaluation metrics - F1 score, Precision, and Recall. The confusion matrix results provided a deeper understanding of each model's performance concerning correctly predicting fraudulent and non-fraudulent transactions, underlining the significance of minimizing both types of errors.

While the optimized Gradient Boosted Tree was the best performer in our study, it is important to note that model selection in practical applications should consider specific dataset characteristics, computation resources, interpretability, and the relative costs of different types of errors.

# Conclusion
This project illustrates the potential and versatility of machine learning in tackling the challenging task of fraud detection. By utilizing a strategic combination of various machine learning models, optimization techniques, and effective sampling strategies, we were able to construct robust and high-performing fraud detection models. The findings and methodologies presented in this project serve as a valuable reference for similar applications in a variety of domains.