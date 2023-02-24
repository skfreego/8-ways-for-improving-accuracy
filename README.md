## 8-ways-for-improving-accuracy

8 Proven Ways for improving the “Accuracy” of a Machine Learning Model
  1. Add more data
	2. Treat missing and Outlier values
		Missing: In case of continuous variables, you can impute the missing 	values with mean, median, mode. For categorical variables, you can treat 	variables as a separate class. You can also build a model to predict the 	missing values. KNN imputation offers a great option to deal with missing 	values. To know more about these methods refer article “Methods to deal and 	treat missing values“.
		Outlier: You can delete the observations, perform transformation, 	binning, Imputation (Same as missing values) or you can also treat outlier 	values separately.  You can refer article “How to detect Outliers in your 	dataset and treat them?” to know more about these methods.
	3. Feature Engineering
		 Feature engineering process can be divided into two steps:

		Feature transformation: There are various scenarios where feature 	transformation is required:
	A) Changing the scale of a variable from original scale to scale between 	zero and one. This is known as data normalization. For example: If a data 	set has 1st variable in meter, 2nd in centi-meter and 3rd in kilo-meter, in 	such case, before applying any algorithm, we must normalize these variable 	in same scale.
	B) Some algorithms works well with normally distributed data. Therefore, we 	must remove skewness of variable(s). There are methods like log, square 	root or inverse of the values to remove skewness.
	Transformation_1C) Some times, creating bins of numeric data works well, 	since it handles the outlier values also. Numeric data can be made discrete 	by grouping values into bins. This is known as data discretization.
	Feature Creation: Deriving new variable(s ) from existing variables is 	known as feature creation. It helps to unleash the hidden relationship of a 	data set. Let’s say, we want to predict the number of transactions in a 	store based on transaction dates. Here transaction dates may not have 	direct correlation with number of transaction, but if we look at the day of 	a week, it may have a higher correlation. In this case, the information 	about day of a week is hidden. We need to extract it to make the model 	better.

	4. Feature Selection
	Feature Selection is a process of finding out the best subset of attributes 	which better explains the relationship of independent variables with target 	variable.
	
	You can select the useful features based on various metrics like:

	Domain Knowledge: Based on domain experience, we select feature(s) which 	may have higher impact on target variable.
	Visualization: As the name suggests, it helps to visualize the relationship 	between variables, which makes your variable selection process easier.
	Statistical Parameters: We also consider the p-values, information values 	and other statistical metrics to select right features.
	PCA: It helps to represent training data into lower dimensional spaces, but 	still characterize the inherent relationships in the data. It is a type of 	dimensionality reduction technique. There are various methods to reduce the 	dimensions (features) of training data like factor analysis, low variance, 	higher correlation, backward/ forward feature selection and others.

	5. Multiple algorithms

	6. Algorithm Tuning

	7. Ensemble methods
		Bagging (Bootstrap Aggregating)
		Boosting

	8. Cross Validation
