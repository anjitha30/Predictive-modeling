# Predictive-modeling
# Customer Booking Prediction

## Description
This project aims to predict whether a customer will complete a booking using machine learning. The dataset includes features such as `purchase_lead`, `total_services`, and `flight_duration`. A RandomForestClassifier was used to build the model.

## Key Features
- Data exploration and preprocessing.
- Feature engineering (e.g., `total_services` = `wants_extra_baggage` + `wants_preferred_seat` + `wants_in_flight_meals`).
- Model training and evaluation using RandomForestClassifier.
- Handling imbalanced data using class weighting.

## Results
- **Accuracy**: 85.66%
- **Precision**: 58.71%
- **Recall**: 10.47%
- **F1-Score**: 17.77%
- **Feature Importance**: `purchase_lead` (0.35), `total_services` (0.25), `flight_duration` (0.15).

