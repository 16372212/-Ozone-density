根据臭氧浓度变化的特性，基于污染源在线排放数据、气象监测数据以及空气质量监测数据构造特征，运用机器学习方法进行臭氧浓度预测.
(this jupyter file is used to predict the classification task of "orzone")

Python,Jupyter

Algorithm：logistic and randomTree

Dataset:Own dataset about Ozone density

Conclusion：
 1. Both models have achieved very high accuracy on both data sets.
 2. However, due to the large difference between the number of positive and negative samples, and a lot of loss data, 
 these factors may lead the prediciton not accuracy,
 However by comparing ROC curve, we find that randomforest classifier is better than logistic regression model
 and they both get very high accuracy
 3. Although randomforestclassifier is better than logistregression in performance, 
 its training time is much loger
 So, if we want to train a model with very big data, we could choose logistic first , if the data is not so big, we could use decision tree 