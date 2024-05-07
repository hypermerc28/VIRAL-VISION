# VIRAL-VISION
A song trend prediction to Predict if the song is going to be a hit or popular can be used in the music industry to help maximize the return on investment. 

## Overview
This project leverages classification models to accurately predict categorical outcomes designated as "Hit" and "Work in Progress". The goal is to fine-tune these models to achieve higher predictive accuracy and efficiency, thereby enabling better decision-making processes based on the model outputs.

## Model Implementation

### Tools and Techniques
We utilize various classification techniques, analyzing their performance with the following metrics:
- **Confusion Matrix**: A visualization tool for the accuracy of the prediction model.
- **ROC Curve (Receiver Operating Characteristics)**: Depicts the diagnostic ability of the classifier, showing its effectiveness in distinguishing between the categories.
- **DecisionTrees**
- 

## Key Results

### Insights from the Confusion Matrix
- **Hits Correctly Predicted**: 218 instances
- **Hits Misclassified as Work in Progress**: 37 instances
- **Work in Progress Correctly Predicted**: 97 instances
- **Work in Progress Misclassified as Hits**: 85 instances

### Insights from the ROC Curve
- **AUC (Area Under Curve)**: 0.76, indicating a robust ability to differentiate between the categories.

## Conclusion and Future Work

The models demonstrate a competent level of discrimination between categories with a promising AUC of 0.76. However, the relatively high number of misclassifications, particularly for 'Work in Progress', suggests that further model refinement is necessary.

### Recommendations for Improvement
- **Model Optimization**: Enhance accuracy through hyperparameter optimization and exploring alternative modeling techniques.
- **Feature Evaluation**: Conduct a thorough review of the predictive features to ensure relevance and impact on the model’s performance.
- **Data Enrichment**: Consider expanding the dataset to improve model training and validation processes.

