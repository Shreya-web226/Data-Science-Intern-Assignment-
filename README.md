# Customer Record Prediction Assignment

This repository contains the solution to the customer record prediction assignment provided as part of the hiring process. The task involves predicting whether customers bought a specific product based on given demographic and activity-based features.

---

## Problem Statement

### Objective
The goal is to predict the variable **'C'** (whether a customer purchased a specific product or not) using the provided dataset:

1. **Dataset.txt**: Contains customer records with features `F1-F22` and target variable `C`.
2. **Dataset_test.txt**: Contains customer records with features `F1-F22` but without the target variable `C`. This file is used for testing the prediction model.

---

### Deliverables
The output consists of the following:

1. **Predictions for Training Dataset**: File in the format `Index<tab-delimited>Class`.
2. **Predictions for Test Dataset**: File in the format `Index<tab-delimited>Class`.
3. **Training Script**: Python script implementing the predictive model.
4. **Detailed Report**: Explanation of the approach, data preprocessing, modeling technique, evaluation metrics, and results, along with visualizations.

---

## Solution Overview

### Files in This Repository

1. **`training_predictions.txt`**: Predictions for the training dataset in the specified format.
2. **`test_predictions.txt`**: Predictions for the test dataset in the specified format.
3. **`training_script.py`**: Python script used for data preprocessing, feature engineering, model training, and evaluation.
4. **`report.pdf`**: A detailed explanation of the solution approach.

---

## Approach

1. **Data Understanding**:
   - Features (`F1-F22`): Combination of demographic data and aggregated past activity data.
   - Target Variable (`C`): Binary outcome indicating whether a customer purchased the product.

2. **Data Preprocessing**:
   - Handled missing values by filling numeric columns with their mean and categorical columns with their mode.
   - Scaled features for uniformity (if required).

3. **Feature Engineering**:
   - Explored correlations between features and the target variable.
   - Addressed class imbalance using appropriate techniques.

4. **Model Selection**:
   - Experimented with different classification models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
   - Selected the best-performing model based on evaluation metrics.

5. **Evaluation Metrics**:
   - Accuracy
   - Precision, Recall, F1-Score
   - ROC-AUC Curve

6. **Results**:
   - Training and test predictions are provided in the required formats.
   - Visualizations and key insights are included in the report.

---

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repository-name>.git
   ```

2. Navigate to the repository:
   ```bash
   cd <repository-name>
   ```

3. Ensure the required Python libraries are installed:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the training script:
   ```bash
   python training_script.py
   ```

5. The predictions will be saved in `training_predictions.txt` and `test_predictions.txt`.

---

## Contact
For any questions or concerns, please reach out to:

- **Shreya Thakur**
- Email: [Your Email Address]
- LinkedIn: [Your LinkedIn Profile]

---

Thank you for the opportunity!

---

### Acknowledgment
Special thanks to **Akash D**, Talent Acquisition Specialist, for providing this assignment and guiding the process.

