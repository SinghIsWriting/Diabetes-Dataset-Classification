# Machine Learning Classification Assignment

## Project Overview

This project involves the implementation of various classification algorithms on a diabetes dataset from the National Institute of Diabetes and Digestive and Kidney Diseases. The goal is to predict whether a patient has diabetes based on diagnostic measurements.

### Dataset Description

The dataset includes the following features:
- **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skin fold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: A function representing the likelihood of diabetes based on family history.
- **Age**: Age in years.
- **Outcome**: Class variable (0: No Diabetes, 1: Diabetes).

The dataset only includes female patients aged at least 21 years.

### Classification Algorithms Used

The following classification algorithms were applied to the dataset:

1. **Logistic Regression**
2. **k-Nearest Neighbors (kNN)**
3. **Decision Tree**
4. **Naïve Bayes**
5. **Support Vector Machine (SVM)**

### Performance Metrics

To evaluate the performance of each classification algorithm, the dataset was split into training and testing sets. The following metrics were used to assess the models:
- **Accuracy**
- **Confusion Matrix**
- **AUC (Area Under the ROC Curve)**

## Results Summary

| Algorithm             | Accuracy | Confusion Matrix               | AUC   |
|-----------------------|----------|--------------------------------|-------|
| Logistic Regression    | 0.760    | `[[84 15], [22 33]]`           | 0.724 |
| k-Nearest Neighbors    | 0.727    | `[[83 16], [26 29]]`           | 0.683 |
| Decision Tree          | 0.701    | `[[72 27], [19 36]]`           | 0.691 |
| Naïve Bayes            | 0.760    | `[[81 18], [19 36]]`           | 0.736 |
| Support Vector Machine | 0.773    | `[[87 12], [23 32]]`           | 0.730 |

## Conclusion

- **Support Vector Machine (SVM)** emerged as the top-performing algorithm with the highest accuracy of **0.773** and an AUC of **0.730**.
- **Logistic Regression** and **Naïve Bayes** achieved the next highest accuracy scores of **0.760** each, with Naïve Bayes slightly outperforming Logistic Regression in AUC (0.736 vs 0.724).
- **k-Nearest Neighbors (kNN)** performed well with an accuracy of **0.727** and an AUC of **0.683**.
- **Decision Tree** had the lowest accuracy of **0.701**, with an AUC of **0.691**.

### Key Insights

- **Support Vector Machine (SVM)** is the recommended model for this classification problem, as it provides the best balance between accuracy and AUC.
- **Logistic Regression** and **Naïve Bayes** are also strong contenders, with competitive performance.
- **kNN** and **Decision Tree** had slightly lower performance and may benefit from further optimization to improve results.

## Instructions for Running the Code

1. Load the diabetes dataset.
2. Split the data into training and testing sets.
3. Apply the following algorithms:
   - Logistic Regression
   - kNN
   - Decision Tree
   - Naïve Bayes
   - Support Vector Machine (SVM)
4. Evaluate each model using accuracy, confusion matrix, and AUC.

### Libraries Required
- pandas
- scikit-learn (Logistic Regression, kNN, Decision Tree, Naïve Bayes, SVM)
- matplotlib (for plotting)
- seaborn (for heatmaps of the confusion matrices)

- - -

## **Contributing**

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit them (`git commit -m 'Add feature-name'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

- - -

## **License**

This project is licensed under the [MIT License](LICENSE).

- - -

## **Contact**

For any inquiries or support, please reach out to:
- **Name**: Abhishek Singh
- **Email**: sabhisheksingh343204@gmail.com
- **LinkedIn**: [My LinkedIn Profile](https://www.linkedin.com/in/abhishek-singh-bba2662a9)

- - -
