# 🩺 Medical Insurance Cost Prediction

This project uses a regression model to predict **medical insurance charges** based on individual features such as age, BMI, number of children, smoking status, sex, and region. The goal is to explore how these factors affect insurance pricing using machine learning.

---

## 📁 Dataset

* **Source**: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
* **Features**:

  * `age`: Age of the primary beneficiary
  * `sex`: Gender
  * `bmi`: Body Mass Index
  * `children`: Number of children covered by health insurance
  * `smoker`: Whether the person smokes
  * `region`: Residential area in the US
  * `charges`: Final insurance cost *(target variable)*

---

## 🚀 Project Workflow

1. **Data Exploration & Cleaning**

   * Checked for missing values
   * Explored distributions and correlations
2. **Feature Encoding**

   * Applied **one-hot encoding** to categorical columns (`sex`, `smoker`, `region`)
3. **Model Building**

   * Used **Linear Regression** from `scikit-learn`
4. **Model Evaluation**

   * R² Score: \~0.69
   * MAE, MSE, RMSE for error analysis
5. **Insights**

   * Smokers pay significantly more
   * Charges increase with age and BMI

---

## 📊 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## 📂 Repository Contents

| File                     | Description                          |
| ------------------------ | ------------------------------------ |
| `insurance.csv`          | Dataset used for training            |
| `medicalinsurance.ipynb` | Main notebook with code and analysis |
| `README.md`              | Project documentation                |
