# HealthSync: Personalized Wellness & Diet Advisor

**Author**: Ruthik Raj Nataraja

HealthSync is a data-driven application designed to predict a user's health score based on their lifestyle and health data. It leverages machine learning models like Random Forest and XGBoost to process various health factors such as calorie intake, water consumption, sleep hours, and body metrics. The system then generates a tailored dietary plan that can be customized based on personal preferences. The goal is to provide users with personalized health insights and dietary recommendations that help improve their overall wellness.

## Features

- **Health Score Prediction**: 
  - The system uses inputs such as age, body fat, calorie intake, and activity level to predict a health score that reflects the user's overall health. This score can be used to track progress over time or to tailor health interventions.
  
- **Dietary Plan Recommendations**: 
  - The system generates personalized meal plans based on the user's dietary preferences, such as vegan, vegetarian, non-veg, or omnivorous. It takes into account preferences, allergies, and health requirements to suggest the best meal options for each user.

- **Customizable Plans**: 
  - Users can request modifications to their dietary plans, allowing the system to tailor the recommendations based on their taste, lifestyle, and dietary restrictions. This flexibility ensures that the system can be used by a wide range of individuals, from those with specific food preferences to those seeking general wellness.

- **User Input Handling**: 
  - The system collects key health data from the user, including daily calorie intake, water intake, sleep hours, weight, height, and current weather conditions. These inputs are critical in forming a comprehensive health profile and are used by machine learning models to provide accurate predictions and recommendations.

- **Machine Learning Models**: 
  - The backend utilizes two powerful machine learning models—**Random Forest Regressor** and **XGBoost Regressor**—to predict the user's health score based on the collected data. These models have been trained on synthetic health datasets to ensure they generalize well to a variety of user profiles.
