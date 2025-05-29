🍄 Poisonous Mushroom Prediction
This project is a binary classification model designed to predict whether a mushroom is edible or poisonous, based on various physical characteristics. The model was developed as part of a Kaggle competition and uses machine learning techniques to help automate this classification task.

🚀 Objective
The goal is to accurately classify mushrooms into one of two categories:

Edible

Poisonous

This can have practical applications in agriculture, biology, and even consumer safety.

📊 Dataset
The dataset used in this notebook comes from a Kaggle competition and includes a variety of categorical features describing mushroom attributes such as:

Cap shape, color, and surface

Gill spacing and size

Odor

Habitat

Stalk features

🔍 Note: All features are categorical, requiring preprocessing before feeding into a machine learning model.

🛠️ Tools & Libraries Used
Python

Pandas & NumPy (Data manipulation)

Scikit-learn (Modeling and evaluation)

Seaborn & Matplotlib (Exploratory Data Analysis & Visualization)

🧠 Model Workflow
Data Cleaning
Checked for missing values and duplicate entries.

Exploratory Data Analysis (EDA)

Visualized distributions and feature correlations

Identified key predictors such as odor and spore print color

Preprocessing

Categorical encoding using LabelEncoder or OneHotEncoder

Splitting into training and test sets

Model Training

Trained multiple classifiers (e.g., Decision Tree, Random Forest, Logistic Regression)

Evaluated using accuracy, precision, recall, and F1-score

Model Selection & Evaluation

Selected the best-performing model

Tuned hyperparameters for optimal performance

✅ Results
Achieved an accuracy of over 99% with models like Random Forest and Gradient Boosting

Identified odor as the most significant feature for predicting mushroom toxicity

📦 How to Run
Clone this repository

Open the Jupyter Notebook or run in a Kaggle environment

Run cells step by step to see data processing and model training in action
