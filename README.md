How to Run the Jupyter Notebook

Follow the steps below to run the project notebook and reproduce all results.

1. Download or Clone the Repository
2. git clone <your_repository_link>
cd <repository_folder>

Alternatively, you can download the ZIP file from GitHub and extract it.

2. Open the Notebook in Google Colab (Recommended)

Go to https://colab.research.google.com

Click Upload Notebook

Select the file:
Tools-Project.ipynb
Also upload the dataset file:
WA_Fn-UseC_-Telco-Customer-Churn.csv

3. Install Required Libraries in Colab

Some libraries (such as xgboost) may not be installed by default.
Run the following cell in the notebook before executing other cells:
!pip install xgboost

4. Upload the Dataset Inside the Notebook

In the dataset loading section, run the upload cell:
from google.colab import files
uploaded = files.upload()
Choose the file:
WA_Fn-UseC_-Telco-Customer-Churn.csv
The notebook will automatically load the dataset.

5. Run All Cells

After uploading the dataset:

Click “Runtime”

Select “Run all”

This will execute the following sections in order:

Importing libraries

Loading the dataset

Exploratory Data Analysis (EDA)

Data cleaning and preprocessing

Visualizations

Machine learning model training

Evaluation (Accuracy, Precision, Recall, F1-score, Confusion Matrix)

Model comparison

All results will appear directly in the notebook.


6. Understanding the Outputs

During execution, the notebook produces:

Dataset summaries

Charts and visualizations

Preprocessing steps

Predictions from multiple machine learning models

Evaluation metrics

A final comparison table showing model accuracy

These outputs help understand the dataset and the predictive performance of each algorithm.




Short Project Summary

This project analyzes the IBM Telco Customer Churn dataset to understand factors influencing telecom customer churn. The dataset undergoes exploratory analysis, cleaning, encoding, and feature scaling. Several machine learning models are trained, including Logistic Regression, Decision Tree, Random Forest, XGBoost, and KNN. Each model is evaluated using accuracy, precision, recall, F1-score, and confusion matrices. Logistic Regression achieved the highest accuracy, making it the best-performing model for this dataset. The project demonstrates practical end-to-end application of data science techniques for churn prediction.

