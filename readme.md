This project analyzes different forecasting models and selects the best model to forecast the stock index for the following 6 stocks:

- Adobe (ADBE)
- Amazon (AMZN)
- Costoc (COST)
- Marriott Int (MAR)
- Lululemon Athletica (LULU)
- American Airlines (AAL)

For all of our analysis, the daily stock Closing Prices are used for each stock.

Setup:
------

Run the scripts in install.txt to install the necessary libraries in R.

Run:
----

Run the scripts in r-scripts.txt to run the model comparison in R.
The results are saved in results/ folder.

After a successful run, the results folder would contains the following:
- **stockdata-*.png** files containing the stock trend for the entire duration for each stock.
- **forecasts-*.png** files containing the forecasts predicted by different models for each stock.
- **results.txt** containing the name of the best model for each stock.
- **results-*.png** files containing the forecast with the best chosen model
