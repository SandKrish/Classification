This notebook predicts if the target class belong to 0 or 1.

The are two different dataset - Training set and Test set.
- Training set contains  3910  rows with  57 features and 1 target
- Test set contains  691  rows and  57 features.

Google colab notebook is used to write the algorithm.

Different Libraries along with there version used for this algorithm are

	- pandas - 1.1.5
	- numpy - 1.19.5
	- seaborn - 0.11.2
	- matplotlib - 3.2.2
	- sklearn - 1.0.1
	- tensorflow - 2.7.0
	- keras - 2.7.0

Here I have used ML classification alogrithm Logistic regression and Random Forest and Neural Network ANN and LSTM to predict the classfication class.
Among ML random forest gave best accuracy.

NN had a overfitting issue, so it was over come by doing feature engineering by extracting 10 features by F-Score Selection. 
It reduced overfitting, but overall accuracy is less than Random Forest.

So we are using Random Forest for prediction as it is in par with the fact that RF works well with high dimensional data and NN are best for unstructured data.



	
