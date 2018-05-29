All the feature engineering is explained in code file only.
Used Mode for categorical values imputation and mean values for Numericla values Imputation.
Didn't make large diff since no' of missing values are very less.'
Removed redundant features based on correlation value and distributions.

1)First run First.py
	Used Dummy encoding and feature engineering.
	Built models with SVM with diff kernels,Xgboost and Logistic regression.

2)Second run Secoond.py
	Used Label Encoding and some feature Engineering.
	Built models with Xgboost and LightGBM.

3)Then run Ensemble.py
	Used Ranking to Combine all the models results.


4)Even though Logistic and LightGBM didnt improve the results.


