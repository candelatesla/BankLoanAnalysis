# Bank Loan Analysis 🏦

**A data analysis project exploring bank loan distribution, default rates, and borrower trends.**

This project performs Exploratory Data Analysis (EDA) on a bank loan dataset to understand the factors affecting loan approval and repayment statuses. It aims to identify patterns in bad loans versus good loans using statistical visualizations.

---

## 📊 Project Overview

The goal of this analysis is to answer key business questions, such as:
* What is the ratio of fully paid loans vs. charged-off (defaulted) loans?
* How does the interest rate vary across different loan grades?
* Which purpose (e.g., debt consolidation, home improvement) attracts the most loans?
* Is there a correlation between annual income and loan amount?

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Libraries:**
  * `pandas` (Data Manipulation)
  * `matplotlib` & `seaborn` (Data Visualization)
  * `numpy` (Numerical Operations)
* **Environment:** Jupyter Notebook / Google Colab

---

## 📉 Key Insights & Visualizations

The analysis includes several key plots:

1.  **Loan Status Distribution:** A breakdown of how many loans are 'Fully Paid', 'Current', or 'Charged Off'.
2.  **Loan Grade vs. Interest Rate:** Analyzing how riskier loan grades correlate with higher interest rates.
3.  **Purpose of Loan:** Visualizing the primary reasons borrowers take loans (mostly Debt Consolidation).
4.  **Geographic Distribution:** Mapping where the majority of borrowers are located (by State).

---

## 🚀 How to Run

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/candelatesla/BankLoanAnalysis.git](https://github.com/candelatesla/BankLoanAnalysis.git)
    cd BankLoanAnalysis
    ```

2.  **Install Dependencies**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

3.  **Launch the Notebook**
    ```bash
    jupyter notebook
    ```
    Open the `.ipynb` file to interact with the analysis.

---

## 📂 Dataset

The dataset used includes columns such as:
* `loan_amount`: The amount of money applied for.
* `term`: The number of payments (36 or 60 months).
* `int_rate`: Interest Rate on the loan.
* `grade`: Loan grade assigned by the bank.
* `emp_length`: Employment length in years.
* `home_ownership`: RENT, OWN, MORTGAGE, etc.

---

## 👤 Author

**Yash Chetan Doshi**
