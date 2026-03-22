# Assignment

This project analyses a Portuguese bank marketing dataset to predict whether a client will subscribe to a term deposit.

The workflow begins with data loading and preprocessing, including handling “unknown” values, encoding categorical variables, feature scaling, and addressing class imbalance using SMOTE.

An Exploratory Data Analysis (EDA) is conducted to understand data distributions, detect outliers, and identify key relationships between features and the target variable. Insights highlight the importance of variables such as call duration, previous contact history, and macroeconomic indicators.

Two supervised machine learning models are then developed and compared:

Logistic Regression (with threshold optimisation using ROC analysis)
Decision Tree (with hyperparameter tuning via GridSearchCV)

Both models are evaluated using metrics such as precision, recall, F1-score, and confusion matrices, with particular focus on handling the imbalanced target.

The project concludes with a performance comparison, showing trade-offs between recall (capturing more potential subscribers) and precision (reducing false positives), providing insights into model suitability for marketing decision-making.
