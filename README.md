# Data-Analysis and Machine Learning - Titanic 
Project Overview:

This project explores the famous Titanic dataset, analyzing survival patterns and building Machine Learning models to predict passenger survival. It includes:

Exploratory Data Analysis (EDA): Understanding survival factors.

Preprocessing & Feature Engineering: Handling missing values, encoding categorical variables, and scaling features.

ML Models: 

  Logistic Regression, 
  Decision Tree, and 
  Random Forest.

Performance Evaluation: 

    Accuracy, 
    Precision, 
    Recall, 
    F1-score

Dataset

    The dataset contains details about passengers aboard the Titanic, including:
    
    Passenger Features: Age, Gender, Ticket Class, Fare, Number of Siblings/Spouses, etc.
  
    Target Variable: Survived (1 = Survived, 0 = Did Not Survive)

Source: The dataset is available from Kaggle - Titanic Dataset.

# Exploratory Data Analysis (EDA)

Key Insights:

    ---> Survival Rate: Only 38% survived, while 62% perished.
    
    ---> Gender Influence: Women had a much higher survival rate than men (233 females vs. 109 males survived).
    
    ---> Fare Distribution: Highly right-skewed (a few high-paying passengers).

    ---> Age & Survival: No strong correlation, as passengers of all ages had varying survival rates.

    ---> Class Influence: 1st-class passengers had higher survival rates than 3rd-class passengers.


Visualizations:
  
    Scatter Plots to explore relationships between age, Survival
    
    Scatter Plots to explore relationships between age, fare, and survival
    
    Histogram for fare distribution (skewed towards lower fares)
    
    Heatmap for correlation between survival and other features
    
    Bar Charts for survival distribution by gender & class.

# Data Preprocessing & Feature Engineering

  1. Handling Missing Values:

    Age filled with mean (as it follows a near-normal distribution).
    
    Embarked filled with mode.
    
    Cabin dropped due to >80% missing values.

  2. Feature Encoding:

    Sex converted to 0 (Male) / 1 (Female).
    
    Embarked one-hot encoded (S, C, Q).

  3. Feature Scaling:

    Used StandardScaler() to normalize numerical features.

# Machine Learning Models

 1. Logistic Regression

        Used class_weight='balanced' to handle class imbalance.

 2. Decision Tree Classifier

 3. Random Forest Classifier (Best Performing Model)

        Tuned Hyperparameters:

        n_estimators=100, max_depth=10, min_samples_split=5, random_state=42

# Model Performance Comparison

Model                          Accuracy

Logistic Regression            ~83%

Decision Tree classifier       ~80%

Random Forest classifer        ~84%

# Future Improvements

    Try SVM and XGBoost for better performance.

    Hyperparameter tuning with GridSearchCV.

    Try Neural Networks (ANN) for improved predictions.



    



