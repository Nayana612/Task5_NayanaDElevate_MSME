#  Diabetes Prediction using Machine Learning

This project focuses on predicting the likelihood of diabetes in patients using the Pima Indian Diabetes Dataset. A **Random Forest Classifier** is used as the primary machine learning model, 
along with essential data preprocessing and evaluation techniques.

## 📁 Dataset

- **Source**: `diabetes.csv`
- **Target Variable**: `Outcome` (0 = No diabetes, 1 = Diabetes)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

## 🛠️ Workflow

### 1. Data Preprocessing
- Missing value handling (if necessary)
- Feature scaling using `StandardScaler`

### 2. Model Building
- Model: `RandomForestClassifier` from `sklearn.ensemble`
- Trained on scaled features
- Feature importance extracted and visualized using a horizontal bar chart

### 3. Model Evaluation
- **Cross-validation** (5-fold) using `cross_val_score`
- Metric: **Accuracy**
- Provides a reliable estimate of model generalization

