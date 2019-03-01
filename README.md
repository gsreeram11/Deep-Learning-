# Stock-Price-Prediction-

The availability of data has facilitated the creation of several new research methodologies, one such methodology is deep learning. 
It is a subfield of Machine Learning focussed on learning representations of the input data through successive layers of representation. 
In deep learning, these layered representations are learned via models called neural networks. Through this project my aim is to create 
a deep learning model that predicts the stock price with the help of neural networks. 
	
Stock price prediction is an extremely difficult task and requires accounting for a lot of variables. In this project I will be taking a 
simpler approach in order to effectively learn the application and functionality of neural networks in a deep learning model. 
I will be outsourcing preprocessed stock data from Kaggle and will be only using the closing price for training, 
testing and prediction purposes. I will be approaching this as a regression problem rather than a binary classification problem. 
	
I wish to address two of the most common issues that is seen around machine learning, first is the problem of “Vanishing Gradient Descent”
and the second is the trade-off between computation expensiveness and representational power of a model. By using LSTM and GRU layers 
I would like to understand how the two layers get rid of the gradient problem and present the infamous trade-off of one being more 
powerful and the other being more efficient. 
	
I will be creating three models in order to analyze the accuracy. The first model will have only LSTM layers, the second model will have 
only GRU layers and the third model will have a combination of both. After tuning each model independently, I will identify the one with
the best result. 
	
The primary purpose of this project is to create a base stock price prediction model. I would like to add sentimental analysis, 
technical indicators and momentum buys/sells in my analysis in the coming future in order to make the model more robust and the 
prediction more accurate in real-time. 

![alt text](Desktop/performance.png)
