# Titanic Survival Prediction

This project explores the use of machine learning to predict survival on the RMS Titanic, one of the most infamous shipwrecks in history. By applying four different machine learning models—Logistic Regression, Neural Networks, Decision Trees, and Random Forest—this study aims to identify which model most accurately predicts survival outcomes based on passenger data. This repository contains the code, datasets, and documentation for the entire analysis process.

## Project Overview

The Titanic dataset, containing passenger information such as age, sex, ticket class, and survival status, serves as a foundational dataset for classification in machine learning. Our analysis involves preprocessing this data, handling missing values, encoding categorical variables, and finally, applying and evaluating the predictive performance of four machine learning models.

## Repository Structure

```
Titanic-Survival-Prediction/
│
├── data/
│   ├── titanic_train.csv          - Training dataset with 891 entries.
│   └── titanic_test.csv           - Testing dataset with 418 entries.
│
├── notebooks/
│   ├── Logistic_Regression.ipynb  - Jupyter notebook for the logistic regression model.
│   ├── Neural_Networks.ipynb      - Jupyter notebook for the neural network model.
│   ├── Decision_Tree.ipynb        - Jupyter notebook for the decision tree model.
│   └── Random_Forest.ipynb        - Jupyter notebook for the random forest model.
│
├── results/
│   ├── model_comparisons.png      - Visual comparison of model accuracies.
│   └── feature_importance.png     - Feature importance for decision trees and random forest.
│
├── .gitignore                     - Specifies intentionally untracked files to ignore.
└── README.md                      - Project overview and repository guide.
```

## Getting Started

To replicate this analysis or explore the dataset with the provided models:

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
   ```
2. Install the required dependencies.
   ```
   pip install -r requirements.txt
   ```
3. Navigate to the `notebooks/` directory and open the Jupyter notebooks to run the models.

## Models and Performance

- **Logistic Regression:** Achieved an accuracy of 79.19%.
- **Neural Networks:** Achieved an accuracy of 79.67%.
- **Decision Trees:** Achieved the highest accuracy of 79.90%.
- **Random Forest:** Achieved an accuracy of 78.23%.

## Discussion and Conclusion

This study provides a comparative analysis of machine learning models on the Titanic dataset. The decision tree model demonstrated the highest accuracy, underscoring its efficacy in handling categorical data and modeling complex decision boundaries. Our findings highlight the importance of appropriate model selection and preprocessing techniques in improving predictive performance.

For a detailed discussion and insights into the methodologies, techniques, and results, please refer to the individual notebooks within the `notebooks/` directory.

## Contributing

Contributions to improve the analysis or explore new models are welcome. For major changes, please open an issue first to discuss what you would like to change.
