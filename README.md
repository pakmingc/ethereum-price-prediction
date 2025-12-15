# 📊 Ethereum Price Prediction

<div align="center">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pakmingc/ethereum-price-prediction/blob/main/Ethereum_price_prediction.ipynb)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

**LSTM Neural Network for Cryptocurrency Price Forecasting**

</div>

---

## 🎯 Project Overview

This project uses deep learning (LSTM) to predict Ethereum price movements. The model is trained on historical price data from Yahoo Finance and generates forecasts for future price trends.

### 📈 Model Performance

| Metric | Value |
|--------|-------|
| MSE | 0.0002 |
| RMSE | 0.0145 |
| Mean Deviation | 0.0097 units |

---

## 🔧 Pipeline

```
📥 Data Mining          →  Historical ETH prices from Yahoo Finance
📊 Exploratory Analysis →  Trends, volatility, volume correlation
🧠 Model Training       →  LSTM neural network (TensorFlow/Keras)
📈 Prediction           →  Future price forecasting
```

---

## ✨ Features

- 🔄 **Automated Data Fetching** - Pull latest prices via yfinance
- 📉 **Technical Analysis** - Price trends, volatility patterns, volume correlation
- 🧠 **LSTM Model** - Sequential neural network for time series
- 📊 **Visualization** - Matplotlib/Seaborn charts for analysis
- 🚀 **Colab Ready** - One-click notebook execution

---

## 🛠️ Tech Stack

```
Python 3.x
├── TensorFlow / Keras   # Deep learning framework
├── Pandas / NumPy       # Data manipulation
├── Matplotlib / Seaborn # Visualization
└── yfinance             # Market data API
```

---

## 🚀 Quick Start

### Option 1: Google Colab (Recommended)

Click the **Open in Colab** badge above to run instantly.

### Option 2: Local Setup

```bash
# Clone repository
git clone https://github.com/pakmingc/ethereum-price-prediction.git
cd ethereum-price-prediction

# Install dependencies
pip install tensorflow pandas numpy matplotlib seaborn yfinance

# Run notebook
jupyter notebook Ethereum_price_prediction.ipynb
```

---

## 📁 Project Structure

```
ethereum-price-prediction/
├── Ethereum_price_prediction.ipynb  # Main notebook
├── README.md                        # Documentation
└── LICENSE                          # MIT License
```

---

## 📊 What the Notebook Generates

- 📈 Historical price charts
- 📉 Volatility analysis
- 🔮 Prediction vs actual comparison
- 📊 Model training loss curves

---

## 🧠 Model Architecture

```
Input Layer (60 time steps)
    ↓
LSTM Layer (50 units, return_sequences=True)
    ↓
Dropout (0.2)
    ↓
LSTM Layer (50 units)
    ↓
Dropout (0.2)
    ↓
Dense Layer (25 units)
    ↓
Output Layer (1 unit - predicted price)
```

---

## ⚠️ Disclaimer

This project is for **educational purposes only**. Cryptocurrency markets are highly volatile. Do not use this model for actual trading decisions.

---

## 🤝 Contributing

Contributions welcome! Feel free to open issues or submit pull requests.

---

## 📫 Contact

📧 pakmingc2@gmail.com

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.
