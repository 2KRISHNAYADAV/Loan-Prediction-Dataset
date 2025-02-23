
# Loan Prediction Model

## 📌 Project Overview
This project focuses on predicting **loan approval status** based on various applicant details using **Machine Learning**. The dataset consists of information such as applicant income, loan amount, credit history, and other demographic details.

## 📂 Dataset Information
- **Dataset Name**: Loan Prediction Dataset
- **Features:**
  - `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`, `Property_Area`
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`
  - `Loan_Status` (Target Variable)

## 🛠️ Libraries Used
- **Pandas** – Data manipulation & cleaning
- **NumPy** – Numerical computations
- **Seaborn & Matplotlib** – Data visualization
- **Scikit-Learn** – Machine learning modeling

## 🔍 Data Preprocessing
1. **Handling Missing Values**
   - Categorical columns → Filled with the most frequent value (mode)
   - Numerical columns → Filled with the median value
2. **Encoding Categorical Variables**
   - One-hot encoding for categorical variables
3. **Outlier Detection & Removal**
   - Used **Interquartile Range (IQR) method**
4. **Feature Scaling**
   - Standardized numerical features using **StandardScaler**
5. **Train-Test Split**
   - Data split into **80% training** and **20% testing**

## 📊 Model Training & Evaluation
- **Model Used**: Logistic Regression
- **Evaluation Metrics:**
  - Accuracy Score: **80.77%**
  - Confusion Matrix & Classification Report for performance analysis

## 🚀 Next Steps
- Try different ML models (Random Forest, XGBoost, etc.)
- Tune hyperparameters for better accuracy
- Deploy model using Flask/FastAPI
- Create a visualization dashboard using Streamlit

## 🤖 How to Run the Project
1. Install dependencies:  
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
2. Run the Python script:  
   ```bash
   python loan_prediction.py
   ```

## 📢 Author
Project by **[KRISHNA SHYAMBAHADUR YADAV]**

