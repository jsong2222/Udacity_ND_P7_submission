# Udacity_ND_P7_submission

I. Package Requirement
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- import operator
- from sklearn.preprocessing import StandardScaler
- #from sklearn.preprocessing import Imputer
- from sklearn.impute import SimpleImputer
- from sklearn.decomposition import PCA
- from sklearn.model_selection import train_test_split, cross_val_score, ShuffleSplit, GridSearchCV
- from sklearn.cluster import KMeans
- from sklearn.linear_model import LogisticRegression
- from sklearn.tree import DecisionTreeClassifier
- from sklearn.ensemble import RandomForestClassifier
- from sklearn.ensemble import GradientBoostingRegressor, AdaBoostRegressor
- from sklearn.ensemble import AdaBoostClassifier, GradientBoostingClassifier
- from sklearn.metrics import accuracy_score, roc_auc_score, confusion_matrix

II. Motivation for Project
- In the current business world, it is always important for a company to know its target customers, to identify life values of the target customers. With the knowledge of the characteristic of target customers, the company will be able to create more specific advertising campaigns to the target customers, increasing the campaign efficiency. The company will also be able to apply the characteristics to find potential customers from the general population as well. The motivation of this project is to find out how to analyze the potential attributes of existing customers and how to apply that knowledge on the general population.

III. Files
- `Udacity_AZDIAS_052018.csv`: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
- `Udacity_CUSTOMERS_052018.csv`: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
- `Udacity_MAILOUT_052018_TRAIN.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
- `Udacity_MAILOUT_052018_TEST.csv`: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).

Besides, there are 2 additional info datasets, which provided the attributes info and value meanings of the above 4 datasets.
- `DIAS Attributes - Values 2017.xlsx`: Meanings of values for columns in the main datasets.
- `DIAS Information Levels - Attributes 2017.xlsx`: Description of columns in the main datasets.

Due to the terms and conditions from the partners who provided data, not all the data files will be available in this git.

IV. Summary of Results
- Summary of the results are provided in the Medium blog post.
The link to the post is: https://medium.com/@jsong01/customer-segmentation-report-for-arvato-financial-services-7ad922982c2a

V. Acknowledgment
- Data sources are provided by the partners of Udacity Data Scientist NanoDegree Program Arvato. The project guidelines are following Udacity Data Scientist NanoDegree Program.