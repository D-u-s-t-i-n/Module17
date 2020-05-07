# Module17

Lastly, you’ll write a brief summary and analysis of the models’ performance. Describe the precision and recall scores, as well as the balanced accuracy score. Additionally, include a final recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

# Model Performance
## Oversampling
### Random Oversampling
Precision scores are 0.01 and 1
Recall scores are 0.71 and 0.61
Balanced Accuracy score is 0.660429

### SMOTE Oversampling
Precision scores are 0.01 and 1
Recall scores are 0.64 and 0.69
Balanced Accuracy score is 0.665649

## Undersampling
Precision scores are 0.01 and 1
Recall scores are 0.66 and 0.40
Balanced Accuracy score is 0.529853

## Combination (SMOTEENN)
Precision scores are 0.01 and 1
Recall scores are 0.73 and 0.57
Balanced Accuracy score is 0.650188

# Recommendation
I would not recommend the models for deployment because at most it is 70% accurate. But if the risks are allowable and selecting a model is required, the SMOTE oversampling seems to be the best to get the most conservative approach that detects the most bad loans.
