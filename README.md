# titanic_rand_forest
Using machine learning to create a model that predicts which passengers survived the Titanic shipwreck

I created a model of machine learning (RandomForestClassifier), that predicts which passengers survived the Titanic shipwreck, for legendary classic Titanic ML competition from Kaggle. So it is a binary classification problem, which I solved a little bit. The created model is pretty simple, but achieves a public score of 78.95%. I used IPythonNotebook and Python 3.

This competition have two similar datasets that include passenger information like name, age, gender, socio-economic class, etc. One dataset is titled `train.csv` (contains the details of the 891 passengers on board and whether they survived or not) and the other is titled `test.csv` (contains the details of the 418 passengers on board). It needes to predict whether the 418 passengers on board (in test.csv) survived.

Submission should be a csv file with exactly 418 entries plus a header row and have exactly 2 columns: PassengerId (sorted in any order); Survived (contains binary predictions: 1 for survived, 0 for deceased).

More information about the Kaggle competition 'Titanic: Machine Learning from Disaster' and data for this you can find on https://www.kaggle.com/c/titanic .
