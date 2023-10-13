---
title: Oct 14
category: Days
order: 3
---


ROC Curve:
from sklearn.metrics import roc_curve

ROC AUC Curve:
from sklearn.metrics import roc_auc_score

Precision Recall Curve:
from sklearn.metrics import precision_recall_curve

Accuracy Score:
from sklearn.metrics import accuracy_score

confusion matrix:
from sklearn.metrics import confusion_matrix

FScore:
from sklearn.metrics import accuracy_score, confusion_matrix, precision_recall_fscore_support

Average Precision Score:
from sklearn.metrics import average_precision_score


Sample project
```
project_name/
|-- data/
|   |-- raw/
|   |-- processed/
|   |-- train/
|   |-- test/
|-- notebooks/
|   |-- 01_data_exploration.ipynb
|   |-- 02_data_preprocessing.ipynb
|   |-- 03_feature_engineering.ipynb
|   |-- 04_model_training.ipynb
|   |-- 05_model_evaluation.ipynb
|   |-- 06_model_tuning.ipynb
|   |-- 07_model_interpretation.ipynb
|-- scripts/
|   |-- data_preprocessing.py
|   |-- feature_engineering.py
|   |-- model_training.py
|   |-- model_evaluation.py
|   |-- model_tuning.py
|   |-- model_interpretation.py
|-- models/
|   |-- model1.pkl
|   |-- model2.pkl
|-- utils/
|   |-- data_utils.py
|   |-- model_utils.py
|   |-- visualization.py
|-- config/
|   |-- hyperparameters.json
|   |-- settings.ini
|-- deployment/
|   |-- api/
|       |-- app.py
|   |-- docker/
|       |-- Dockerfile
|       |-- requirements.txt
|   |-- model_server/
|       |-- server.py
|-- main.py
|-- README.md
|-- requirements.txt

```