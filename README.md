# Stock Price Prediction Model

This project implements deep learning models for forecasting Microsoft stock prices using historical data. It explores two approaches: a basic LSTM model and a more advanced model leveraging transfer learning techniques.

## Features

- **Data Preprocessing**: Handling historical stock data, including scaling and sequence creation for time-series forecasting.
- **Basic LSTM Model**: A baseline Recurrent Neural Network (RNN) using Long Short-Term Memory (LSTM) units to predict future stock closing prices.
- **Transfer Learning Approach**: A pre-trained deep recurrent neural network approach (inspired by research on time series classification) to potentially improve prediction accuracy.
- **Visualization**: Plotting actual vs. predicted stock prices to visually assess model performance.

## Dataset

The project uses Microsoft (MSFT) historical stock data (`microsoft_stock_data.csv`), covering daily open, high, low, close, and volume metrics.

## Installation

1.  Clone the repository:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

The project consists of two main Jupyter Notebooks:

1.  **`basic-lstm-least-accuracy.ipynb`**: Contains the implementation of the basic LSTM model. This serves as a baseline for performance.
2.  **`tranfer-better-accuracy.ipynb`**: Implements the transfer learning strategy, pre-training on synthetic data (sine waves) before fine-tuning on the actual stock data.

To run the project, launch Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

Open the desired notebook and run the cells sequentially to train the models and visualize the predictions.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- tensorflow

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
