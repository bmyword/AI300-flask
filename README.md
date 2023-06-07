# Capstone Phase 1: Sample Project

_Sample Code from Loan Outcome Prediction Case Study_

**Phase 1 Objectives**

In Jupyter Notebook:
* Retrieve and conduct exploratory analysis on source dataset
* Select final model and save as `.pkl` file (from research .ipynb)

Also, under `src/` folder:
* Create `Model()` object that loads and predicts from model in `.pkl` file
* Create Flask app that takes in prediction input features (via UI or JSON), and generates prediction from model file

## Instructions to run codebase locally

Firstly, ensure you have installed all package dependencies in `requirements.txt`.

To access app `localhost:5000`, in project root directory, run
```bash
python src/app.py
```

_Note: Ensure that no other Flask app is running on port 5000!_