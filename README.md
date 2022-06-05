# Time Series Forcasting

This is a Python application allowing users to use time series forcasting to analyze and forcast E-Commerce platform's serch traffic, stock price and revenue

The application works by importing and cleaning data from csv, Mine the search traffic data for seasonality, Create a time series model with Prophet, applying Kmeans and PCA method to clusering data, Forecast revenue by using time series models. 
 

 
---

## Technologies

This project leverages python 3.7 +, pandas, Prophet


---

## Installation Guide

Note: please use google Colab (not jupyter) to run the codes

Before running the application, first make sure below libaries are installed

```python
  pip install pandas
  pip install pystan
  pip install fbprophet
  pip install hvplot
  pip install holoviews
```

--

## Usage

Step 1: run crypto_inevstiments.ipynb
```python
forecasting_net_prophet.ipynb
```
Step 2: import data(search trend) from csv.


<img width="373" alt="image" src="https://user-images.githubusercontent.com/99616004/172058039-6674c57a-c1f5-40e6-bb71-c98ef583dc89.png">


Step 3: Use hvPlot to visualize the data for May 2020


<img width="762" alt="image" src="https://user-images.githubusercontent.com/99616004/172058118-677d1042-d255-4764-9b66-cd7fddd8ca14.png">



Step 4: Group the hourly search data to plot (use hvPlot) the average traffic by the day of week 


<img width="765" alt="image" src="https://user-images.githubusercontent.com/99616004/172058193-cd23a487-a37b-4c7f-90ba-6abf267f0b12.png">


Step 5: Use hvPlot to visualize the hour of the day and day of week search traffic as a heatmap.

<img width="751" alt="image" src="https://user-images.githubusercontent.com/99616004/172058219-e5090177-55d0-413f-bdd8-b9317658dc44.png">

Step 6: Group the hourly search data to plot (use hvPlot) the average traffic by the week of the year

<img width="745" alt="image" src="https://user-images.githubusercontent.com/99616004/172058322-99304025-5546-4de7-806f-1a0822d5f46a.png">

Step 7: Use hvPlot to visualize the closing price of the df_mercado_stock DataFrame.

<img width="729" alt="image" src="https://user-images.githubusercontent.com/99616004/172058355-6e4f8934-3f19-4504-8c51-c48966a3f95b.png">

Step 8: Use hvPlot to visualize the close and Search Trends data.

<img width="776" alt="image" src="https://user-images.githubusercontent.com/99616004/172058440-f911c93f-4283-465b-933b-c12308115350.png">

Step 9: Use hvPlot to visualize the stock volatility

<img width="753" alt="image" src="https://user-images.githubusercontent.com/99616004/172058484-94a387f2-f8ca-4d2c-b311-810c41199323.png">

Step 10: Plot the Prophet predictions for the Mercado trends data

<img width="762" alt="image" src="https://user-images.githubusercontent.com/99616004/172058519-415439cc-0e51-4ce3-bcd8-f98fe6dd8346.png">

Step 11: UFrom the forecast_mercado_trends DataFrame, use hvPlot to visualize the yhat, yhat_lower, and yhat_upper columns over the last 2000 hours 

<img width="662" alt="image" src="https://user-images.githubusercontent.com/99616004/172058572-540485a1-02d3-421a-9b3b-b084b50c9ee0.png">


Step 12:  Use the plot_components function to visualize the forecast results 

<img width="663" alt="image" src="https://user-images.githubusercontent.com/99616004/172058642-9e6a99d9-a6f5-4301-ab68-cc2c4b14f7a0.png">

<img width="687" alt="image" src="https://user-images.githubusercontent.com/99616004/172058683-f854ed38-a7c6-4d8b-aad2-f1dae727be74.png">

Step 15: Use hvPlot to visualize the daily sales figures 

<img width="751" alt="image" src="https://user-images.githubusercontent.com/99616004/172058768-77503307-0045-416e-bf17-2cea06eb01e4.png">

Step 16: Use the plot_components function to analyze seasonal patterns in the company's revenue

<img width="658" alt="image" src="https://user-images.githubusercontent.com/99616004/172058795-f8b7b403-3a78-426e-b250-b4a3687a2041.png">

Step 17: Plot the predictions for the Mercado sales

<img width="693" alt="image" src="https://user-images.githubusercontent.com/99616004/172059070-b7c029db-85f9-45f6-936f-9f4b1ef9f4a2.png">

Step 18: # Displayed the summed values for all the rows in the forecast_quarter DataFrame

<img width="288" alt="image" src="https://user-images.githubusercontent.com/99616004/172059112-22a3944a-619a-44d4-ad24-a5188f7b8fe7.png">




Conclution:  

Prophet proves a very powerful tool to check the seasonality of the data as well as a good tool for forcasting for the future data



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
