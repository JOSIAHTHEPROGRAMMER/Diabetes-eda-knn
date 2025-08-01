# Diabetes Prediction using K-Nearest Neighbors (KNN)

This project focuses on exploratory data analysis (EDA) and building a machine learning model to predict the presence of diabetes in patients using the Pima Indians Diabetes Dataset.

The model is based on the K-Nearest Neighbors (KNN) algorithm and is implemented in a Jupyter Notebook using Python libraries such as pandas, seaborn, matplotlib, and scikit-learn.

---

## Dataset

The dataset used is available on [Kaggle](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset). It contains several medical predictor variables and one target variable (`Outcome`) that indicates whether or not a patient has diabetes.

**Features:**

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 = No diabetes, 1 = Diabetes)

---

## Exploratory Data Analysis (EDA)

The notebook includes:

- Overview of dataset structure and summary statistics
- Missing value analysis and handling
- Distribution plots (histograms, KDEs)
- Outlier detection with boxplots
- Correlation heatmap
- Standardization of features using `StandardScaler`

---

## Machine Learning

### Algorithm Used:
- **K-Nearest Neighbors (KNN)** classifier

### Steps:
- Data preprocessing and feature scaling
- Splitting data into training and test sets (70%/30%)
- Training the KNN model with `k=13`
- Evaluating performance using:
  - Accuracy score
  - Confusion matrix
  - Classification report (precision, recall, F1-score)

---

## Visualizations

- Countplot for target variable (`Outcome`)
- Boxplots for outlier detection
- Histograms with KDE curves for feature distributions
- Correlation heatmap
- Line plot for KNN performance over different values of `k`

---

##  Project Structure

```bash
├── dataset/
│ └── eda-on-diabetes-dataset.ipynb 
├── README.md 
└── requirements.txt 
```
