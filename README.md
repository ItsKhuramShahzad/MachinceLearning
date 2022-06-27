# Adavance Machince Learning Ass 01
Apply any 4 /5 clustering algorithms on the following datasets and compare their results using at least 4 metrics. Implement the algorithm of at least one of the clustering algorithms i.e., do not use library functions for it.



1. Submit your code with comments

2. Try to fine-tune the algorithms as much as possible to achieve the
highest score on the evaluation metrics. Provide a description file
having details of parameters used for each algorithm (the final values
only i.e., after trying different arrangements only use the values that
are producing the best evaluation scores)  

3. A 2/3 page report
presently results through tables and figures. Discuss the results in
tables and figures in the text. Discuss reasons why certain algorithms
are performing better as compared to others.

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
