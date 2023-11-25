# Road-Traffic-Accidents

Overview
This project aims to analyze road traffic accidents using machine learning classification algorithms to identify major causes and predict accident severity based on various factors.

Dataset
The dataset used in this project contains records of road traffic accidents from 2017 to 2020. The original dataset was pre-processed and cleaned to exclude sensitive information. It consists of 32 features and 12,316 instances of accidents.

Data Columns
Age_band_of_driver
Sex_of_driver
Educational_level
Vehicle_driver_relation
Driving_experience
Lanes_or_Medians
Types_of_Junction
Road_surface_type
Light_conditions
Weather_conditions
Type_of_collision
Vehicle_movement
Pedestrian_movement
Cause_of_accident
Accident_severity
Models
Three machine learning models were employed for analysis:
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier
Evaluation Metrics
The models were evaluated using various metrics including accuracy, precision, recall, and F1-score.

Results
Decision Tree: Accuracy - 73.6%, Precision - 73%, Recall - 74%, F1-score - 73%
Random Forest: Accuracy - 83.6%, Precision - 75%, Recall - 84%, F1-score - 77%
Gradient Boosting: Accuracy - 83.6%, Precision - 75%, Recall - 84%, F1-score - 77%
Conclusion
Based on the evaluation metrics, both Random Forest and Gradient Boosting models outperformed the Decision Tree model. Further analysis might be required to select the best model based on specific requirements.
