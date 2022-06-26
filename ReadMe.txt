
# Classification

## [1. Class Imbalance Dataset](https://github.com/SandKrish/Classification_Prediction/blob/main/imbalance-insurance-data-analysis.ipynb)
This notebook is used to analyze Insurance Imbalance Data.

## [2.KNN-SVM-SVM with Kernel](https://github.com/SandKrish/Classification_Prediction/blob/main/knn-svm-svm-with-kernel-hyperparameter.ipynb)
This notebook is used to analyze a dataset with KNN, SVM and SVM with Kernel

## [3. Binary_Classification of huge dataset](https://github.com/SandKrish/Classification_Prediction/blob/main/Binary_Classification_Prediction.ipynb)
This notebook predicts if the target class belong to 0 or 1 for nuge dataset with 58 columns.


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



	
