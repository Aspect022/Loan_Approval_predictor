
---

# 🏦 Loan Approval Prediction using Machine Learning

This is a simple classification project to predict whether a loan application will be approved or not, based on applicant details like income, dependents, education, employment status, property area, and more. The project uses a publicly available dataset and implements a Logistic Regression model.

---

## 📊 Dataset Description

The dataset contains the following columns:

| Column Name        | Description                                                   |
|:-----------------:|:--------------------------------------------------------------|
| Loan_ID            | Unique identifier for each loan application                   |
| Gender             | Applicant's gender                                            |
| Married            | Marital status                                                |
| Dependents         | Number of dependents (0, 1, 2, 3+)                            |
| Education          | Applicant's education level (Graduate / Not Graduate)         |
| Self_Employed      | Employment status                                             |
| ApplicantIncome    | Applicant's income                                            |
| CoapplicantIncome  | Co-applicant's income                                         |
| LoanAmount         | Loan amount applied for                                       |
| Loan_Amount_Term   | Term of loan in months                                        |
| Credit_History     | Applicant's credit history (1.0 = good, 0.0 = bad)            |
| Property_Area      | Type of property area (Urban / Semiurban / Rural)             |
| Loan_Status        | Loan approval status (Y = Approved, N = Rejected) *(Target)*  |

---

## 📝 Project Workflow

1. **Data Loading**
2. **Data Cleaning**
   - Handle missing values
   - Replace categorical anomalies (e.g., '3+' in Dependents)
3. **Data Encoding**
   - Label Encoding for categorical variables
4. **Train-Test Split**
5. **Model Training**
   - Logistic Regression
6. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix

---

## 📌 Dependencies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook (optional for running locally)

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/loan-approval-prediction.git
   cd loan-approval-prediction


2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or Python file:

   ```bash
   jupyter notebook Loan_Approval_Prediction.ipynb
   ```

---

## 📊 Results

Achieved an accuracy of **90%** using Logistic Regression. 

---

## 📚 Future Work

* Implement other classification models (Decision Tree, Random Forest, XGBoost)
* Perform hyperparameter tuning
* Deploy the model using Flask or FastAPI
* Integrate with a frontend interface

---

## 🧑‍💻 Author

* **Jayesh RL**
* [LinkedIn]([https://www.linkedin.com](https://www.linkedin.com/in/jayesh-rl-748059291/)) 
* [GitHub]([https://github.com/your-username](https://github.com/Aspect022))

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

