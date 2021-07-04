## GENDER_CLASSIFICATION

This is the code for the gender classification. The code uses the scikit-learn machine learning library to train a decision tree on a small dataset of body metrics (height, width, and shoe size) labeled male or female. Used 3 classifiers ( **SVM**, **perceptron**, **KNN** ) and trained them on the dataset and printed out the best one.

## Dependencies

- Scikit-learn  ( `pip install sklearn` )
- Numpy ( `pip install numpy` )

### For importing the classifiers
- `from sklearn.svm import SVC`
- `from sklearn.linear_model import Perceptron`
- `from sklearn.neighbors import KNeighborsClassifier`
- `from sklearn.metrics import accuracy_score`
- `import numpy as np`

### Install any missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

## Conclusion:
KNN will give the highest accuracy followed by SVM and perceptron
