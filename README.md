# Insurance-Cost-Prediction-using-NN
Neural Network model to predict insurance cost from a medical cost dataset.


In this notebook we try to predict the insurance cost based on the medical data provided to us by the dataset.


We make use of "mean absolute error" loss function alongside "Adam" optimizer and use the metrics of mean absolute error.


After creating the model and compiling it we run it for 500 epochs to get a good result for our data.

![image](https://user-images.githubusercontent.com/22250758/137962638-fd449116-87a5-4337-b48c-13dcee0b046f.png)


As a measure of evaluation we see the chart below representing its performance. 

![image](https://user-images.githubusercontent.com/22250758/137962031-b9899b5a-00fb-4012-82bc-c0809f3d48ba.png)


After going with the previous iteration we tweaked it a bit to better our overall model performance.


The main change we made here was to make changes to the learning rate and after finally setting it at our chosen value we run it for 200 epochs to get our dinal model performance score.

![image](https://user-images.githubusercontent.com/22250758/137962438-cb090fda-a4c8-4069-83f7-a86727bb0120.png)

This modifies our score to give us a better result as shown below : 

![image](https://user-images.githubusercontent.com/22250758/137962563-e4414231-4ab5-47da-9409-3ea8a5c94ec5.png)
