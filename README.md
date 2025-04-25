# medical-condition-prediction
A machine learning project that predicts patient medical conditions using real-world hospital data. Includes data preprocessing, feature engineering, and model evaluation using Random Forest classification.
# 🩺 Medical Condition Prediction from Patient Data

This project uses a healthcare dataset to build a machine learning model that predicts a patient's **medical condition** based on information like age, gender, blood type, insurance, test results, and billing amount.

## 📁 Dataset

- Source: [Kaggle – Healthcare Dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset)
- Size: 55,500 records
- Features include:
  - `Age`, `Gender`, `Blood Type`
  - `Insurance Provider`, `Admission Type`
  - `Billing Amount`, `Test Results`
  - Target: `Medical Condition` (6 unique values)

## 🧼 Data Preprocessing

- Removed negative values in billing amounts
- Cleaned inconsistent blood type entries
- One-hot encoded categorical variables
- Scaled numeric features (age and billing)

## 🧠 Model

- Used **Random Forest Classifier**
- 80/20 train-test split
- Scaled numeric features using `StandardScaler`

### 📊 Evaluation Results:

- **Accuracy:** ~XX%  *(← fill in your result!)*
- **Confusion Matrix:** Visualized performance across conditions
- **Classification Report:** Included precision, recall, and F1-score

## 📌 Key Insights

- Age and billing amount had moderate predictive value.
- Test results and admission type were useful for differentiating conditions.
- The model could be improved with feature engineering or handling class imbalance.

## 🚀 Future Work

- Try more models (e.g., XGBoost, Logistic Regression)
- Handle potential class imbalance
- Incorporate hospital stay duration as a feature
- Hyperparameter tuning for improved accuracy

## 🛠️ Tools & Libraries

- Python, pandas, numpy
- Scikit-learn
- Seaborn, matplotlib
- Jupyter / Kaggle Notebooks

## 📎 Project Links

- 📘 [Kaggle Notebook](https://www.kaggle.com/ozipeck)  
- 💻 [Live Notebook (GitHub)](link-to-notebook.ipynb)

---

## 🙋‍♀️ About Me

I’m a data analyst passionate about healthcare and predictive modelling.  
Open to internship opportunities and collaboration!

**Connect on [LinkedIn](ipekozturkusa)
