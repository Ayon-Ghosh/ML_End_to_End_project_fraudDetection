# ML_End_to_End_project_fraudDetection

Full stack ML project with end to end pipeline. 

EDA as well.

Problem Statement													
To build a classification methodology to determine whether a customer is placing a fraudulent insurance claim.													

Clustering	kneed import KneeLocator - for KMeans
Models	XGBoost and SVM with HyperParameter tuming trained for each cluster and best model with best parameters are choosen for each cluster 
	
	Feature Engineering
Scaling	Standard Scaler
String operation	String operation on specific column
Impute Missing values	KNN Imputer
	
	
	Training Model Stack
Kmeans	Clsuter the data
Models	Train each group of models for each cluster and save the best performing model for each cluster
	
	Prediction Model Stack
Kmeans	Cluster the data
Model	Use the respective best saved model for each cluster to predict

