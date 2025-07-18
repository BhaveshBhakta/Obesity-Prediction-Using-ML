# Obesity Prediction Using Machine Learning

## Project Overview

This project focuses on predicting **obesity levels** based on a variety of physiological, behavioral, and lifestyle factors using supervised machine learning. The classification model categorizes individuals into different obesity levels using structured health-related data, aiming to support proactive healthcare decisions and awareness.

---

## Technical Highlights

* **Dataset**:

  * 2,111 samples and 17 features
  * Includes both **numerical** (age, BMI, water intake, physical activity) and **categorical** (gender, diet habits, alcohol, transport) attributes
  * Target label: `Obesity` (multiclass categories)

* **Exploratory Data Analysis**:

  * Analyzed distributions of variables like age, gender, water/alcohol intake
  * Visualized correlations between numerical features (e.g., BMI vs Obesity)
  * Investigated lifestyle factors (e.g., transportation, smoking, eating habits)

* **Preprocessing**:

  * Dropped duplicates
  * Feature engineering (e.g., calculated `BMI`)
  * Encoding: Ordinal, One-Hot, and Label Encoding
  * Feature scaling using Standard Scaler

* **Model Building**:

  * Used `GradientBoostingClassifier` for multiclass classification
  * Achieved **training accuracy of 100%** and **testing accuracy of 97%**

* **Evaluation**:

  * Used confusion matrices and performance metrics (Accuracy, Precision, Recall, F1-score)
  * Achieved strong generalization performance across all obesity classes

---

## Key Use Cases

* Predictive tool for **obesity level classification** in health-tech applications
* Enables **personalized fitness or diet recommendations**
* Supports **health insurance** assessments based on lifestyle risk factors
* Useful in **preventive healthcare analytics**

---

## Installation

 **Clone the repository**

   ```bash
   git clone https://github.com/BhaveshBhakta/Obesity-Prediction-Using-ML.git
   cd Obesity-Prediction-Using-ML
   ```


---

## Contributions

Contributions are welcome! If you’d like to improve model performance, add new visualizations, or integrate the project with a web interface.
