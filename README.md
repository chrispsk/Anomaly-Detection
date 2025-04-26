In this project, I implemented and compared two machine learning models for classifying an imbalanced dataset (containing rare classes eg: Privilege Escalation only 59 logs). 
Approach:

    Data Preprocessing: The dataset was split into training and testing sets.

    Models:

        Random Forest Classifier: Used with default settings and class balancing.

        XGBoost: A boosting model applied to the data.

    Performance: Both models performed well, with XGBoost achieving 100% accuracy for most classes but with slightly lower recall for rare classes like "Privilege."

Results:

    Random Forest: Strong performance across most classes.

    XGBoost: Excellent accuracy and F1-scores for most classes, though recall for "Privilege" was lower.

Improvements:

    SMOTE could be applied for handling class imbalance, especially for rare classes.
    Hyperparameter tuning could improve model performance further.
    Adding more logs for privilege escalation.

    
