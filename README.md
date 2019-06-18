# The-Winton-Stock-Market-Challenge
The Winton Stock Market Challenge
The purpose of this project is to take on the Winton Stock Market Challenge on Kaggle. The aim of this challenge is to predict intra and end of the day returns using already given historical stock performance and a host of masked features.
Two Neural Network models were used to predict stock returns, whose performance was measured with loss and Mean Square Error.

The Winton StockMarket CIn order to predict the future stock returns, given the data, the best fitting models would be Long Short Term Memory Networks and the Sequential Model. hallenge is a Kaggle contest sponsored by Winton Capital. A machine learning model is to be trained on data consisting of historical stock performance and a host of masked features to predict future intra and end of the day returns.

The different approaches adopted in this project utilize regression using Neural Networks to make future predictions of stock returns. 

The initial approach involved using the Keras Regression Model. After splitting and normalizing the data, the above-mentioned Regression model was trained on it. This model proved to be overfitting and the loss was 0%. Then the Sequential Model was tried. Initially, it gave a large Mean Square Error. On trying deeper topology, different number of epochs, and varied batch sizes this error, as well as loss, was reduced. The final approach used Long Short Term Memory networks that are a special kind of Recurrent Neural Networks. This model was trained on the data to give an acceptable loss and MSE. Further, the LSTM Model was also trained on relative returns. The data was processed to give the stock returns relative to the first day instead of the day previous to the respective data point. This approach also gave an acceptable loss and MSE.

In order to predict the future stock returns, given the data, the best fitting models would be Long Short Term Memory Networks and the Sequential Model. 
