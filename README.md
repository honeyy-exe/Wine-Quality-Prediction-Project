# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Overview
Developed a machine learning model to predict wine quality based on physicochemical properties such as acidity, pH, alcohol content, and residual sugar. The project focuses on data analysis, visualization, and classification using ensemble learning techniques.

---

## 🎯 Objective
To analyze key factors affecting wine quality and build a predictive model that classifies wines as **good** or **bad**.

---

## 📊 Dataset
- Source: Wine Quality Dataset (Red Wine)
- Features include:
  - Fixed Acidity
  - Volatile Acidity
  - Citric Acid
  - Residual Sugar
  - Chlorides
  - Alcohol
  - pH, etc.

---

## ⚙️ Tech Stack
- **Programming:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn  

---

## 🔍 Project Workflow
1. **Data Collection & Cleaning**
   - Loaded dataset and checked for missing values  
   - Dataset found to be clean and ready for analysis  

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions  
   - Analyzed relationships using bar plots and count plots  

3. **Correlation Analysis**
   - Generated a heatmap to identify feature relationships  

4. **Data Preprocessing**
   - Separated features and target variable  
   - Applied label binarization (Good vs Bad quality)  

5. **Model Training**
   - Used **Random Forest Classifier**  
   - Split dataset into training and testing sets  

6. **Model Evaluation**
   - Evaluated using accuracy score  

7. **Prediction System**
   - Built a system to predict wine quality from input values  

---

## 🤖 Model Used
- Random Forest Classifier (Ensemble Learning)

---

## 📈 Results
- Achieved reliable accuracy in classifying wine quality  
- Demonstrated effectiveness of ensemble models on structured data  

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python wine_quality_prediction.py
