# AdavanceMachinceLearning Ass 02
ASSIGNMENT QUESTION:
Classify the following dataset to distinguish between skin color and nonskin color. You may try different models but report at least the two top scoring classifiers. Use the following settings for the experiments.
1.	Stratified 5-Fold cross-validation (the dataset is imbalanced)
2.	Report precision, recall, and F1-score (with micro as averaging scheme)
Data Set: https://archive.ics.uci.edu/ml/datasets/Skin+Segmentation
Submit a code document and a word document with setup, results and discussion.

# AdavanceMachinceLearning Ass 03
Use an IDE with a somewhat similar directory/file structure as given below. Try different possibilities to improve accuracy as much as possible. 
Report accuracies, precision, recall, f1-scores for 5-fold and 10-fold cross validation. Its a binary class classification problem with labels
as individuals earning above 50K per year or below.


input
   adultData.xlsx
models
   //store trained models

src
   __init__.py
   dataset.py
   dispatcher.py
   createfolds.py
   engine.py
   feature_generator.py
   loss.py
   metrics.py
   predict.py
   preprocess.py
   train.py
   utils.py
