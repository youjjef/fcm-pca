# fcm-pca
Implemented fuzzy C means clustering algorithm on iris 
dataset before and after PCA to compare results
(implemented both algorithms from scratch).
The ACC Of FCM model decreases slightly after applying PCA , very small change As we Takes The Most 2 Importnat Featuers As Our PCA Components/
Select The most 2 important components According to highest varinces of each feature
--------------------------------------------------------------------
As you can see the variance of first two features equals :
------------------------------------------------------------
72.9624454132999 + 22.850761786701746 = 95.813207200001646

---> Thus we chose these two as PCA

Performance Before applying PCA :
------------------------------------
confusion matrix is:

[[50  0  0]

 [ 0 39 11]

 [ 0 13 37]]

Accuracy of the model is 84.0

Recall of the model is 84.0

Precision of the model is 84.02777777777779

F1-Score of the model is 84.01388659282526

Performance after applying PCA :
-------------------------------------
confusion matrix is:

[[50  0  0]
[ 0 39 11]

 [ 0 14 36]]

Accuracy of the model is 83.33333333333334

Recall of the model is 83.33333333333334

Precision of the model is 83.39355011374282

F1-Score of the model is 83.36343084928502
