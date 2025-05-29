# ML-TASK3
Implement and understand **simple and multiple linear regression** using a real-world dataset. The goal is to train a model to predict a continuous value (e.g., house rent) using one or more numerical features.

# 🧠 AI & ML Internship - Task 3: Linear Regression

## 📌 Objective

Implement and understand **simple and multiple linear regression** using a real-world dataset. The goal is to train a model to predict a continuous value (e.g., house rent) using one or more numerical features.

---

## 📁 Dataset

**Dataset Used:** [House Rent Dataset]  
- Loaded from: `/content/Lab 27 House_Rent_Dataset.csv`  
- Contains features like `Size`, `Bathroom`, `BHK`, and the target variable `Rent`.

---

## ✅ Steps Performed

1. **Imported & cleaned the dataset**  
   - Used `pandas` to handle data  
   - Dropped missing values using `dropna()`  

2. **Exploratory Data Analysis (EDA)**  
   - Inspected column names, datatypes, and basic statistics  
   - Visualized relationships between features and target using `seaborn`

3. **Feature Selection**  
   - Chose numerical features like `Size`, `Bathroom`, and `BHK`  
   - Target variable: `Rent`

4. **Train-Test Split**  
   - Used `train_test_split()` from `sklearn.model_selection`  
   - 80% training, 20% testing

5. **Model Training**  
   - Used `LinearRegression()` from `sklearn.linear_model`  
   - Trained both simple and multiple linear regression models

6. **Model Evaluation**  
   - Evaluated using:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score (R²)

7. **Visualization**  
   - Plotted regression line for simple linear regression (e.g., `Size` vs `Rent`)

---

## 📊 Results

| Metric | Value |
|--------|-------|
| MAE    | _(insert value)_ |
| MSE    | _(insert value)_ |
| R²     | _(insert value)_ |

---

## 📈 Visualization

> A scatter plot with a regression line showing the relationship between **Size** and **Rent**.

---

## 💬 Interview Questions & Answers

1. **What assumptions does linear regression make?**  
   - Linearity, independence, homoscedasticity, normal distribution of errors, no multicollinearity.

2. **How do you interpret the coefficients?**  
   - Coefficients represent the change in the target variable for a one-unit change in the feature, keeping other features constant.

3. **What is R² score and its significance?**  
   - R² indicates how well the model explains the variance in the target variable. Closer to 1 means a better fit.

4. **When would you prefer MSE over MAE?**  
   - MSE penalizes large errors more, so use it when large errors are particularly undesirable.

5. **How do you detect multicollinearity?**  
   - Using correlation matrix or Variance Inflation Factor (VIF).

6. **What is the difference between simple and multiple regression?**  
   - Simple regression uses one feature; multiple regression uses two or more features to predict the target.

7. **Can linear regression be used for classification?**  
   - Not directly. Logistic regression is preferred for binary classification.

8. **What happens if you violate regression assumptions?**  
   - It can lead to unreliable or biased predictions.

---

## 🧾 Files Included

- `linear_regression_task3.ipynb`: Jupyter Notebook with code
- `Lab 27 House_Rent_Dataset.csv`: Dataset used
- `README.md`: Project description and documentation
- `screenshots/`: (Optional) EDA or regression plots

---

## 🚀 How to Run

1. Clone the repository
2. Open `linear_regression_task3.ipynb` in Jupyter/Colab
3. Run all cells to train the model and view results

---

## 🔗 Submission

**GitHub Repo Link:**  
[Paste your GitHub repo URL here]

**Internship Task Link:**  
[Submit your repo here as per the instructions]

