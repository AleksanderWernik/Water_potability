# Water potability 🚰

### Objective 🎯
“Potable water” simply means water that is safe to drink. The main goal is to predict if each water sample is potable or not potable.

### Description Of Dataset 📊 
The dataset considered for this project is taken from Kaggle dataset (https://www.kaggle.com/adityakadiwal/water-potability)

The dataset consists of 3276 records with 10 column of which 9 are input variables and 'potability' is the output variable. For all of the chemical and physicochemical variables the World Health Organization (WHO) organization has preapred water quality standards. In the project I'll also check if the quality standards are fulfilled. 

### Methodology ⚙️
I trained LinearRegression, KNeighbors Classifier, XGBoost Classifier, Decision Tree Classifier, Ridge Classifier, Random Forest Classifier, GaussianNB, GradientBoosting Classifier and AdaBoost Classifier from the Sklearn library, on the training set. Grid Search CV was used to find optimal hyper-parameters for the best models. Appropriate graphs and metrics were generated for the analysis and performance of the different models were compared.
