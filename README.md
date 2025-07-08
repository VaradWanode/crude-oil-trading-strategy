# crude-oil-trading-strategy
# Crude Oil Trading Strategy using Python

## 📈 Overview
A simplified commodity trading strategy for Crude Oil built using Python. It generates Buy/Sell signals based on technical indicators (RSI, MACD) and daily news sentiment.

## 🔧 Tools Used
- Python (Pandas, NumPy)
- TextBlob (NLP sentiment)
- Matplotlib (Visualization)
- Google Colab (Development)

## 💡 Strategy Logic
- **Buy Signal:** RSI < 50, MACD > Signal Line, Sentiment ≥ 0
- **Sell Signal:** RSI > 50, MACD < Signal Line, Sentiment ≤ 0

## 📊 Output
Price plotted with Buy (▲) and Sell (▼) signals clearly marked on the time series chart.

## 🧠 Future Work
- Integrate real news data using APIs (e.g., NewsAPI)
- Backtest performance vs benchmark
- Extend to other asset classes
