# Hearing Test Project Using Machine Learning

## Overview

This project aims to predict a person's hearing test result using machine learning, based on their age and physical activity score. By leveraging a logistic regression model, the system achieves an accuracy of approximately 90%. The prediction can help identify individuals at risk and enable early intervention.

## Features

- **Data-driven prediction:** Uses age and physical activity score as input features for hearing test result prediction.
- **Machine Learning Model:** Implements logistic regression for classification.
- **High Accuracy:** Achieves around 90% accuracy on test data.
- **Extensible:** The solution can be improved by adding more features or experimenting with other algorithms.

## How It Works

1. **Data Loading:** The dataset (`hearing_test.csv`) is loaded and includes age, physical activity score, and test result.
2. **Preprocessing:** The relevant features are selected: `age` and `physical_score`.
3. **Model Training:** Logistic Regression is used to train the model on the training set.
4. **Prediction & Evaluation:** The model predicts hearing test outcomes on the test set, and accuracy is calculated.
5. **Visualization:** Bar plots are used to visualize predicted vs. actual results.

## Usage

- Ensure you have the dataset file (`hearing_test.csv`).
- Run the `logistics_reg.py` script to train and evaluate the model.
- The script is written in Python and uses libraries such as Pandas, scikit-learn, and Matplotlib.

## Future Improvements

- Add more features to the dataset for improved predictions.
- Experiment with different machine learning algorithms.
- Build an interactive web app for user-friendly hearing test prediction.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- matplotlib

## Author

Created by [ASHENEE123](https://github.com/ASHENEE123)

---

> _This project demonstrates the power of machine learning in health diagnostics. Contributions and suggestions are welcome!_
