# cricket-predictive-model
This repository contains a project focused on predicting the likelihood of a wicket falling in a T20 cricket match. Using a deep learning approach, the project utilizes ball-by-ball data from cricket matches to build a predictive model.

Key Features:

Data Loading: Reads and processes T20 cricket match data from YAML files, including ball speed, stump coverage, and ball landing coordinates.
Data Preprocessing: Cleans and prepares the data for model training, including feature extraction and dataset splitting.
Model Building: Constructs a neural network model using TensorFlow and Keras to predict the probability of a wicket falling.
Custom Metrics: Implements a custom metric to evaluate the model's performance in terms of expected wickets (xW).
Visualization: Provides visualizations of training history, including accuracy and loss metrics.
Evaluation: Evaluates the model on test data and compares predicted vs. actual outcomes.
Usage:

Clone this repository to your local machine.
Install the required dependencies listed in requirements.txt.
Open the Jupyter Notebook and run the cells to execute the code.
Dependencies:

TensorFlow
Keras
Pandas
NumPy
Matplotlib
scikit-learn
Purpose:

The goal of this project is to explore how machine learning can be applied to cricket data for predictive analysis. By leveraging deep learning techniques, the model aims to enhance decision-making in cricket by forecasting wicket occurrences based on ball and player statistics.

