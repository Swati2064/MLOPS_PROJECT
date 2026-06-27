# MLflow End-to-End Machine Learning Project

## Project Overview

This project demonstrates an end-to-end Machine Learning workflow using **MLflow**. It covers experiment tracking, binary classification model training, artifact logging, and model registration.

The project is divided into three notebooks, each focusing on a different stage of the ML lifecycle.

---

## Project Structure

```
MLflow_Project/
│
├── 1stcode_experiment.ipynb
├── 2n_mlflow_binaryclassification.ipynb
├── 3rd_mlflow_model_registration.ipynb
├── Iris.csv
├── mlflow.db
├── mlruns/
├── artifacts/
└── README.md
```

---

## Project Objectives

- Understand MLflow Experiment Tracking
- Compare machine learning models
- Log parameters, metrics, and artifacts
- Register trained models
- Load registered models
- Build a reproducible ML workflow

---

## Notebook Description

### 1. Experiment Tracking (`1stcode_experiment.ipynb`)

This notebook demonstrates the basics of MLflow Experiment Tracking.

**Topics Covered**
- MLflow setup
- Creating experiments
- Starting MLflow runs
- Logging parameters
- Logging metrics
- Viewing experiments in MLflow UI

---

### 2. Binary Classification (`2n_mlflow_binaryclassification.ipynb`)

This notebook builds and evaluates a binary classification model.

**Topics Covered**
- Data preprocessing
- Train-test split
- Model training
- Model evaluation
- Accuracy calculation
- Confusion Matrix
- Logging metrics and artifacts using MLflow

---

### 3. Model Registration (`3rd_mlflow_model_registration.ipynb`)

This notebook demonstrates MLflow Model Registry.

**Topics Covered**
- Train multiple models
- Log models
- Register models
- Save confusion matrices
- Load registered models
- Compare model performance

---

## Dataset

**Dataset:** Iris Dataset

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target

- Species

Classes

- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier

---

## MLflow Features Demonstrated

- Experiment Tracking
- Run Management
- Parameter Logging
- Metric Logging
- Artifact Logging
- Model Logging
- Model Registry
- Model Loading

---

## Artifacts Generated

- Confusion Matrix Images
- Trained Models
- MLflow Run Information

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- MLflow
- Matplotlib
- Seaborn
- SQLite (mlflow.db)

---

## Installation

Install the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn mlflow
```

---

## Running the Project
----

### Step 1

Run the notebooks in the following order:

1. 1stcode_experiment.ipynb
2. 2n_mlflow_binaryclassification.ipynb
3. 3rd_mlflow_model_registration.ipynb

---

## Start MLflow UI

```bash
mlflow ui
```

Open the browser:

```
http://127.0.0.1:5000
```

---

## Expected Output

After running the notebooks, you will be able to:

- Track experiments
- Compare multiple runs
- View parameters and metrics
- Visualize confusion matrices
- Register machine learning models
- Load registered models from MLflow Registry

---

## Learning Outcomes

This project helps in understanding:

- MLflow Tracking
- MLflow UI
- Machine Learning Experiment Management
- Model Evaluation
- Model Registry
- Artifact Management
- End-to-End MLOps Workflow

---

## Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Model Versioning
- Deployment using Flask/FastAPI
- Docker Integration
- CI/CD Pipeline
- Cloud Deployment
- DVC Integration

---

## Author

**Swati Jadhav**




