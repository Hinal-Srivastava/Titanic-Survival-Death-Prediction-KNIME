# Titanic-Survival-Death-Prediction-KNIME

It is observed that men, especially the older ones, had a lower chance of survival than women. This highlights the societal bias at the time. Adults in the age bandwidth of 28-40 also had a lower chance of survival. It is also observed that passengers who had a higher fare had a higher chance of survival. The port of embarkment also happens to have a correlation with survival rate however this could be because of the fact that most passengers embarked from Southampton. The decision tree performed slightly better than the random forest with an accuracy score of 87.87% and an error rate of 12.13%. The confusion matrix also supported this finding by giving higher values for recall, sensitivity, precision, specificity and F-measure. However, since the accuracies of both models were similar the ROC curves look identical. The model can be improved by performing hyperparameter tuning and introducing more features. Introducing variance filtering to remove features that surpass a threshold variance would also be beneficial. 

## Workflows

### EDA
![eda](https://github.com/Hinal-Srivastava/Titanic-Survival-Death-Prediction-KNIME/assets/28009493/00ad207b-b835-4e88-bdc8-893c8f4cac2f)

### Modeling Decision Tree
![Modeling_decisionTrees](https://github.com/Hinal-Srivastava/Titanic-Survival-Death-Prediction-KNIME/assets/28009493/9875d470-b395-4260-b695-0b06334a27fc)

### Cross-validation Decision Tree
![crossValidation_DT](https://github.com/Hinal-Srivastava/Titanic-Survival-Death-Prediction-KNIME/assets/28009493/69b87f7f-6792-4b8b-8c9b-f2ff32e14348)

### Modeling Random Forest
![Modeling_randomForest](https://github.com/Hinal-Srivastava/Titanic-Survival-Death-Prediction-KNIME/assets/28009493/cf4bcf28-3331-4724-a47a-04cf69ac7f0a)

### Cross-validation Random Forest
![crossValidation_RF](https://github.com/Hinal-Srivastava/Titanic-Survival-Death-Prediction-KNIME/assets/28009493/8c009231-7bd1-4777-97a7-281e8ddcf712)
