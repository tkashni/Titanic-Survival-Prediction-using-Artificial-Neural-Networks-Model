# Titanic Survival Prediction using Artificial Neural Networks (ANN) | Deep Learning with Python
A deep learning project using Artificial Neural Networks (ANN) to predict passenger survival on the Titanic. Complete implementation with data preprocessing, EDA, and neural network training.
## Dataset Links:


🔹 README.md (GitHub – Proper & Professional)
📌 Project Overview
The Titanic disaster is a classic machine learning problem where the goal is to predict whether a passenger survived based on demographic and travel-related features.
In this project, an Artificial Neural Network (ANN) is built to learn complex non-linear patterns and improve prediction performance.

📂 Dataset

Data set (Test):
https://drive.google.com/file/d/1uQYd6aptuh6qYqKMMCXr1FZALFo53eZj/view?usp=share_link

Data set(Train):
https://drive.google.com/file/d/1iEuqOToDAOSnqs_FOKiExScUkA0h3k-l/view?usp=share_link

Features include:

Passenger class

Sex

Age

Fare

Embarked port

Family relations (SibSp, Parch)

🧭 Approach Followed
Reading the Data

Loaded datasets using Pandas

Verified shape, data types, and missing values

Understanding the Data

Analyzed feature distributions

Identified categorical and numerical variables

Exploratory Data Analysis (EDA)

Survival analysis based on gender, class, and age

Correlation analysis between features and survival

Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling using standardization

Splitting the Data

Train–test split to evaluate model performance

Modeling (ANN)

Input layer with selected features

Hidden layers with ReLU activation

Output layer with Sigmoid activation

Binary Cross-Entropy loss function

Training and Testing

Optimizer: Adam

Batch training with validation

Model Evaluation

Accuracy score

Loss and performance monitoring

📊 Model Performance
✅ Model Accuracy: ~85% on validation data

(Accuracy may vary slightly depending on hyperparameters and random state)

🧠 Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

TensorFlow / Keras

🚀 Key Learnings
Practical implementation of Artificial Neural Networks

Importance of data preprocessing in deep learning

Feature impact on classification performance

ANN vs traditional ML models for binary classification

📎 Future Enhancements
Hyperparameter tuning

Comparison with Logistic Regression, Random Forest

Cross-validation

Model explainability (SHAP)
