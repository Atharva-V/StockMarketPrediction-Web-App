# StockMarketPrediction-Web-App
This is Stock market related project in which LSTM is used to predict future stock price and everything is creating on dash where you can check all current stock prices and also added feature which shows top 10 news . Yahoo and BBC-news APIs are used.

## Predict model
predict model.py is the first file to open which takes in a dataset of stock( preferably from yahho finance) and makees predictions using LSTM algorithm and save in it in form "saved_model.h5" in the same directory.
<img src="https://github.com/Atharva-V/StockMarketPrediction-Web-App/blob/main/screenshots/2.png" width="900" height="40">

## Frontend App
Now run main.py which is basically a dash app. It will display a tab where you model will be shown graphically which you can analyse.

<img src="https://github.com/Atharva-V/StockMarketPrediction-Web-App/blob/main/screenshots/3.png" width="550" height="350">

Second tab will allow you to examine all stocks live data using Yahoo finance API.

<img src="https://github.com/Atharva-V/StockMarketPrediction-Web-App/blob/main/screenshots/4.png" width="550" height="350">

Finally the last tab shows all top news using BBC-news API related to stocks.

<img src="https://github.com/Atharva-V/StockMarketPrediction-Web-App/blob/main/screenshots/5.png" width="550" height="350">
