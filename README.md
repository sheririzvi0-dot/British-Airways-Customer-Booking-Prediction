# British-airways-customer-booking-prediction
Machine Learning project predicting customer booking behavior using Python and Random Forest.

✈️ Project Overview
This project is part of the British Airways Data Science Job Simulation (Forage).
The goal is to build a machine learning model that predicts whether a customer will complete a flight booking based on their behavior and travel preferences.
Using historical booking data, we analyze customer patterns and train a Random Forest Classifier to identify key factors influencing booking decisions.

🎯 Objective
Predict customer booking completion (Yes/No)
Understand key factors influencing bookings
Build an interpretable machine learning model
Evaluate model performance using cross-validation

📊 Dataset Features
The dataset includes:
👥 Number of passengers
💳 Sales channel
✈️ Trip type
⏳ Purchase lead time
🏨 Length of stay
🕒 Flight hour & day
🌍 Route & origin
🎒 Extra baggage preference
💺 Seat selection
🍽️ In-flight meal preference
⌛ Flight duration

Target Variable:
booking_complete (0 = No, 1 = Yes)

🧠 Machine Learning Workflow
✔ Data Exploration (EDA)
✔ Data Cleaning & Preprocessing
✔ Feature Encoding (One-Hot Encoding)
✔ Train-Test Split
✔ Model Training (Random Forest)
✔ Model Evaluation
✔ Cross-Validation
✔ Feature Importance Analysis

🤖 Model Used
Random Forest Classifier
Handles categorical + numerical data well
Provides feature importance
Robust and interpretable

📈 Model Performance
Accuracy: ~85% (example — replace with your actual score)
Cross-validation used for stability check
Feature importance used for interpretability

🔑 Key Insights
Purchase lead time strongly impacts booking behavior
Flight duration is a major predictor
Ancillary services (seat, baggage, meals) influence conversion
Customer engagement increases booking probability

💡 Business Impact
This model helps airlines:
Predict customer booking likelihood
Optimize marketing strategies
Improve conversion rates
Identify high-value customers early

🏁 Conclusion
The Random Forest model successfully predicts customer booking behavior and highlights key drivers influencing customer decisions. This provides actionable insights for improving airline marketing and customer 
