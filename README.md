<!DOCTYPE html>
<html lang="en">
<body>
  <h1>Heart Disease Prediction</h1>

  <p>This repository contains code for predicting heart disease using logistic regression. The model is trained on patient data to classify whether a patient has heart disease based on various medical attributes.</p>

  <h2>Overview</h2>

  <p>The project consists of the following steps:</p>

  <ol>
    <li><strong>Importing Libraries</strong>: Essential Python libraries for data manipulation, visualization, and machine learning are imported.</li>
    <li><strong>Loading Data</strong>: Reads the dataset <code>heart.csv</code> containing patient data into a Pandas DataFrame.</li>
    <li><strong>Exploring Data</strong>: Displays initial rows, info, and summary statistics of the dataset to understand its structure and attributes.</li>
    <li><strong>Data Preprocessing</strong>: Preprocesses the data by separating features and the target variable.</li>
    <li><strong>Train-Test Split</strong>: Splits the dataset into training and testing sets to evaluate the model's performance.</li>
    <li><strong>Model Training</strong>: Uses logistic regression to train a model on the training data.</li>
    <li><strong>Model Evaluation</strong>: Evaluates the model's accuracy on both training and test datasets and generates an ROC curve.</li>
    <li><strong>Making Predictions</strong>: Predicts heart disease presence for a new patient based on input data.</li>
  </ol>

  <h2>Files</h2>

  <ul>
    <li><code>heart.csv</code>: Dataset containing patient information.</li>
    <li><code>heart_disease_prediction.ipynb</code>: Jupyter Notebook containing Python code for the project.</li>
    <li><code>README.md</code>: This file, providing an overview of the project.</li>
  </ul>

  <h2>Usage</h2>

  <p>To run the notebook <code>heart_disease_prediction.ipynb</code>, follow these steps:</p>

  <ol>
    <li>Clone the repository:</li>
  </ol>

  <pre><code>git clone https://github.com/your-username/heart-disease-prediction.git</code></pre>

  <ol start="2">
    <li>Navigate to the project directory:</li>
  </ol>

  <pre><code>cd heart-disease-prediction</code></pre>

  <ol start="3">
    <li>Open the Jupyter Notebook:</li>
  </ol>

  <pre><code>jupyter notebook heart_disease_prediction.ipynb</code></pre>

  <ol start="4">
    <li>Execute the cells in the notebook to explore, preprocess data, train the model, evaluate its performance, and make predictions.</li>
  </ol>

  <h2>Dependencies</h2>

  <p>Install required libraries using pip:</p>

  <pre><code>pip install numpy pandas matplotlib seaborn scikit-learn</code></pre>

  <h2>License</h2>

  <p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

  <h2>Acknowledgments</h2>

  <ul>
    <li>Data source: <a href="https://archive.ics.uci.edu/ml/datasets/Heart+Disease">UCI Machine Learning Repository - Heart Disease Data Set</a></li>
    <li>Inspiration: This project was inspired by the need to predict heart disease based on patient medical data.</li>
  </ul>

</body>
</html>
