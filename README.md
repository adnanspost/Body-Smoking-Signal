# Body-Signal-Smoking

## Introduction: This project involves solving a binary classification machine learning problem in Healthcare.

## Aim: The aim of this project is to make accurate predictions from historical data in regards to whether the person will be smoker or not.

## Methodology: 

While the fine details of the methodology followed in this project will be elaborated further in the relevant sections to come, it is to be mentioned that 16 standard machine learning models and 10 machine learning optimization have been implemented, compared, and contrasted to identify the best performing one.

### 01. Import CPU Python Libraries 
### 02. Function Helper
### 03. Import Dataset & Data Description
        - Import CSV File
        - Data Description
### 04. Data Understanding
        - Data Information
        - Data Summary Statistic
        - Data Variance
### 05. Select the Featurs
### 06. Data Pre-Processing
        - Drop Variables 
        - Convert Data Type
        - Missing Value
### 07. Exploratory Data Analysis
        - DV Visualization
        - Categorical IDV
        - Categorical IDV With DV
        - Numerical IDV
        - Numerical IDV With DV
### 08. Data Transformation
        - Standerd Scale
### 9. Feature Selection
        - Wrapper - Forward
### 10. Feature Engineering 
        - LableEncoder
### 11. Statistics
        - Correlations IDV with DV
        - Correlation between all the Variables
### 12. Resampling Data
        - SMOTE
### 13. Data Splitting 
### 14. Standard Machine Learning Models 
        - Build the Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        K Neighbors Classifier
        -        Naive Bayes Classifiers
        -        Naive Bayes Classifier for Multivariate Bernoulli
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Logistic Regression CV Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        XGBoost Classifiers
        -        Support Vector Machines Classifiers
        -        Linear Support Vector Classification
        -        Multilayer Perceptron Classifier
        - Predication X_test
        - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix
### 15. Optmization Machine Learning Models 
        - random grid for CPU Machine Learning Models
        - Hyperparameters for CPU Machine Learning Models
        - Build the Models 'Train the Models'
        -        Random Forest Classifier
        -        Gradient Boosting Classifier
        -        Histogram-based Gradient Boosting Classification Tree
        -        AdaBoost Classifier
        -        Extra Trees Classifier
        -        Decision Tree Classifier
        -        Logistic Regression Classifier
        -        Stochastic Gradient Descent Classifier
        -        Linear Perceptron Classifier
        -        Support Vector Machines Classifiers
        - Predication X_test
        - Models Evaluation
        -       Accuracy Score
        -       Classification Report
        -       Confusion Matrix
        
### 16. Accuracy Score Summary 

## Results

![175338165-39ac6bbd-ac50-4df2-9902-06ff23a03b63](https://user-images.githubusercontent.com/108016592/175768062-972a34ef-d172-44f4-a000-7d050b35a204.png)

![175338185-af20abc2-2c3a-4d4e-8082-58e5d6222d4a](https://user-images.githubusercontent.com/108016592/175768118-2f7ad43b-a22c-44e9-86fe-30a087f1165c.png)

The results for the Standered Machine Learning it is showing Random Forest Classifier, Extra Trees Classifier, XGBoost Classifiers with accuracy (87.2, 87.2, and 82.3) respectively.

![175341064-31cf6b4e-f121-4b5d-a140-c7d7eb181086](https://user-images.githubusercontent.com/108016592/175768151-792d9ba0-9f09-4993-8bcd-b148b82d723c.png)

![175341089-d9d10125-9a33-401c-9075-bfe2de87a678](https://user-images.githubusercontent.com/108016592/175768184-7ef62a7d-c0c0-49e1-9482-4f8b14b2863d.png)

The results for the Optimization Machine Learning it is showing Gradient Boosting Classifier, Random Forest Classifier, Histogram-based Gradient Boosting Classification Tree with accuracy (83.8, 83.2, and 81.7) respectively.

## Discussion:

![175341274-81b6e705-53b3-4777-81a0-099764ee63a9](https://user-images.githubusercontent.com/108016592/175768295-12a9432f-436a-47a2-8b36-af3179887570.png)

The table above depicts the Accuracy of the Standard CPU Models vs Accuracy of the Optimized CPU Models. As it can be seen above, the performance of some of the models have in fact reduced even after going through the process of optimization. This is because the hyperparameters have been experimented with only 150 interations. This iteration number is chosen at random, instead of the default number of optimization. Although performance or accuracy of the models could have been further improved than the original accuracies of the models, the computation power and time required to carry out the entire learning process is more than ideal. Since the highest accuracy achieved is 83.8%, this has been deemed sufficient for the purpose of this project and not further experimentation have been performed in attempts to achieve high accuracy
