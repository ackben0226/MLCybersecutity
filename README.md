# Enhancing Cybersecurity Resilience: Leveraging Machine Learning for Advanced Threat Detection and Response
## Table of Content 
- Project Description
- Features
- Installation
- Usage
- Datasets
- Machine Learning Models
- Evaluation Metrics
- Contributing
- License
- Acknowledgments
## Project Description
This project explores the application of machine learning techniques to cybersecurity, focusing on network traffic classification for intrusion detection. It compares supervised learning models like Random Forest (RF), XGBoost (XGB), Decision Trees (DT), and Support Vector Machines (SVM) across benchmark datasets such as CICIDS2017 and UNSW-NB15. The research aims to enhance threat detection accuracy, minimize false positives, and optimize resource use in cybersecurity operations.
## Features
- Supervised Learning Models: Implementation of multiple models (RF, XGB, DT, SVM) to detect cyber threats in network traffic.
- Comparative Analysis: Model performance comparison based on accuracy, precision, recall, and F1-score.
- Data Preprocessing: Techniques like handling missing values, outlier mitigation, and feature scaling.
- Evaluation Metrics: Use of precision, recall, F1-score, and ROC-AUC for performance analysis.
## Installation
- Clone the repository:
git clone https://[github.com/ackben0226/cybersecurity-ml.git](https://github.com/ackben0226/MLCybersecutity/blob/main/ML%20Cybersecurity%20project/Final_CICIDS2017%20(3).ipynb)
1. Install dependencies:
<br/> pip install jupyterlab pandas scikit-learn matplotlib
2. Launch the notebook:
<br/> jupyter notebook
## Download datasets:
UNSW-NB15 Dataset: [Link](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- This dataset contains network traffic with both normal and malicious activities and is used for training and testing network intrusion detection systems (NIDS).
  
CICIDS2017 Dataset: [Link](https://www.unb.ca/cic/datasets/ids-2017.html)
 - This dataset includes network traffic and various types of malicious attacks such as DDoS, Brute Force, and Infiltration attacks, useful for intrusion detection research.
- Run the setup script:
python setup.py
Usage
Preprocess the Data: Run the following command to preprocess the datasets.

## python preprocess.py
Train Machine Learning Models: To train the models on the datasets, use:
python train_model.py
Evaluate Models: After training, you can evaluate model performance using:
python evaluate.py
## Datasets
## UNSW-NB15
The UNSW-NB15 dataset contains 257,673 records and includes 49 features that represent nine types of attacks.
## CICIDS2017
CICIDS2017 contains 251,496 instances and 79 features covering 14 attack types.
## Machine Learning Models
- Random Forest (RF): A versatile model that operates by constructing multiple decision trees.
- XGBoost (XGB): A gradient boosting framework used for more efficient and faster learning.
- Decision Trees (DT): A model that splits the data into subsets based on the most significant features.
- Support Vector Machines (SVM): A robust classifier using hyperplanes to separate different classes.
## Evaluation Metrics
- Accuracy: Measures the overall correctness of the model’s predictions.
- Precision: The ratio of correctly predicted positive observations.
- Recall: The ratio of correctly predicted positive observations to all actual positives.
- F1-Score: A weighted average of precision and recall.
- ROC-AUC: Measures the performance of classification models at various threshold settings.
## Acknowledgments
- Special thanks to my supervisor, Dr. Imran Khan, for his guidance throughout this research.
- This project utilizes the datasets provided by UNSW and the Canadian Institute for Cybersecurity.
