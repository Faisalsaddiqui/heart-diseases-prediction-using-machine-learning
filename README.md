# Heart-Diseases-Prediction-Using-Machine-Learning ❤️🧠📊
This project aims to predict heart diseases using machine learning techniques. The dataset used contains various health parameters which are used to train and evaluate the performance of different machine learning models.

## Table of Contents
[Introduction](#introduction)

[Dataset](#Dataset)

[Libraries Used](#Libraries-Used)

[Data Preprocessing](#Data-Preprocessing)

[Modeling](#Modeling)

[Evaluation](#Evaluation)

[How to Run](#How-to-Run)

[Results](#Results)

[Contributing](#Contributing)

## Introduction
Heart disease is one of the leading causes of death worldwide. Early prediction of heart disease can significantly aid in providing timely treatment and saving lives. This project leverages machine learning algorithms to predict the likelihood of heart disease based on various health parameters.

## Dataset
The dataset used in this project is a publicly available heart disease dataset, which contains several health-related attributes. The dataset is imported using the following command:
```
data = pd.read_csv('heart.csv')
```
## Libraries Used
The following Python libraries are used in this project:

pandas, numpy, matplotlib, seaborn, scikit-learn.
## Data Preprocessing
Data preprocessing steps include handling missing values, feature scaling, and encoding categorical variables. The preprocessing steps are crucial to prepare the data for model training and evaluation.

## Modeling
Several machine learning models are trained and evaluated in this project, including but not limited to:

Logistic Regression, Decision Trees, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN).
## Evaluation
The performance of the models is evaluated using various metrics such as accuracy, precision, recall, and F1-score. These metrics help in understanding the strengths and weaknesses of each model.

## How to Run
Clone the repository:
```
git clone https://github.com/your-username/heart-disease-prediction.git
```
Navigate to the project directory:
```
cd heart-disease-prediction
```
Install the required libraries:
```
pip install -r requirements.txt
```
Run the Jupyter notebook:
```
jupyter notebook "Heart Diseases Prediction Using Machine Learning.ipynb"
```
## Results
The results of the project, including the performance of different models and their respective evaluation metrics, are documented in the notebook. Visualizations and detailed explanations are provided to illustrate the findings.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.
