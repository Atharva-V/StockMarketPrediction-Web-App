# StockMarketPrediction-Web-App
This is Stock market related project in which LSTM is used to predict future stock price and everything is creating on dash where you can check all current stock prices and also added feature which shows top 10 news . Yahoo and BBC-news APIs are used.

## Predict model
predict model.py is the first file to open which takes in a dataset of stock( preferably from yahho finance) and predicts model and save in it in form "saved_model.h5" in the same directory.
<img src="https://github.com/Atharva-V/StockMarketPrediction-Web-App/blob/main/screenshots/2.png" width="100" height="100">

## Frontend App
Now run main.py which is basically a dash app. It will display a tab where you model will be shown graphically which you can analyse.
![3](https://user-images.githubusercontent.com/74040947/133564606-1acf9862-0fbd-459d-ae76-c088150077cf.png)

Second tab will allow you to examine all stocks live data using Yahoo finance API.
![4](https://user-images.githubusercontent.com/74040947/133564794-d646da5a-8bf8-4b65-aa3c-8dbb9f6a95df.png)

Finally the last tab shows all top news using BBC-news API related to stocks.
![5](https://user-images.githubusercontent.com/74040947/133564889-76f351a4-bdae-403f-b0e2-fdf8436a1fb5.png)
