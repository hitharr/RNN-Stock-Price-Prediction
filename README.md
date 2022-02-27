# RNN-Stock-Price-Prediction
### Description
The final project offers a comparison between a basic Recurrent Neural Network example coded with PySpark notebook against a Long Short-Term Memory Recurrent Neural Network using the keras library to perform time series prediction on stock prices. For this project, the Recurrent Neural Networks were used to predict the close price of the INFOSYS stock and then prints the Root Mean Squared Error on the training and test sets. The National Stock Exchange time series dataset was used was sourced from Kaggle.

The Kaggle Dataset can be originally found here: [https://www.kaggle.com/atulanandjha/national-stock-exchange-time-series](https://www.kaggle.com/atulanandjha/national-stock-exchange-time-series)

The data used for this project is hosted publicly on Amazon S3:
[https://s3.amazonaws.com/cs6350.0u1/Project/infy_stock.csv](https://s3.amazonaws.com/cs6350.0u1/Project/infy_stock.csv)

### How to Run
The project showing the basic RNN implementation can be found here:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1005059527658068/660925766944664/7740729220923964/latest.html


The project showing the implementation of the LSTM RNN with libraries can be found here:
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/1005059527658068/660925766944681/7740729220923964/latest.html

In order to run the Databricks notebooks. follow the below steps:
 - Create a cluster 
	 - NOTE: The notebook using keras requires creating a Databricks Cluster with a Runtime Version that includes ML (Databricks Runtime for Machine Learning). I created the cluster with Runtime 7.1 ML.
- Attach notebook to cluster
- Change parameters as desired under comment `#Params that can be changed`
- Click `Run All` at top of notebook
