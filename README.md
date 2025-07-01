# LSTM forecasting fuel price
Forecasting price of coal and crude oil for 7 and 30 days with Long Short-Term Memory recurrent neural network.
![image](https://github.com/user-attachments/assets/06c2ee62-8d21-413f-9f55-b3e6be8bf3d2)

Preprocessing.ipynb - Jupyter Notebook containing input data preparation for models training process

For both timeframes, prices were predicted by models trained based only on closing prices of the raw material and based on closing prices and selected technical indicators. 

Predicting multiple time steps requires the use of multi-step forecasting.
A recursive strategy and a multiple output strategy were used to create a forecast of natural fuel closing prices.
![image](https://github.com/user-attachments/assets/7aa854c7-d9c0-4d71-80e3-95b8f7790790)
