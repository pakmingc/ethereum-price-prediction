# Ethereum Price Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pakmingc/ethereum-price-prediction/blob/main/Ethereum_price_prediction.ipynb)

This project aims to predict the future price of Ethereum using historical price data and advanced data science techniques. The prediction focuses on the period from 2024 to 2027.

## Project Overview

The project involves the following key steps:

1. Data Mining: Collecting historical price data for Ethereum from Yahoo Finance.
2. Exploratory Data Analysis (EDA): Exploring price trends, volatility, and the relationship between price and trading volume.
3. Model Development: Building a predictive model using TensorFlow and Long Short-Term Memory (LSTM) neural networks.
4. Results and Interpretation: Evaluating the model's performance and interpreting the price predictions.

## Requirements

To run the code in this repository, you need the following dependencies:

- Python 3.x
- TensorFlow
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yfinance

You can install the required packages using pip:

## Usage

1. Clone this repository to your local machine or download the Colab program file.
2. Install the required dependencies.
3. Run the Colab program file to execute the code.
4. The program will download the historical price data, perform exploratory data analysis, train the LSTM model, and generate price predictions for Ethereum from 2024 to 2027.

## Results

The LSTM model achieved an MSE of 0.0002 and an RMSE of 0.0145 on the test data, indicating a good fit to the data. The model's predictions closely align with the actual prices, diverging by an average of 0.0097 units.

Please refer to the Colab program file for detailed code and visualizations.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

If you have any questions or need further assistance, please feel free to contact the project maintainer at pakmingc2@gmail.com

## License

This project is licensed under the [MIT License](LICENSE).
