Experimenting with GCP - Bigquery creating ML model. Tutorial for self learning purpose only.

For more details & instructions - https://cloud.google.com/bigquery-ml/docs/bigqueryml-web-ui-start

1 Using BigQuery create a regression model using public datasets predict whether a website visitor will make a transaction

2. create model SQL command 

3. Evaluate your model

4. Predict model on the number of visitors from different countries will maka a transaction.



![image](https://user-images.githubusercontent.com/49286341/64492843-aaa7dd80-d22d-11e9-9c2d-70f14821ee5f.png)



![image](https://user-images.githubusercontent.com/49286341/64492845-ae3b6480-d22d-11e9-806c-3399e108de6e.png)



![image](https://user-images.githubusercontent.com/49286341/64492847-b1365500-d22d-11e9-836e-f1b5891e41d3.png)



![image](https://user-images.githubusercontent.com/49286341/64492848-b5627280-d22d-11e9-831c-1cc07e62e956.png)



Create a logistic regression model using Google Analytics Sample dataset for BigQuery. This create model command trains the model using the data retrieved from select command.


![image](https://user-images.githubusercontent.com/49286341/64492850-b98e9000-d22d-11e9-88c0-3696e5205d81.png)



![image](https://user-images.githubusercontent.com/49286341/64492851-bdbaad80-d22d-11e9-9455-4aab0fd15411.png)


It runs few iterations.



![image](https://user-images.githubusercontent.com/49286341/64492853-c1e6cb00-d22d-11e9-9aa3-cd27db925b69.png)


Model statistics displayed in Graph. There is also Table format available. 


![image](https://user-images.githubusercontent.com/49286341/64492857-c90dd900-d22d-11e9-9b7a-d90a15feeb16.png)


Evaluate the model - Lables are 0 and 1 which represents no transactions and transactions made

![image](https://user-images.githubusercontent.com/49286341/64492859-cf9c5080-d22d-11e9-8e77-9d2149b6391f.png)



![image](https://user-images.githubusercontent.com/49286341/64492861-d32fd780-d22d-11e9-9e03-83bc08dbf642.png)




![image](https://user-images.githubusercontent.com/49286341/64492863-d62ac800-d22d-11e9-8546-3045e81c9077.png)


This query provides the prediction for website visitors from each country and number of transactions made.

![image](https://user-images.githubusercontent.com/49286341/64492864-d925b880-d22d-11e9-9468-907993948532.png)


![image](https://user-images.githubusercontent.com/49286341/64492870-db881280-d22d-11e9-959b-3d1f2a264a8b.png)
