# Impute-missing-data-with-KNNImputer
When signaficant amont of data are missing, what can we do? Impute the missing data with mean or median? Actually, Scikit-Learn provides a KNNImputer which can impute missing data using the mean value from n_neighbors nearest neighbors found in the training set.

Before imputation, there are significant amount of "Cost", a few "Weight", and many "Ingredient Number" data missing in the dataset.

![image](https://github.com/hanfei1986/Impute-missing-data-with-KNNImputer/assets/59255164/353dcbd8-f733-4ba4-a61d-6cdaf8e686bd)

After imputation, all the columns are filled.

![image](https://github.com/hanfei1986/Impute-missing-data-with-KNNImputer/assets/59255164/b4bcf1f2-61b0-48b9-aa32-473961a4e8ab)

Let's have a look at the imputation effect. Amazing!

![image](https://github.com/hanfei1986/Impute-missing-data-with-KNNImputer/assets/59255164/1e97712f-5979-4e5d-b700-88df0af46a21)

