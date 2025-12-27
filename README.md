# Customer_Satisfaction_Prediction

🧾 Abstract

This project implements a customer satisfaction prediction system using supervised machine learning techniques. The complete analysis was performed in a Jupyter Notebook using Python 🐍. The workflow includes dataset loading, data inspection, exploratory data analysis (EDA), preprocessing, model implementation, and evaluation. Logistic Regression, Decision Tree, and Random Forest classifiers were trained and compared using standard classification metrics.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📘 1. Introduction

Customer satisfaction analysis helps organizations evaluate service quality and customer experience 😊. Using historical customer support data, machine learning models can be applied to predict satisfaction levels. This project demonstrates a practical application of data science techniques to classify customer satisfaction outcomes.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📂 2. Dataset Loading and Understanding

The dataset was loaded from a CSV file named customer_support_tickets.csv using the Pandas library 📊.
Initial inspection included:

👀 Viewing first and last rows of the dataset
📐 Checking dataset dimensions
🧬 Examining column names and data types using info()

This step helped in understanding the structure of the dataset and identifying categorical and numerical features.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
📊 3. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to study the distribution and relationships among variables 🔍. The following steps were carried out:

📈 Descriptive statistics using describe()
📊 Distribution and count plots
🏷 Visualization of categorical feature distributions
🔗 Correlation analysis for numerical features

Matplotlib and Seaborn were used for data visualization 🎨.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
⚙️ 4. Data Preprocessing

To prepare the dataset for model training, the following preprocessing steps were applied:

🧹 Handling missing values
🔡 Encoding categorical variables using Label Encoding
🎯 Separating features and target variable
🔀 Splitting data into training and testing sets using train_test_split
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
🤖 5. Model Implementation

The following supervised machine learning models were implemented using Scikit-learn:

📉 Logistic Regression
🌳 Decision Tree Classifier
🌲 Random Forest Classifier

Each model was trained using the training dataset and tested on unseen data.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
📏 6. Model Evaluation

Model performance was evaluated using:

✅ Accuracy score
🎯 Precision
🔁 Recall
🧮 F1-score
📄 Classification report

The evaluation results were compared across all models.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
🏆 7. Results and Analysis

The Random Forest Classifier achieved the best overall performance among the implemented models 🥇. The results indicate that ensemble learning methods perform better for customer satisfaction prediction compared to individual classifiers.
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
🧠 8. Conclusion

This project demonstrates an end-to-end machine learning workflow for predicting customer satisfaction using Python 🐍. All steps from data loading to model evaluation were implemented in a Jupyter Notebook. The project reflects practical understanding of data analysis, preprocessing, and classification modeling.

📁 Project Structure
Customer_Satisfaction_Prediction/
│
├── Customer_Satisfaction_Prediction.ipynb
├── customer_support_tickets.csv
├── README.md
└── .gitignore
_____________________________________________________________________________________________________________________________________________________________________________________________________________________
🛠 Tools and Technologies Used

🐍 Python
📊 Pandas, NumPy
📈 Matplotlib, Seaborn
🤖 Scikit-learn
📓 Jupyter Notebook
🔗 Git and GitHub
