# Heart Disease Prediction

## 📌 Project Overview
This project aims to predict the likelihood of heart disease in patients based on medical attributes using machine learning models. The dataset contains various health indicators, such as age, cholesterol levels, and blood pressure, which are analyzed to make predictions.

## 📊 Dataset Information
- **Total Entries:** 1025
- **Total Features:** 14
- **Key Columns:**
  - `age`: Age of the patient
  - `sex`: Gender (Male/Female)
  - `chest_pain_type`: Type of chest pain experienced
  - `resting_blood_pressure`: Patient's resting blood pressure
  - `cholestoral`: Cholesterol level in mg/dl
  - `fasting_blood_sugar`: Fasting blood sugar level
  - `rest_ecg`: Resting electrocardiographic results
  - `Max_heart_rate`: Maximum heart rate achieved
  - `exercise_induced_angina`: Whether exercise induced angina (Yes/No)
  - `oldpeak`: ST depression induced by exercise
  - `slope`: Slope of the peak exercise ST segment
  - `vessels_colored_by_flourosopy`: Number of major vessels colored by fluoroscopy
  - `thalassemia`: Blood disorder affecting hemoglobin

## ⚙️ Data Preprocessing
- **Handling Missing Values**: Checked for missing values and handled them appropriately.
- **Categorical Encoding**: Converted categorical variables into numerical values.
- **Feature Scaling**: Applied normalization/standardization to improve model performance.
- **Train-Test Split**: Divided the dataset into training and testing sets.

## 🏆 Models Used & Performance
### Machine Learning Models:
1. **Logistic Regression**
2. **Random Forest Classifier**
3. **XGBoost Classifier**

### Model Performance (Cross-Validation Scores):
- **Logistic Regression**: `0.85`
- **Random Forest Classifier**: `0.99`
- **XGBoost Classifier**: `0.99`

## 📌 How to Run
### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Script
```bash
python main.py
```

## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Author:** Arush