## Resampling 

**Which model had the best balanced accuracy score?**

1. RandomOverSampler = ~.82
2. SMOTE = ~.80
3. ClusterCentroids = ~.80
4. SMOOTEENN = ~.79

*RandomOverSampler had the best balanced accuracy score.*

**Which model had the best recall score (average)?** 

1. RandomOverSampler = .85
2. SMOTE = .87
3. ClusterCentroids = .75
4. SMOTEENN = .86

*SMOTE had the best average recall score.*

**Which model had the best geometric mean score (average)?**

1. RandomOverSampler = .82
2. SMOTE = .79
3. ClusterCentroids = .80
4. SMOTEENN = .79

*RandomOverSampler had the the best average geometric mean score.*

## Ensemble Learning

**Which model had the best balanced accuracy score?**

1. BalancedRandomForestClassifier = ~.77
2. EasyEnsembleClassifier = ~.93

*EasyEnsembleClassifier had the best balanced accuracy score.*

**Which model had the best recall score (average)?**

1. BalancedRandomForestClassifier = .90
2. EasyEnsembleClassifier = .94

*EasyEnsembleClassifier had the best average recall score.*

**Which model had the best geometric mean score (average)?**

1. BalancedRandomForestClassifier = .76
2. EasyEnsembleClassifier = .93

*EasyEnsembleClassifier had the best average geometric mean score.*

**What are the top three features?**

Feature    |   Score         
            ---  | --- 
'total_acc'| ~ .08
'pub_rec' | ~ .07     
 'revol_bal' | ~ .068      

