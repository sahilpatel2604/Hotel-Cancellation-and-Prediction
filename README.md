# Hotel-Cancellation-and-Prediction
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
