# Module17 Challenge (Model Performance)
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
  
# Notes  
I noticed that the starter code has the solver='warning' whereas my environment only sets it to 'lbfgs' by default. Some of my values do not match with that of the starter code output. I assume this may be due to a version mismatch.   
  
# Recommendation  
The low risk precision scores are all 1, but the high risk scores are all 0.01. Conservatively, I would not recommend the models for deployment because at most it is 72% accurate. But if the risks are allowable and selecting a model is required, the SMOTE oversampling seems to be the best to get the most conservative approach that detects the most bad loans. This depends on how much risk the bank is willing to cover.
