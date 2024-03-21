# Shipment-Status-Prediction-using-ML

# PROBLEM STATEMENT:
Developing a machine learning model to accurately predict the product shipment status ,to predict whether the product will deliver on time or not by using past data.

# Flow Chart :
DATA COLLECTION
DATA PREPROCESSING
BASE MODEL
CLASS IMBALANCE TREATMENT
EDA-OUTLIERS, SKEWNESS TREATMENT
MODEL  BUILDING
SECOND DATAFRAME
FEATURE SELECTION
FINAL DATAFRAME

# DATASET INSIGHTS \n
This dataset contains 10099 rows and 12 columns

# TARGET COLUMN
 This target variable of this data is “Reached_on_time” which has the values one and zero. 
 The target variable is categorical.
 There are 11 independent columns like Warehouse Block, Cost of the Product, weight of product ,Shipment Mode that impacts the target variable.

 # Base Model
''' Modelname	Accuracy	TPR	FPR	Specificity	Precision	F1-score
0	Logistic	61.863636	0.540	0.330	0.660	0.530	0.560
1	Decision_tree	65.227273	0.540	0.300	0.710	0.570	0.600
2	Random_forest	66.727273	0.680	0.340	0.650	0.580	0.610
3	KNN	65.863636	0.616	0.311	0.688	0.581	0.613
4	Naive_bayes	67.454545	0.789	0.406	0.593	0.576	0.930
5	SVM	66.500000	0.630	0.310	0.689	0.580	0.603
6	ADA BOOST	68.227273	0.762	0.374	0.625	0.588	0.663
7	XG Boost	66.636364	0.000	0.387	0.612	0.573	0.647 '''



