# ml_gold_price_predictor
![image](https://user-images.githubusercontent.com/64217477/229080970-f7570c8c-92c7-442d-a69f-dfce08385bed.png)

This repository contains code for predicting the price of gold using a Random Forest Regressor model. The following libraries are used in this project:

- matplotlib.pyplot for data visualization.
- seaborn for data visualization.
- sklearn.model_selection.train_test_split for splitting the data into training and testing sets.
- sklearn.ensemble.RandomForestRegressor for training and testing the machine learning model.
- sklearn.metrics for evaluating the model's performance.

<br/> The model was trained on a dataset containing information about the stock market, oil prices, and exchange rates in addition to the price of gold. The dataset has 5 columns: Date, S&P 500 Index (SPX), Gold (GLD), United States Oil Fund (USO), Silver (SLV), and Euro to US Dollar exchange rate (EUR/USD).

<br/>After training and testing the model, the r2 score was found to be 0.9999, indicating that the model performs very well in predicting the price of gold.

<br/> To run this project, simply clone the repository and run the Python file. The model will be trained on the provided dataset and the predicted gold prices will be displayed.





