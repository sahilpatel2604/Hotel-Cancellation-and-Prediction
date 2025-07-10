# Hotel-Cancellation-and-Prediction

Hotel Booking Cancellation Prediction
This project aims to predict hotel booking cancellations, enabling hotels to take proactive actions that minimize revenue loss and improve customer retention.

📊 Dataset Overview
Contains ~119,000 records from City Hotel and Resort Hotel

Comprises 32 features, including:

Booking and arrival dates

Lead time

Deposit type

Customer demographics and booking preferences

Cancellation rate: ~37% of all bookings

🔍 Key Insights
Higher cancellation likelihood is associated with:

Long lead times

No deposit required

Transient customer types

Repeat guests show significantly lower cancellation rates, reflecting stronger loyalty and trust.

🧹 Data Preprocessing
Steps performed using pandas, numpy, and LabelEncoder:

Handled missing values

Removed outliers

Encoded categorical variables

Scaled numerical features for optimal model performance

🤖 Modeling Approach
Three classification models were trained and evaluated:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Performance metrics included:

Accuracy

Precision

Recall

Confusion Matrix

Classification Report

✅ Best Model: XGBoost
Accuracy: ~87%

ROC-AUC Score: 0.91

Demonstrated the best balance of performance and generalization

🏆 Feature Importance
Top predictors of cancellations:

Lead time

Deposit type

Number of previous cancellations

Booking changes

💡 Business Application
The final model enables hotel operators to:

Identify high-risk bookings early

Implement targeted strategies like flexible cancellation policies or loyalty incentives

Improve revenue forecasting and reduce operational uncertainty

📦 Tools & Libraries Used
Python

Pandas, NumPy – data manipulation

Matplotlib.pyplot – visualizations

LabelEncoder – encoding categorical variables

RandomForestClassifier, XGBoost – model training

accuracy_score, precision_score, recall_score, classification_report, confusion_matrix – model evaluation



This project focuses on predicting hotel booking cancellations to help hotels take proactive measures and reduce revenue loss.

The dataset contains ~119,000 records from both City Hotel and Resort Hotel, with 32 features like booking date, lead time, deposit type, and customer information.

Approximately 37% of all bookings were canceled, highlighting the importance of accurate cancellation prediction.

Long lead time, no deposit, and transient customer type are major indicators of higher cancellation probability.

Repeat guests are significantly less likely to cancel, indicating stronger loyalty and trust.

Preprocessing steps included handling missing values, removing outliers, encoding categorical variables, and scaling numeric data to prepare it for modeling.

Three classification models were built: Logistic Regression, Random Forest, and XGBoost.

XGBoost outperformed other models, achieving an accuracy of ~87% and a ROC-AUC score of 0.91, making it ideal for deployment.

The most influential features in predicting cancellations were lead time, deposit type, number of previous cancellations, and booking modifications.

The trained model can be used by hotel operators to identify high-risk bookings early and offer targeted incentives, such as discounts or flexible policies, to reduce cancellation rates.
