# Google Stock Predictor

This project aims to predict Google's stock prices using a Long Short-Term Memory (LSTM) neural network. The model is trained on historical stock price data and can predict future stock prices based on past trends.

## Project Overview

The project includes the following steps:
1. Data Preprocessing: Loading and cleaning historical stock price data.
2. Feature Scaling: Normalizing the data to ensure the model performs well.
3. Creating Sequences: Preparing data sequences to feed into the LSTM model.
4. Building the Model: Constructing the LSTM neural network.
5. Training the Model: Training the model on historical data.
6. Predicting and Visualizing: Making predictions on test data and visualizing the results.

## Dataset

The dataset used for this project includes historical stock prices for Google from 2004 to 2024. The data is split into training and testing datasets:
- `Google_train_dataset.csv`
- `Google_test_dataset.csv`

## Dependencies

The project requires the following Python libraries:
- numpy
- pandas
- matplotlib
- scikit-learn
- keras
- tensorflow

You can install the required libraries using the following command:

```sh
pip install numpy pandas matplotlib scikit-learn keras tensorflow
```

## Usage

1. Clone the repository:

```sh
git clone https://github.com/your-username/google-stock-predictor.git
```

2. Navigate to the project directory:

```sh
cd google-stock-predictor
```

3. Run the Jupyter Notebook or Python script:

```sh
jupyter notebook stock_predictor.ipynb
# or
python stock_predictor.py
```

## Code Explanation

### Data Preprocessing

The data preprocessing step involves loading the CSV files, converting the 'Close' prices to numeric values, handling missing values, and scaling the features.

### Building and Training the Model

The LSTM model is built using the Keras library. The model consists of multiple LSTM layers with dropout regularization to prevent overfitting. The model is trained on the training dataset.

### Making Predictions

The trained model is used to make predictions on the test dataset. The results are then plotted to visualize the actual vs. predicted stock prices.

### Visualization

Matplotlib is used to plot the actual and predicted stock prices, showing the model's performance visually.

## Results

The model's performance can be evaluated by comparing the predicted stock prices with the actual stock prices on the test dataset. 

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgements

- This project uses historical stock price data from Yahoo Finance.
- Thanks to the Keras and TensorFlow teams for their excellent libraries.

```
