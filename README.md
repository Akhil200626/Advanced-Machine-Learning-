# Heart Disease Prediction Using Machine Learning

## Project Overview

This project focuses on predicting the presence of heart disease using Machine Learning classification algorithms.

Three different Machine Learning algorithms are applied to the Heart Disease dataset and their performance is compared using multiple evaluation metrics.

##  Objective

The main objectives of this project are:

* To preprocess the Heart Disease dataset.
* To train multiple Machine Learning classification models.
* To predict whether a patient has heart disease.
* To compare the performance of different algorithms.
* To identify the best-performing Machine Learning algorithm.

##  Dataset

The dataset contains patient health-related information used to predict heart disease.

### Features

| Feature    | Description                          |
| ---------- | ------------------------------------ |
| `age`      | Age of the patient                   |
| `sex`      | Gender                               |
| `cp`       | Chest pain type                      |
| `trestbps` | Resting blood pressure               |
| `chol`     | Cholesterol level                    |
| `fbs`      | Fasting blood sugar                  |
| `restecg`  | Resting electrocardiographic results |
| `thalach`  | Maximum heart rate achieved          |
| `exang`    | Exercise-induced angina              |
| `oldpeak`  | ST depression                        |
| `slope`    | Slope of peak exercise ST segment    |
| `ca`       | Number of major vessels              |
| `thal`     | Thalassemia                          |
| `target`   | Heart disease prediction             |

### Target

* `0` → No Heart Disease
* `1` → Heart Disease

##  Machine Learning Algorithms

The following algorithms are used:

### 1. Naive Bayes

A probabilistic classification algorithm based on Bayes' theorem.

### 2. Decision Tree

A tree-based classification algorithm that makes decisions using feature-based conditions.

### 3. K-Nearest Neighbors (KNN)

A distance-based algorithm that classifies a data point based on its nearest neighbors.

##  Methodology

The project follows these steps:

```text
Dataset
   ↓
Data Cleaning
   ↓
Feature & Target Separation
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Performance Comparison
   ↓
Best Model Selection
```

## Evaluation Metrics

The models are evaluated using:

* **Accuracy** – Measures the overall percentage of correct predictions.
* **Precision** – Measures how many predicted positive cases are actually positive.
* **Recall** – Measures how many actual positive cases are correctly identified.
* **F1 Score** – Provides a balance between precision and recall.
* **Confusion Matrix** – Shows correct and incorrect predictions for each class.
* **Classification Report** – Provides precision, recall, F1-score, and support.

##  Project Structure

```text
Heart-Disease-Prediction/
│
├── heart.csv
├── heart_disease_prediction.ipynb
└── README.md
```

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Installation

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

##  How to Run

1. Clone or download this repository.
2. Open Jupyter Notebook.
3. Place `heart.csv` in the same folder as the notebook.
4. Open `heart_disease_prediction.ipynb`.
5. Run the cells sequentially.
6. View the model performance and visualizations.

##  Results

The performance of the three algorithms is compared using:

```text
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
```

The notebook automatically identifies the **best-performing algorithm based on accuracy**.

##  Decision Tree Visualization

The project also includes a visualization of the trained Decision Tree to understand how the model makes classification decisions.

## Future Improvements

The project can be further improved by:

* Hyperparameter tuning
* Cross-validation
* Feature selection
* Ensemble learning
* Trying additional algorithms such as Random Forest, SVM, and Logistic Regression
* Deploying the model as a web application

## Disclaimer

This project is developed for **educational and academic purposes only**. The predictions produced by the Machine Learning models should not be considered a substitute for professional medical diagnosis.

##  Author

**Akhil**

Machine Learning Project — Heart Disease Prediction
