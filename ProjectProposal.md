# Project proposal for WATER POTABILITY
Author: Osman Yaseen

## 1. Why: Question/Topic being investigated 1pt

The Question/Topic that will be investigated is which factors are most significant when determining if water is potable (drinkable) or not. As access to clean to drinking water remains a problem for many communities around the world, I hope to quantify which factors have the highest impact on overall water potability and which factors have the least impact on overall water potablity. This may help in determining which potability tests to prioritize in resource-limited environments. It may also help determine if a specific factor or multiple factors are a reasonable indicator of water potablity versus each and every factor. 

## 2. How: Plan of attack 1pt
In the provided dataset, water potability is classified as either potable or not followed by 9 factors which may or may not determine a given water samples potability. This project is therefore a classification task. I hope to implement the aspects of Lab 3 (Classification) but, also in addition to Lab 3, determine and plot features importance. I would like more experience with classification and will therefore also utilize the lecture/lab notes and materials to determine how best to optimize and visualize the project.

## 3. What: Dataset, models, framework, components 2pts

Kaggle Dataset URL: https://www.kaggle.com/adityakadiwal/water-potability 
Scikit-learn Classifiers: LogisticRegression(), SVC(), BernoulliNB(), RandomForestClassifier(), GradientBoostingClassifier() 
Possibility of extending to use XGBoost Classifier as well.