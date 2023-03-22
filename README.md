# Water potability 🚰

### Objective 🎯
“Potable water” simply means water that is safe to drink. The main goal is to predict if each water sample is potable or not potable.

### Description Of Dataset 📊 
The dataset considered for this project is taken from Kaggle dataset (https://www.kaggle.com/adityakadiwal/water-potability)

The dataset consists of 3276 records with 10 column of which 9 are input variables and 'potability' is the output variable. For all of the chemical and physicochemical variables the World Health Organization (WHO) organization has preapred water quality standards. In the project I'll also check if the quality standards are fulfilled. 

### Methodology ⚙️
10 classifiers were sorted out based on their accuracy and roc_auc_score on the testing data. After that, 3 of them (SVM, Random Forest Classifier, GradientBoosting Classifier) were tuned with Grid Search CV to find optimal hyper-parameters, but but it did't help to improve the results. The best results gives SVM: 63,9% (roc auc score) and 72% accuracy on test data. Appropriate graphs and metrics were generated for the analysis and performance of the different models were compared.
