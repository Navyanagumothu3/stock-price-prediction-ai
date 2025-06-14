# 📈 Stock Price Prediction using Machine Learning

This project is an AI-based system to predict stock price movement (up/down) using historical stock data. It uses machine learning algorithms like Logistic Regression, SVM, and XGBoost, and includes feature engineering with technical indicators such as SMA, EMA, RSI, Bollinger Bands, and more.

## 📂 Dataset

The dataset used is from **ADANIPORTS** stock and includes:
- Date-wise Open, High, Low, Close prices
- Volume
- VWAP (Volume Weighted Average Price)

## 🧠 Algorithms Used

- Logistic Regression
- Support Vector Machine (SVM with polynomial kernel)
- XGBoost Classifier

## 📊 Features Engineered

- Simple Moving Averages (SMA)
- Exponential Moving Averages (EMA)
- Momentum and ROC
- Bollinger Bands (Upper, Lower, Std)
- RSI (Relative Strength Index)
- `Open - Close`, `Low - High`
- Quarter-end detection

## 🛠️ Technologies Used

- Python
- Jupyter Notebook (Google Colab)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `xgboost`, `scikit-learn`

## 📈 Results

- ROC AUC (Train): ~0.89
- ROC AUC (Validation): ~0.54+
- Model used: XGBoost
- Target: Binary classification of stock price movement

## 🗂️ File Structure

| File                         | Description |
|------------------------------|-------------|
| `ADANIPORTS.csv`             | Raw dataset |
| `Stock_Price_Prediction.ipynb` | Main notebook with full code, plots, training & evaluation |
| `requirements.txt`           | All Python dependencies |

## ▶️ How to Run

1. Clone the repo:
    ```bash
    git clone https://github.com/your-username/stock-price-prediction-ai.git
    cd stock-price-prediction-ai
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open and run the notebook:
    - `Stock_Price_Prediction.ipynb`

## 🙌 Acknowledgments

- Dataset: Sourced from stock exchange data (NSE/BSE)
- Technical Indicator Concepts: Investopedia

