# IR-TASK-2 TEXT CLASSIFICATION BATTLE – COMPARE, ANALYZE AND DEFEND

# IR-TASK-2: TEXT CLASSIFICATION BATTLE

## 1. Project Overview
This project performs SMS Spam Classification using Machine Learning algorithms. The objective is to classify SMS messages into two categories: Ham (Normal Message) and Spam (Unwanted Message).

## 2. Dataset
- Dataset: SMS Spam Collection Dataset
- Input: SMS Text Messages
- Output: Ham and Spam

## 3. Algorithms Used
1. Decision Tree
2. K-Nearest Neighbours (KNN)
3. Support Vector Machine (SVM)
4. Naive Bayes

## 4. Performance Comparison

The graph compares Accuracy, Precision, Recall and F1-Score of all four classifiers.

![Performance Comparison](Classifier%20comparison.png)
## 5. Confusion Matrix

The following confusion matrices show the classification results of all four algorithms.

![Confusion Matrix](confusion%20matrix.png)

## 6. Classifier Performance Results

The following table compares the performance of four machine learning algorithms.

| Classifier | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Decision Tree | 0.761905 | 0.782313 | 0.761905 | 0.755182 |
| KNN | 0.523810 | 0.761905 | 0.523810 | 0.404762 |
| SVM | 0.809524 | 0.819597 | 0.809524 | 0.806878 |
| Naive Bayes | 0.571429 | 0.603175 | 0.571429 | 0.551261 |

## 7. What-If Experiment Results

The experiment compares Linear Kernel and RBF Kernel using the SVM algorithm.

| SVM Kernel | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Linear Kernel (Baseline) | 0.809524 | 0.819597 | 0.809524 | 0.806878 |
| RBF Kernel (What-If) | 0.809524 | 0.819597 | 0.809524 | 0.806878 |

### Analysis

- SVM achieved the highest accuracy of 80.95%.
- Decision Tree achieved 76.19% accuracy.
- Naive Bayes achieved 57.14% accuracy.
- KNN achieved 52.38% accuracy.
- Both Linear and RBF kernels produced identical results in this experiment.

### Conclusion

Based on the experimental results, SVM achieved the best classification performance among the four algorithms. The What-If experiment showed that changing the kernel from Linear to RBF did not improve the evaluation metrics on this test dataset.




