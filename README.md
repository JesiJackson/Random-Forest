## 🌲 Loan Default Prediction Using Random Forest

You work for a company that provides car loans with interest rates. Recently, loan underwriters have been issuing a significant number of loans that end up defaulting. As a result, there’s a need to improve the underwriting process. To address this issue, you decide to use a **Random Forest algorithm** to enhance the accuracy and reliability of loan approvals.

---

### 🧪 Project Overview

This research employed a binary target variable, **default payment** (`1 = Yes`, `0 = No`), and used 23 explanatory variables derived from demographic information and financial behavior, including:

* **Credit amount**, **age**, **gender**, **education**, and **marital status**
* **Payment history** over 6 months
* **Monthly bill statements** and **payment amounts**

---

### 📊 What You'll Find in This Repository

* **Data Preprocessing**: Handling categorical values, missing data, and scaling as needed
* **Exploratory Data Analysis (EDA)**: Visualizing variable distributions, correlations, and class imbalance
* **Random Forest Modeling**: Training, tuning hyperparameters, and applying the model to classify defaults
* **Model Evaluation**:

  * Confusion matrix
  * Accuracy, precision, recall, and F1-score
  * Feature importance ranking

---

### ✅ Key Results

* The **Random Forest classifier achieved high accuracy**, effectively distinguishing between default and non-default customers.
* **Precision and recall** metrics were balanced, showing the model's reliability in identifying high-risk clients.
* The most important features included:

  * **Repayment status in recent months**
  * **Amount of credit given**
  * **Bill statement history**

These results suggest that the Random Forest model can support better decision-making in the loan underwriting process by identifying potential defaulters more accurately.

---

### 🧰 Tools & Technologies

* **Pandas**, **NumPy**, **Scikit-learn**, **Matplotlib**, **Seaborn**

---



More information about variables:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

X4: Marital status (1 = married; 2 = single; 3 = others).

X5: Age (year).

X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005. 

X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.
