### Predicting the onset of diabetes in the next 5 years in Indigenous Pima women.

**Vivek Narra**

#### Executive Summary

Indigenous Pima women have a higher rate of incidence of diabetes and predicting this disease early on would help treat the disease effectively thereby preventing or delaying the complications of the disease. Different classifiers were used to select a model that would accurately predict the onset of diabetes in these women and the best one was selected. The selected algorithm can be used to predict the developing diabetes within 5 years with good confidence.

#

#### Rationale
Predicting the disease early would prevent complications of the disease and thereby affording a good quality of life for the patient. Healthcare costs in general would be lower with early prediction and care.

#### Research Question

To identify Pima Indigenous women who are at a high risk of developing diabetes mellitus within the next five years.

#### Data Source

Background Data: This dataset was taken from the National Institute of Diabetes and Digestive and Kidney Diseases and was downloaded from Kaggle datasets. Several constraints were placed on the selection of these instances. Patients in this data are all females aged 21 years and above and come from the Pima Indians heritage.

#### Methodology

A CRISP-DM framework was used to understand and prepare the data. This framework was used to assess multiple classifier models. The models that were assessed were K-Nearest Neighbor, Logistic Regression, Decision Tree Classifier and Support Vector Machine Classifier. Hyperparameters were fine-tuned for better accuracy with GridSearch CV.

#### Results

The model developed is a decision tree algorithm-based model that can be used to identify patients that will develop diabetes in the next 5 years. This model may identify patients that may not develop diabetes as potentially at risk for diabetes (false positives) and subject patients to unnecessary anxiety, tests and treatment. On the other hand, there is a certain number of patients that would not be diagnosed (false negatives) and this would delay the treatment which may not be an improvement from the current situation for these women.

As we collect more data with this model, there is a good chance that the model will improve. As the data continues increase, we would run the various classifiers again to pick the best model.


#### Outline of project

[The project and the code can be found here]( https://github.com/vnavanee/PROF-AIML-20)

##### Contact 

Please feel free to reach Vivek Navaneethan @ vivekbiz@gmail.com for any questions.
