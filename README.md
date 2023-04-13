# Breast Cancer Detection using Machine Learning Algorithms

<img src="https://img.freepik.com/free-vector/bound_53876-25486.jpg" width="100" height="100">

Breast cancer is one of the leading causes of death among women worldwide. Early detection of breast cancer is crucial in reducing mortality rates. This project aims to build a machine learning model that detects breast cancer using the K-Nearest Neighbor (KNN) and Support Vector Machine (SVM) algorithms. The dataset used in this project contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## Technologies used

- Python
- Machine learning algorithms (KNN, SVM, Random Forest Classifier)

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Dataset, obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)). The dataset contains 569 instances with 30 features each. The features represent the computed attributes of the cell nuclei in the digitized image of the FNA.

## Model Building and Evaluation

We built two models using the KNN and SVM algorithms. Both models were trained on 80% of the dataset and tested on the remaining 20%. We evaluated the models using the accuracy metric.

| Algorithm | Accuracy |
| --------- | -------- |
| KNN       | 0.956    |
| SVM       | 0.982    |

The SVM model outperformed the KNN model in terms of accuracy.

## Conclusion

The SVM model was able to accurately classify breast cancer instances in the dataset. This project demonstrates the potential of machine learning in breast cancer detection and diagnosis.

## References

- UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Dataset. (n.d.). Retrieved April 13, 2023, from https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)
