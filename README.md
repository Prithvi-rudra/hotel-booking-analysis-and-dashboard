# Hotel Booking Cancellation Prediction

This project focuses on analyzing and predicting hotel booking cancellations using machine learning. The goal was to understand guest behavior and identify the primary factors that lead to booking cancellations.

## Project Workflow
The project follows an end-to-end data science pipeline:
* **Data Cleaning & Exploration:** Handled missing data and prepared raw information for analysis.
* **Feature Engineering:** Transformed categorical text data into numerical formats to ensure compatibility with machine learning models.
* **Predictive Modeling:** Built and evaluated multiple models, including Logistic Regression and Random Forest.
* **Feature Importance Analysis:** Interpreted the final model to identify the key drivers of booking cancellations.

## Results
After testing various models, the **Random Forest** classifier was selected as the final model.
* **Accuracy:** The model achieved an accuracy of **85%** on the test dataset.
* **Performance:** The model demonstrated strong performance in identifying guests likely to cancel compared to our baseline model.

## Key Findings
Through feature importance analysis, we identified that the following factors most heavily influence a guest's likelihood to cancel:
1. **Lead Time:** The number of days between booking and arrival is the strongest predictor of cancellation.
2. **Country:** A guest's country of origin plays a significant role in booking patterns.
3. **Average Daily Rate (ADR):** Higher price points correlate with an increased likelihood of cancellation.
4. **Special Requests:** Guests who make zero special requests are generally more likely to cancel their bookings.
