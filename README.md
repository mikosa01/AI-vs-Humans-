# Human vs AI Article Classification

## Overview
This Jupyter Notebook project is designed to classify articles into two categories: "Human" and "AI." It utilizes machine learning techniques, specifically logistic regression, to classify text data based on its content. The classification model is trained on a dataset containing articles labeled as either 0('Human') or 1('AI').

## Usage
1. **Clone the repository**: Clone this repository to your local machine.
   
2. **Install dependencies**: Make sure you have Python installed on your system along with the required libraries. You can install the dependencies by running the following command in your terminal:

```pip install pandas nltk scikit-learn matplotlib```

You also need to download the NLTK data by running the following Python code once:

```python```

```import nltk```

```nltk.download('wordnet')```


Open the notebook: Open the Jupyter Notebook classification.ipynb in your Jupyter environment.

Follow the instructions: Execute each cell in the notebook sequentially to understand the data preprocessing, training, and evaluation steps. Make sure to read the comments provided in the code cells for guidance.

Notebook Structure
Data Loading and Preprocessing: This section includes code for reading and preprocessing the dataset, including text cleaning and feature extraction using TF-IDF.

Model Training: This section contains code for training a logistic regression classifier on the preprocessed data.

Model Evaluation: This section evaluates the trained classifier's performance using various metrics such as accuracy, F1 score, precision, and ROC curve.

Dataset
The dataset used for training and evaluation is stored in the data directory. It contains articles labeled as binary i.e. 0 or 1 in a CSV format.

Acknowledgments
This project makes use of the following Python libraries:

pandas
nltk
scikit-learn
matplotlib

License
This project is licensed under the MIT License - see the LICENSE file for details.









