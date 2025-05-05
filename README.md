# Data-Science-Internship-Task
Company Name : Codtech IT Solution Pvt.Ltd
Name : Pritam Balkrishna Meshram
Intern ID : CT04WT68
DOMAIN : DATA SCIENCE
Duration : 4 Weeks
Mentor : Neela Santhosh
## Description:
In this task, the objective was to perform comprehensive data preprocessing using the well-known Titanic dataset. This dataset contains various passenger details such as age, gender, ticket class, survival status, and more. Preprocessing is a critical step in any data science or machine learning workflow, as raw data often contains inconsistencies, missing values, and non-numeric features that must be addressed before model building.

The task began with importing the dataset using Pandas, a powerful Python library used for data analysis and manipulation. We explored the structure of the dataset using functions like .head(), .info(), and .describe() to understand the types of features and identify issues such as null values and inconsistent data types.

The next step was handling missing values. Missing data can introduce bias and reduce model accuracy if not treated properly. We used appropriate strategies such as filling missing age values with the median of the column and filling categorical missing data like "Embarked" with the most frequent value (mode). We also removed any duplicate records to ensure the data was clean and reliable.

Once the dataset was cleaned, we moved on to encoding categorical variables. Since machine learning models work with numerical data, categorical columns like “Sex” and “Embarked” were transformed using Label Encoding or One-Hot Encoding, depending on the nature of the variable. This step helps convert text-based values into numerical format while preserving the categorical relationship.

After encoding, the next step was to scale the numerical features using StandardScaler from the sklearn.preprocessing module. Scaling ensures that features like age and fare are on a similar range, which helps certain algorithms (like KNN, SVM, or logistic regression) perform better by not being biased toward higher-value features.

Finally, we saved the cleaned and preprocessed dataset to a new CSV file using Pandas. This file can now be used for further analysis, visualization, or building machine learning models in the next stages of the project.

🔧 Tools & Libraries Used:
Python

Jupyter Notebook / Google Colab

Libraries:

pandas for data manipulation

numpy for numerical operations

sklearn.preprocessing for encoding and scaling

This task helped build a strong foundation in real-world data preparation and reinforced the importance of preprocessing for accurate and meaningful machine learning insights.
