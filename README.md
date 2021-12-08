# DiabetesReadmission_Ary-d
This project attempts to create a machine learning classification tool that as accurately as possible classifies 
whether a person with diabetes will be readmitted within 30 days, in more than 30 days, or not readmitted at all.
The models tried are all from sklearn-
LogisticRegression with penalty=none,l1,l2 and elasticnet
RandomForestClassifier
KNeighborsClassifier
SVC
The best performing model was SVC with parameters C=10, gamma=0.01
Mean test score of this model: 0.593142509237481
Standard deviation of test score: 0.0026521117330162245

The dependencies used are as follows-
  - python=3.9
  - matplotlib=3.4.2
  - pandas=1.3.1
  - scikit-learn=0.24.2
  - numpy=1.21.1
  - shap=0.39.0
  - jupyter_client
  - jupyter_core
  - jupyterlab
  - jupyterlab_server
  - jupytext
  - rise
