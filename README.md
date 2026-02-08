Electricity Consumption Classification

This project applies machine learning classification techniques to electricity consumption data to identify and compare consumer usage patterns. Using historical electricity load data, multiple classification models are trained and evaluated to analyze their predictive performance.

The project is implemented entirely in a Jupyter Notebook and is intended for academic and portfolio purposes.

Dataset
Source: UCI Machine Learning Repository
Electricity Load Diagrams 2011–2014
https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014

The dataset contains electricity consumption measurements for 370 clients.
Each column represents a client’s electricity usage.
Rows represent time-based consumption values.

Objectives:
Preprocess and prepare electricity consumption data for classification
Train multiple machine learning classifiers
Evaluate and compare model performance
Visualize results using standard classification metrics

Models Used:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier

Feature Selection and Data Assumptions:
The dataset contains heterogeneous columns, where each column represents electricity consumption data from a different client. Because these columns cannot be directly comparable as simultaneous features, the classification models do not use all columns together.
Instead - a single selected column is used as the input feature set for each experiment.

This approach ensures feature consistency and avoids mixing heterogeneous consumption patterns across different clients.
Data Processing:
Data cleaning and preprocessing
Feature scaling / normalization
Train-test split

Evaluation Metrics:
Accuracy
Confusion Matrix
ROC Curve
AUC
Visualizations are used to clearly compare model performance.

Libraries Used:
Python
Jupyter Notebook
Pandas
NumPy
Scikit-learn
Matplotlib
