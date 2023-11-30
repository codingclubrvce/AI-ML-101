# Spam Message Detection Project 📩
## Overview 🧐
The primary goal of this project is to develop a model that can accurately classify messages as either spam or not spam. The project uses Scikit-learn's SVM classifier, TF-IDF vectorization, and GridSearchCV for hyperparameter tuning to detect spam messages. It employs pipelines for streamlined workflow, saves the trained model using Joblib or Pickle for future use, and demonstrates accuracy evaluation on a test set.
## Table of Contents📜:

[Packages](#Packages)

[Workflow](#Workflow)

[Advantages](#Advantages)

[Disadvantages](#Disadvantages)

[Dataset Description](#Dataset-Description)

[Usage](#Usage)

[Links](#Links)
## Packages 📦

Packages used in this project are listed [here](requirements.txt).

## Workflow 🔀
1. **Data Preparation:** Labeled message data is collected and split it into training and testing sets.
2. **Pipeline Construction:** TF-IDF Vectorizer for text-to-numerical conversion and an SVM classifier are used in the pipeline.
3. **Hyperparameter Tuning:** Hyperparameters for the SVM (kernels, C values, gamma, etc.) are defined. GridSearchCV is used within the pipeline to find the best hyperparameters.
4. **Model Training and Evaluation:** The training data is fed into the pipeline and fitted and optimized with the best hyperparameters. Model's performance is then evaluated using the test dataset (accuracy, precision, recall).
5. **Model Persistence:** The final optimized model (TF-IDF Vectorizer + SVM) is saved using Joblib or Pickle for future use.
## Advantages 🌟

- SVMs can handle complex, high-dimensional datasets efficiently. 
- SVMs aim to maximize the margin between classes, making them less prone to overfitting and often resulting in better generalization to unseen data.

## Disadvantages ⚠️
- SVMs can be less efficient with large datasets because of their computational complexity.
- SVMs are sensitive to noise in the dataset. Noisy data or overlapping classes can negatively impact their performance and generalization.

## Dataset Description 📂

The [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data) is a set of SMS tagged messages that have been collected for SMS Spam research. It consists of 5,574 english messages, tagged according to being ham (legitimate) or spam.

## Usage 🛠️

1. Clone the repository by running the following command:
   ```
   git clone https://github.com/codingclubrvce/AI-ML-101.git
   ```
2. Go to SpamMessageDetection folder by running the following command:
   ```
   cd AI-ML-101/Machine-Learning-Models/SpamMessageDetection
   ```
3. Install all the required packages by running the following command:
   ```
   pip install -r requirements.txt
   ```
4. Download the dataset from [here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset/data) and move it to the above folder.
5. Open spamdetection_using_scikitlearn.ipynb file and run all the cells.
6. Once the models are saved, you can use them in different files.
## Links 🔗
- [Support Vector Machines](https://scikit-learn.org/stable/modules/svm.html)

- [TF-IDf Vectorizer](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)

- [Hyper-parmeter tuning](https://scikit-learn.org/stable/modules/grid_search.html)

- [Pipelines](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)

## Contribution Guidelines 🤝
If you'd like to contribute to this project, please follow the guidelines outlined in [contribution.md](https://github.com/codingclubrvce/AI-ML-101/blob/a190d5d38896d8e883f5ef5a158521c1f3e394d4/contribution.md).

## Feedback and Support 📬
For any questions, feedback, or issues regarding the project, feel free to open an issue or reach out to the Coding Club, RVCE.

Happy Learning and Coding! 🚀