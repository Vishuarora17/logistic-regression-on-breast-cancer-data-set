Logistic Regression for Breast Cancer Prediction
Overview
This project implements a Logistic Regression model to classify breast cancer cases as malignant or benign. The dataset used is the Breast Cancer Wisconsin dataset, which contains various diagnostic measurements. The model is trained using Scikit-Learn and evaluates the accuracy using common performance metrics.

Dataset
Source: sklearn.datasets.load_breast_cancer
Features: 30 numerical attributes related to cell nuclei properties
Target Classes:
0 → Malignant
1 → Benign
Dependencies
To run this notebook, install the following Python libraries:

bash
Copy
Edit
pip install numpy pandas scikit-learn matplotlib seaborn
How to Run
Clone this repository or download the notebook.
Open the notebook in Jupyter Notebook or Google Colab.
Run all cells sequentially.
Key Steps in the Notebook
Data Loading: Import the dataset using sklearn.datasets.
Exploratory Data Analysis (EDA):
Display feature distributions.
Check for missing values.
Model Training:
Train a Logistic Regression model.
Split data into training and testing sets.
Evaluation:
Compute accuracy, precision, recall, and confusion matrix.
Visualize feature importance.
Results
The trained model achieves an accuracy of ~95%, making it a reliable predictor for breast cancer classification.
