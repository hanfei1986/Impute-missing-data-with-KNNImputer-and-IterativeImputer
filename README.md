# Impute-missing-data-with-KNNImputer-and-IterativeImputer
When signaficant amont of data are missing, what can we do? Impute the missing data with mean or median? That will be a diaster. Actually, Scikit-Learn provides two powerful imputers, KNNImputer and IterativeImputer. The former imputes missing data using the mean value from n_neighbors nearest neighbors found in the training set, and the latter is inspired by R's MICE package and imputes missing values by modeling each feature with missing values as a function of other features in a round-robin fashion.

Before imputation, there are significant amount of "Cost", a few "Weight", and many "Ingredient Number" data missing in the dataset.

![image](https://github.com/hanfei1986/Impute-missing-data-with-KNNImputer/assets/59255164/353dcbd8-f733-4ba4-a61d-6cdaf8e686bd)

After imputation, all the columns are filled.

![image](https://github.com/hanfei1986/Impute-missing-data-with-KNNImputer/assets/59255164/b4bcf1f2-61b0-48b9-aa32-473961a4e8ab)

Let's have a look at the imputation effect. Amazing!

![image](https://github.com/hanfei1986/Impute-missing-data-with-KNNImputer/assets/59255164/1e97712f-5979-4e5d-b700-88df0af46a21)

