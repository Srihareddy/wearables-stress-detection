# Wearable Stress Detection System

## Overview
This project implements an AI-driven stress detection system using physiological data collected from wearable devices. By analyzing biosignals such as heart rate, electrodermal activity, and body temperature, machine learning models are used to classify stress and non-stress states.

The project demonstrates an end-to-end AI and data analytics pipeline, highlighting how wearable sensor data can be transformed into actionable insights for health monitoring applications.

---

## Problem Statement
Stress assessment is traditionally subjective and self-reported. This project addresses that limitation by building an automated and objective stress detection framework using wearable sensor data and supervised machine learning techniques.

---

## Dataset
- Wearable sensor data containing physiological signals
- Features include:
  - Heart Rate (HR)
  - Electrodermal Activity (EDA)
  - Skin / Body Temperature
  - Activity-related measurements
- Preprocessing includes noise removal, normalization, and missing value handling

---

## AI & Machine Learning Approach
### Data Preprocessing
- Missing value imputation
- Feature scaling and normalization
- Signal transformation for improved model learning

### Exploratory Data Analysis (EDA)
- Statistical and correlation analysis
- Visualization of stress vs non-stress patterns

### Model Development
- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- Neural Networks (if applicable)

### Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Cross-validation

---

## Technologies Used
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Results
- Achieved reliable classification of stress vs non-stress states
- Tree-based and ensemble models demonstrated strong predictive performance
- Validated feasibility of AI-based stress monitoring using wearable data

---

## Project Structure
Wearable-Stress-Detection/
├── data/
├── notebooks/
├── src/


---

## How to Run
```bash
git clone https://github.com/your-username/wearable-stress-detection.git
cd wearable-stress-detection
pip install -r requirements.txt
jupyter notebook
