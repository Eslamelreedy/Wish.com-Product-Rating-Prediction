# Wish.com Product Rating Prediction

This repository contains the code and documentation for the Wish.com Product Rating Prediction competition on Kaggle. The goal of this competition is to predict the product ratings given other features known for a product on Wish.com. The dataset provided is a tabular dataset that requires preprocessing before modeling.

## Problem Formulation
- Input: Dataset containing features of products on Wish.com
- Output: Predicted product ratings (categories from 1 to 5)

The data mining function required for this problem is supervised learning, where we train a model on the provided training set to make predictions on the test set. The challenges include dealing with noisy data and performing effective preprocessing to extract relevant features.

The impact of this prediction task is to estimate the likelihood of people liking a product on Wish.com without actually listing it. It also helps in understanding the factors that contribute to highly rated products, enabling a better understanding of the customer base.

## Experimental Protocol and Preprocessing Steps
The experimental protocol used for model tuning and documentation follows the data science life cycle. The steps involved are as follows:

1. Exploratory Data Analysis (EDA): Analyze the dataset, identify missing values, outliers, and the distribution of the target variable.
2. Data Preprocessing: Perform data cleaning, handle missing values, and outliers if necessary. Convert categorical variables into numerical representations if required.
3. Feature Engineering: Create new features or derive meaningful features from the existing ones to enhance model performance.
4. Model Selection: Choose suitable models for the prediction task (e.g., decision tree, SVM, Naive Bayes).
5. Model Training and Evaluation: Train the selected models on the training set and evaluate their performance using appropriate evaluation metrics.
6. Hyperparameter Tuning: Experiment with different hyperparameter configurations for the models to optimize their performance.
7. Model Comparison and Selection: Compare the performance of different models and select the best-performing model for prediction.
8. Documentation: Document the entire process, including thoughts, observations, code, and results for each trial.

## Model Tuning and Documentation
The template provided in the repository is used as a guide to improve the model's performance on the public leaderboard. Several trials are conducted with different features, hyperparameters, and models. Each trial is documented with the reason for making specific changes, the expected outcome, the observed performance, and thoughts on the results.

The requirements for the model tuning process are as follows:
- At least 5 trials with different solutions (e.g., different feature sets, different preprocessing techniques).
- Decision tree model tried with at least 2 different configurations/hyperparameters.
- SVM model tried with at least 2 different configurations/hyperparameters.
- Naive Bayes model tried.

The emphasis is on the documentation of the thought process and observations made during each trial, as it helps in understanding the rationale behind the decisions and assists in troubleshooting.

## Answering the Questions

🌈 Why Data Mining is a misnomer? What is another preferred name?
Data Mining is considered a misnomer because it implies the extraction of new information from data, while in reality, it primarily involves the application of various algorithms to extract patterns, relationships, and insights from data. Another preferred name for Data Mining is Knowledge Discovery in Databases (KDD).

🌈 What is the general knowledge discovery process? What is the difference between a data engineer and data scientist/AI engineer?
The general knowledge discovery process involves several steps: data selection, data preprocessing, transformation, data mining, interpretation/evaluation, and knowledge presentation. It encompasses the entire process of extracting valuable knowledge from data.

The main difference between a data engineer and a data scientist/AI engineer lies in their roles and responsibilities. A data engineer primarily focuses on the design, construction, and maintenance

 of data pipelines, databases, and infrastructure required for data analysis. They ensure data availability, reliability, and efficiency. On the other hand, a data scientist/AI engineer focuses on analyzing data, developing models, and extracting insights to solve complex problems using techniques like machine learning and AI. They leverage their domain knowledge and analytical skills to derive meaningful insights from data.

🌈 In data mining, what is the difference between prediction and categorization?
In data mining, prediction and categorization are two different tasks:

- Prediction: In prediction, the goal is to estimate or predict a numerical value or a continuous variable based on the input features. For example, predicting the product rating on Wish.com falls under prediction. The output is a numerical value within a range.
- Categorization (or Classification): In categorization, the goal is to assign a category or label to the input based on predefined categories. For example, classifying emails as spam or not spam. The output is a discrete category or label.

🌈 Why data science/machine learning is a bad idea in the context of information security?
Data science and machine learning, when applied in the context of information security, can have drawbacks and challenges. Some reasons include:

- Adversarial Attacks: Malicious actors can manipulate data or exploit vulnerabilities in machine learning models to deceive or compromise the security system.
- Data Privacy: The use of sensitive data for training models may raise privacy concerns if not handled carefully. Privacy-preserving techniques must be considered.
- Model Interpretability: In security-critical domains, the interpretability of machine learning models is crucial. Complex models may be difficult to interpret, leading to trust and security issues.
- Generalization and Robustness: Machine learning models may struggle to generalize well and adapt to evolving security threats. Robustness to adversarial examples is also a concern.

🌈 What is CIA principle, and how can we use it to assess the security/privacy aspect of the AI system/pipelines?
CIA stands for Confidentiality, Integrity, and Availability. It is a fundamental principle in information security.

- Confidentiality: Ensuring that data and information are accessible only to authorized individuals or systems.
- Integrity: Maintaining the accuracy, consistency, and trustworthiness of data and preventing unauthorized modifications or tampering.
- Availability: Ensuring that data and systems are available and accessible when needed.

To assess the security and privacy aspect of AI systems/pipelines, we can apply the CIA principle as follows:

- Confidentiality: Implement measures like encryption, access controls, and secure communication protocols to protect sensitive data used in AI systems.
- Integrity: Apply techniques like data validation, anomaly detection, and cryptographic mechanisms to ensure the integrity of data and prevent unauthorized modifications.
- Availability: Design robust and redundant systems, backup data regularly, and employ measures to protect against service disruptions or denial-of-service attacks.

By considering the CIA principle, we can evaluate and enhance the security and privacy aspects of AI systems and pipelines.


