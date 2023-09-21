# Predicting Indian Stock Prices with Stacked LSTM

If you find this project useful, don't forget to give it a star ⭐!

![Alt Text](https://github.com/XAheli/Predicting-Indian-Stocks-Price-with-Stacked-LSTM/raw/main/pred.png)


This Python project focuses on predicting Indian stock prices using a Stacked Long Short-Term Memory (LSTM) neural network model. It provides valuable insights into stock data for four prominent Indian companies: Reliance Industries, Tata Steel, HDFC Bank, and Infosys. Here's what you need to know:

## Project Highlights:

![The LSTM unit has four input weights (from the data to the input and three gates) and four recurrent weights (from the output to the input and the three gates). Peepholes are extra connections between the memory cell and the gates, but they do not increase the performance by much and are often omitted for simplicity. Image by Klaus Greff and colleagues as published in LSTM: A Search Space Odyssey](https://github.com/XAheli/Predicting-Indian-Stocks-Price-with-Stacked-LSTM/blob/main/lstm.png)
*The LSTM unit has four input weights (from the data to the input and three gates) and four recurrent weights (from the output to the input and the three gates). Peepholes are extra connections between the memory cell and the gates, but they do not increase the performance by much and are often omitted for simplicity. Image by Klaus Greff and colleagues as published in [LSTM: A Search Space Odyssey](https://arxiv.org/abs/1503.04069).*


### Stacked LSTM Model:
- **Sequential Model:** Utilizes Keras' Sequential model for building the LSTM architecture.
- **Stacked LSTM Layers:** Employs three LSTM layers stacked to capture intricate temporal patterns in stock prices.
- **Activation Functions:** Explores Swish activation for smoothness and improved performance.
- **Output Layer:** Features a dense output layer for continuous stock price prediction.

### Hyperparameter Tuning:
- **Optimization Functions:** Compares various functions like Adam, Nadam, Adagrad, and Adadelta for model training.
- **Epochs and Batch Size:** Experiment with different values to optimize training.
- **Dropout Layers:** Utilizes dropout layers to prevent overfitting and enhance generalization.

### Model Evaluation:
- Uses Root Mean Square Error (RMSE) to assess model performance, with an RMSE of approximately 25.99 as the benchmark.

## Exploratory Data Analysis (EDA):
### 1. Overview of All 4 Companies:
- Visualizes the closing prices of all four companies on a single plot.
- Offers insights into stock price trends over time.

### 2. Adjusted Close Price for Each Stock:
- Displays adjusted close prices for each stock via subplots.
- Provides historical performance snapshots.

### 3. Total Volume of Stock Traded Each Day:
- Depicts trading volume for each company over time.
- Reflects stock liquidity and investor interest.

### 4. Moving Average of Each Stock:
- Calculates and plots moving averages (10, 30, and 50 days) for each stock.
- Identifies trends and smoothes price fluctuations.

### 5. Daily Return:
- Computes and visualizes daily returns through line plots and histograms.
- Offers insights into daily price fluctuations and return distributions.

### 6. Correlation between Different Stocks & Closing Prices:
- Explores correlations between closing prices of the four companies.
- Uses scatter plots and correlation matrices to uncover relationships.

## Project Output:
This project provides an in-depth analysis of Indian stock data, from data collection to visualization and model development. It showcases the potential of LSTM neural networks in stock price prediction, with an RMSE benchmark of 25.99. Contributors are encouraged to fine-tune hyperparameters and apply diverse techniques to enhance model performance.

## How to Contribute:
1. Fork this repository.
2. Clone your forked repository to your local machine.
3. Create a new branch: `git checkout -b feature/your-feature-name`.
4. Make your contributions and commit changes: `git commit -m "Description of your changes"`.
5. Push your changes to your forked repository: `git push origin feature/your-feature-name`.
6. Open a Pull Request (PR) to this repository's main branch.
7. Describe your changes and their significance.

## References:
- [Keras Documentation](https://keras.io/)
- [Numpy Documentation](https://numpy.org/doc/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Yahoo Finance API (yfinance)](https://pypi.org/project/yfinance/)

Feel free to contribute, explore, and improve this project! Let's predict Indian stock prices together.

---

*Note: This project is under the [Apache License 2.0](LICENSE).*
