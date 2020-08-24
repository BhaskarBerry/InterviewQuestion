# InterviewQuestion
1. What is Machine Learning?
2. Differnce between Supervised learning and Unsupervised learning?
3. What are the steps involued for solving a datascience problem ?
4. What is datacleaning and Preprocessing ?	
5. what is classification and Regression ? when one iuse classification over regression ?
6. What is Clustering ? How it is different from classification ?
7. How is the K-nearest neighbour algorithms different from k-means clustering ?
8. What is normal distribution ?
9. What is bias variance trade-off ?
10. What is Precision and recall ?
11. What is over-fitting ?
12. What is multicollinearity ?
13. What is dimesionality reduction ?
14. When to use cross validation ? -- overfitting

14. ML end to End

--------------------------------------------------------------------------------
Q. What is Machine Learning?
	ML- Learn the pattern based on the data provided to any model
	Classified into Supervised and unsupervised Learning
	Supervised Learning -- we have label data to identify the patterns ex: Provide based on the data for providing a loan (default or not)  
	unsupervised Learning  -- we dont have label data, extracts based on the similarities of the data to identify some patterns(K-Means CLustering , Recommender system)

Q. What are the steps involued for solving a datascience problem ?
    > Identify the problem & formulating problem defination
    > Talk to different team , ER team ,Busiines steam
	> Data cleaning and pre-processing (Quality of data)
	> EDA(Understand the data, statistics)
	> Feature Analysis and selection
	> Split the data train, and test and validation set
	> Result should be based on the Target after applying the ML models

Q. What is datacleaning and Preprocessing ?	
	> Data Cleaning - missing values, null, large rows, -- remove if the data is huge , small -imputation (mean, median ,constant)
					- Continuous Variable
					--Categorical variables --gender , handle them dummy variables--> ,numeric variables	
	> Data split -- train and test split -- 80-20
	> Feature Scaling - Z-score(std dt from the mean value), standardization and normalization
	
Q. what is classification and Regression ? when one iuse classification over regression ?
	C -- traget varibale -- category/class --yes/no
		Ex: loan can be Given or not
		k-nn, dt classifier, Logit rec, Svm 
	R -- target varibale  -- continuous -- sales forecating.weather	
		Ex: Linear Regression,Poly regre, DT regression 
		
Q. What is Clustering ? How it is different from classification ?
	Classification is a supervised learing -- provided the labelled data
	Clustering -- donot have previously labelled data. group the data based on the classes of cluster, but the data in the cluster are similar to each other
	
Q. How is the K-nearest neighbour algorithms different from k-means clustering ?
	Clustering - K-means
		Data point - 2 features - closer to each other and form clusrt based on the similarties
	Classification -KNN	
		Data ponts - based on the label - it classifies(based on the n- neighbours)
			
Q. What is normal distribution 
	Type of probability distribution also known as Gaussian distribution -- Bell curve
	99- 3 sd
	95- 2 sd
	68- 1 sd
	
Q. What is bias variance trade-off?	
	Applicable in Supervised Learning problem 
		1. Bias Error -- High bias -- linear regresion y= mx + c
			chnage in  traing data will not lead much chnage in target varible
			 
		2. Variance Error -- Change the data result will go off the line .. trained too much on the data --
			 High variance mean small chnage in the data leads to huge chnage in the target varibale  (DT,   Knn, SVM -- non linear models)
			 Low variance => small chnage in the feature data will lead to small chnage in  the taget data
		3. Irerudceable error
			
Q. What is Precision and recall ?
	P and R are measures of accuracy
	P - num of relevant instance among the total instance whihc we have predicted  tp/ tp + fn
	R - Sensitivity -   tp/tp+ fp

Q. What is over-fitting ?	
	TRained on the data -- basically memorized and not able to generalized -- nnon paramteric(RF, DT , AdaBoost)has a greater tendecy
	train data 0good and test daat -bad
	

Q. What is multicollinearity ?
	MC-- LInear Regresion -- parameteic model --
		-- IV related to each other 
		-- IVF -- reduce the dimesion , reduce the feature 
		
Q. What is dimesionality reduction ?
	--PCA -- reduce the feature without loosing the variance
	-- less complex
	
	
		
		
			