# Twitter Link Prediction Model 🐦🔗

Predicting missing links in a Twitter network using various machine learning algorithms.

## Overview

We developed a link prediction model to identify missing links within a Twitter network comprising 4.8 million nodes and 23 million edges. The model leverages Artificial Neural Networks (ANN), Logistic Regression (LR), and Random Forest (RF) algorithms for accurate predictions. Feature extraction is performed using both edge and node features.

## Key Features

- 🚀 Implemented predictive analysis to determine the authenticity of missing links.
- 📊 Validated model accuracy using a test set of 2000 links.
- 🎯 Utilized stratified sampling to generate a balanced training sample of 50,000 points, including randomly sampled negative points.
- 🧠 Explored various classification models, including Logistic Regression, Random Forest, Support Vector Machine (SVM), and ANN.
- 📈 Achieved a peak AUC score of 90.10% and introduced regularization to improve accuracy to 93.5%.

## Project Structure
```plaintext
.
├── 📔 notebooks
│ ├── link_prediction.ipynb # Jupyter notebook with the main project code
├── 📁 data
│ ├── twitter_network.csv # Dataset containing Twitter network information
├── 📂 output
│ ├── model_results.csv # CSV file with model evaluation results
├── 📄 README.md # Project documentation


