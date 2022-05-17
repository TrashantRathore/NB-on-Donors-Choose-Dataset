# NB-on-Donors-Choose-Dataset
This Code includes all these important points:
1. Dataset used is Donors Choose Dataset with 100k rows.
2. Splitted Dataset into 75% in Train and 25% in Test data.
3. Encoding numerical and categorical features into 2 sets i.e first set making BOW(Bag of Words) and second TF-IDF set. 
4. Used n-gram range upto 4 for better getting words with symantic meanings.
5. Dataset used in my Program is already preprossed on all features that involves data cleaning of all features.
6. Took hyperparameter(alpha) range in 10^-5 to 10^2 and explored 'class_prior', 'fit_prior' in it.
7. Plotted performance curve between train and CV data to get optimal value of alpha(hyperparameter of Naive Bayes Classifier).
8. With BOW used RandomSearchCV in finding best hyperparameter with cv = 10.
9. With TF-IDF used GridSearch SV in procuring best hyperparameter with cv = 20.
10. Used ROC Curve between hyperparameters and AUC for getting best HP.
11. AUC Score after applying both of these BOW and TFIDF sets were 65% and 55% even after tuning all parameters.
12. Plotted ROC Curves, Performance Curve, Confusion Matrices etc
13. Libraries used numpy, pandas, nltk, matplot, seaborn, sklearn's packages including TfidfVectorizer, CountVectorizer, GridSearchCV, RandomizedSearchCV, MultinomialNB,  Plotly and Pretty Table.
14. All References are given in top/middle of the cell where the reference had been taken.
15. All Observations are written at the bottom of the python notebook and all instructions used in this notebook is mentioned at top of the notebook.
16. Please, if anyone is taking this code mention my ID as Reference. 
17. Dataset can be downloaded from  https://www.kaggle.com/competitions/donorschoose-application-screening/
18. Welcome you all for suggestions to me by any way to improve AUC score.
