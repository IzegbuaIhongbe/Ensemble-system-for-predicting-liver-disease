# Developing an ensemble system for predicting liver disease in adults

Liver disease is a significant health concern that affects millions of people worldwide. Early detection of liver disease can help prevent complications and improve patient outcomes. 

The aim of this project is to develop and compare 2 types of ensemble system that predict the presence of liver disease in adults.

The first approach taken is from a pure data science perspective, with a focus on pre-processing the dataset before training the models.

The second approach looks into medical literature to identify and possibly categorise important attributes in line with the medical field's point of view which involves creating new attributes, categorizing feature variables based on established medical knowledge, and incorporating domain-specific insights into feature selection and engineering. 

Some medical articles `Article 1`, `Article 2`, `Article 3`, `Article 4` (uploaded in the repo) are utilized to help with medical knowledge, also categorising the Age attribute into young, middle-aged, and older adults help to identify patterns related to age in the dataset.

The solution would predict (with reasonable accuracy) whether a new patient (i.e., one that is not in the dataset) is at high risk of liver disease. It is also important that the solution performs well for both well and at-risk persons.

Both ensemble systems are compared to determine which one would perform better.


# Data

The dataset used in this project is titled `Liver_Disease_Raw_Dataset` and is available in the repo, data processing is done in the project notebook.

