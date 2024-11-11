<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1 align="center">Heart Disease Prediction using ANN</h1>



<p align="center">
  A machine learning project using Artificial Neural Networks (ANN) to predict heart disease risk based on patient data. Built and trained in Google Colab.
</p>

<hr>

<h2>🚀 Project Overview</h2>

<p>
Heart disease is one of the leading causes of death worldwide. This project aims to predict the likelihood of heart disease in a patient using a dataset containing various health attributes. With the help of an Artificial Neural Network (ANN), we can analyze patterns in the data and predict the risk, providing a useful tool for early diagnosis.
</p>

<hr>

<h2>📚 Dataset</h2>

<ul>
  <li><strong>Source</strong>: UCI Machine Learning Repository - Heart Disease Dataset</li>
  <li><strong>Features</strong>: 13 attributes including age, gender, chest pain type, blood pressure, cholesterol level, and more</li>
  <li><strong>Target</strong>: Binary classification - 0 (No Heart Disease), 1 (Heart Disease)</li>
</ul>

<hr>

<h2>💻 Tech Stack</h2>

<ul>
  <li><strong>Python</strong>: Programming language</li>
  <li><strong>TensorFlow/Keras</strong>: ANN model implementation</li>
  <li><strong>Pandas & Numpy</strong>: Data manipulation and preprocessing</li>
  <li><strong>Google Colab</strong>: Platform for development and model training</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<ul>
  <li><strong>Heart_Disease_Prediction.ipynb</strong>: Main notebook containing data analysis, model building, and training steps</li>
  <li><strong>README.md</strong>: Project documentation</li>
  <li><strong>Data</strong>: Heart disease dataset (CSV format)</li>
</ul>

<hr>

<h2>🔧 Setup Instructions</h2>

<ol>
  <li><strong>Clone the repository</strong>:
    <pre><code>git clone https://github.com/your-username/heart-disease-prediction.git</code></pre>
  </li>
  <li><strong>Upload the dataset to Google Colab</strong>:
    <ul>
      <li>Open <code>Heart_Disease_Prediction.ipynb</code> in Google Colab.</li>
      <li>Upload the heart disease dataset to your Colab environment.</li>
    </ul>
  </li>
  <li><strong>Install required packages</strong> (if not already available):
    <pre><code>!pip install tensorflow pandas numpy</code></pre>
  </li>
  <li><strong>Run the notebook</strong>:
    <ul>
      <li>Follow the cells in <code>Heart_Disease_Prediction.ipynb</code> to load data, preprocess, train, and evaluate the model.</li>
    </ul>
  </li>
</ol>

<hr>

<h2>📊 Model Architecture</h2>

<p>Our ANN model consists of:</p>

<ul>
  <li><strong>Input Layer</strong>: 13 nodes (one for each feature)</li>
  <li><strong>Hidden Layers</strong>: Two dense layers with ReLU activation</li>
  <li><strong>Output Layer</strong>: A single node with sigmoid activation for binary classification</li>
</ul>

<hr>

<h2>📈 Results and Evaluation</h2>

<ul>
  <li><strong>Accuracy</strong>: Achieved around 85% accuracy on the test dataset</li>
  <li><strong>Precision, Recall, F1-Score</strong>: Evaluated to understand the model's performance in predicting positive and negative classes</li>
</ul>

<hr>

<h2>🤖 Key Steps</h2>

<ol>
  <li><strong>Data Preprocessing</strong>: Handling missing values, scaling features</li>
  <li><strong>Building the ANN Model</strong>: Using Keras Sequential API</li>
  <li><strong>Model Training</strong>: Using binary cross-entropy as the loss function and Adam optimizer</li>
  <li><strong>Evaluation</strong>: Checking accuracy, confusion matrix, and classification report</li>
</ol>

<hr>

<h2>📬 Contact</h2>

<p>For questions or feedback, feel free to reach out!</p>

<ul>
  <li><strong>GitHub</strong>: <a href="https://github.com/sonamkavi">sonamkavi</a></li>
  <li><strong>Email</strong>: sk93040bharti@gmail.com</li>
</ul>

<p align="center">
  <strong>Let's fight heart disease with the power of AI! ❤️</strong>
</p>

</body>
</html>
