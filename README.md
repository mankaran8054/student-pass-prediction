#  Student Pass/Fail Prediction (Machine Learning Project)

##  Overview

This project predicts whether a student will **Pass or Fail** based on academic and lifestyle factors using a Machine Learning classification model.

The model analyzes patterns from student data and makes predictions using a trained **Logistic Regression algorithm**.

---

## Features Used

The model uses the following input features:

* Hours Studied
* Attendance (%)
* Sleep Hours
* Previous Exam Score

---

##  Machine Learning Workflow

1. Data Loading
2. Feature Selection
3. Data Scaling (StandardScaler)
4. Train/Test Split
5. Model Training (Logistic Regression)
6. Evaluation Metrics
7. Confusion Matrix Visualization
8. Model Saving using Pickle

---

##  Model Performance

The model is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

##  How to Run the Project

### 1️ Install dependencies

```
pip install pandas scikit-learn matplotlib seaborn
```

### 2️ Run training script

```
python train.py
```

### 3️ Run prediction script

```
python predict.py
```

---

##  Project Structure

```
Student-Pass-Prediction/
│
├── dataset.csv
├── train.py
├── predict.py
├── model.pkl
├── scaler.pkl
└── README.md
```

---

##  Example Prediction

Input:

```
Study Hours = 6  
Attendance = 75  
Sleep Hours = 7  
Previous Score = 68
```

Output:

```
PASS
```

---

##  Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

##  Future Improvements

* Add web interface
* Deploy model online
* Add more features for prediction
* Improve accuracy with advanced models

---

##  Author

Mankarandeep singh

---

*If you like this project, consider giving it a star on GitHub!*

