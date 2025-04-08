# neural-network-challenge-2
# Description
This program makes a branching neural network model based on retention data from a fictional company.  The HR department wanted to know if whether if an employee leaves can be predicted as well as whether employees were in the correct department.  The data was prepared using ordinal and OneHot encoders depending on the data type.  Numeric columns were prepared with standardscaler.  Accuracy, confusion matrix, and classification report were used to access the performance of the model. The attrition accuracy was 0.9 and the department accuracy was 0.97.  The attrition accuracy may be affected by imbalanced data and some suggestions are made to accommodate this.
# Data source
-https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv'
# Dependencies
- pandas
- tensorflow
- tensorflow.keras.layers
- tensorflow.keras.models
- sklearn.model.selection
- standardscaler
- sklearn.metrics
- numpy
#Python version
- 3.12.7
