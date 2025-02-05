# 📊 Bank Customer Churn Prediction and Analysis Project"

## 🎯 Objective 1: Profile & Explore the Data

1. **Data Import and Data Type Assignment:**
   - Imported the `Bank_Churn.csv` file and assigned appropriate data types to each column.

2. **Missing Values Check:**
   - Checked for missing values and handled them appropriately.
   - Calculated the minimum, maximum, and mean for all numeric columns.

3. **Scatterplot Matrix:**
   - Built a scatterplot matrix to examine relationships between pairs of numeric columns.

4. **Box Plots by Target Variable:**
   - Created box plots for each numeric column grouped by the target variable `Exited`.

5. **Categorical Analysis:**
   - Built bar charts to display the percentage of `Exited` customers for each category in categorical columns.

---

## 🎯 Objective 2: Prepare the Data for Modeling

1. **Feature Selection:**
   - Dropped columns unsuitable for modeling based on their relevance and data quality.

2. **Feature Engineering:**
   - Created a new column `balance_to_income` by dividing `Balance` by `EstimatedSalary`.
   - Created a new column `income_v_products` by dividing `EstimatedSalary` by `NumOfProducts`.

3. **Dummy Variable Creation:**
   - Generated dummy variables for all categorical columns for model compatibility.

4. **Data Splitting:**
   - Split the dataset into training and testing sets with 80% for training and 20% for testing.

---

## 🎯 Objective 3: Build & Evaluate a Logistic Regression Model

1. **Model Fitting:**
   - Trained a logistic regression model using the training data.

2. **Confusion Matrix:**
   - Evaluated model predictions with a confusion matrix.

3. **Performance Metrics:**
   - Calculated accuracy, precision, recall, and F1 score for the test dataset.

4. **ROC Curve:**
   - Plotted an ROC curve and calculated the AUC statistic.

5. **Threshold Analysis:**
   - Plotted precision and recall against the model threshold to find the optimal value for high recall while maintaining precision above 50%.

---

## 🎯 Objective 4: Fit & Tune a Random Forest Model

1. **Initial Model:**
   - Trained a random forest model with default hyperparameters.

2. **Hyperparameter Tuning:**
   - Used cross-validation to fine-tune the model's hyperparameters.

3. **Final Evaluation:**
   - Reported the final test accuracy and AUC score for the optimized model.

4. **Feature Importance:**
   - Visualized feature importance using a bar chart.

---

## ✨ Key Outcomes
- Built models to predict customer churn with actionable insights.
- Feature engineering and exploratory data analysis improved model accuracy.
- Random forest model tuning resulted in higher performance metrics compared to logistic regression.

---

## 📂 Files Included
- **Python Notebook:** `final bank churn project.ipynb`
- **HTML Report:** `final bank churn project.html`
- **Dataset:** `Bank_Churn.csv`

---

This project demonstrates skills in data cleaning, feature engineering, and predictive modeling to provide actionable business insights. Let me know if you’d like to collaborate or discuss further!
