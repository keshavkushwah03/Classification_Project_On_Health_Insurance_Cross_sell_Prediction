# Classification_Project_On_Health_Insurance_Cross_sell_Prediction

## Project Type: Classification
## Author: Keshav Kushwah

## Project Summary

The aim of this project is to develop a classification model that predicts whether a customer would be interested in purchasing vehicle insurance. This prediction is essential for insurance companies to optimize their communication strategies and business revenue.

### Project Strategy

#### Data Cleaning and Feature Engineering:
- Missing values were handled, and incomplete rows were removed to ensure data integrity.
- Categorical variables were encoded appropriately.
- Numerical features were scaled for uniformity.

#### Exploratory Data Analysis (EDA):
- Explored insights from the dataset.
- Analyzed age groups, previous insurance status, and the relationship between vehicle damage history and response.
- Used various visualizations to represent relationships in the data.

#### Training a Model:
- Utilized machine learning algorithms like Random Forest, Logistic Regression, and Gradient Boosting.
- Split the dataset into training and testing sets.
- Evaluated models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

The final model was selected based on a balance between precision and recall to identify potential accident cases while minimizing false positives. The chosen model underwent hyperparameter optimization for improved predictive capabilities.

## Problem Statement

Developing a classification model to predict the likelihood of vehicle accidents for insurance policyholders is crucial for insurance companies. This prediction empowers companies to optimize risk assessment, customer communication, and business strategies effectively.

## Conclusion

### Insights from EDA

- The majority of responses in the dataset are labeled as '0,' indicating that most customers did not show interest in the vehicle insurance policy.
- Customers with a driving license are more prominent, with a higher count of '0' responses (no interest) than '1' responses (interest).
- Slightly more than half of the policyholders were not previously insured.
- Customers with vehicle damage history ('Vehicle_Damage' = 'Yes') are more likely to show interest (Response = 1).

### Machine Learning Models

1. Trained models using Logistic Regression, Random Forest Classifier, and XGBoost Classifier.
2. Hyperparameter tuning improved performance in all models.
3. Random Forest initially outperformed with high accuracy and ROC-AUC but was overfit.
4. XGBoost demonstrated consistent performance with the highest F1 scores after tuning.
5. The XGBoost Classifier was chosen as the preferred model for this classification project.

## Acknowledgments

The dataset used for this project is obtained from [(https://colab.research.google.com/drive/11B63ha9A33oS0Gra2wb1ByMec0vGDVxv?usp=sharing)] and should be credited.

## Author

- Keshav Kushwah
- Contact: keshavkushwah03@gmail.com

Feel free to reach out if you have any questions or suggestions!
