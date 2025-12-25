# Stock-market-pred-model


## Stock Market Prediction using Bidirectional LSTM
This project implements a Deep Learning solution to predict the closing prices of major technology stocks. It leverages Long Short-Term Memory (LSTM) networks, a type of Recurrent Neural Network (RNN) capable of learning long-term dependencies, making it ideal for time-series forecasting like stock market trends.🚀 OverviewThe model predicts the stock prices of four tech giants:Apple (AAPL)Google (GOOGL)Microsoft (MSFT)Amazon (AMZN)By integrating historical price data with technical indicators, the project explores how deep learning can capture complex patterns in financial markets.


### Tech StackLanguage:
Python 🐍Deep Learning: TensorFlow, KerasData Manipulation: Pandas, NumPyTechnical Analysis: ta library (Technical Analysis Library)Data Source: Yahoo Finance (yfinance)Visualization: Matplotlib, Seaborn, Plotly (for interactive charts)Scaling: Scikit-learn (MinMaxScaler)


### Key FeaturesAutomated Data Collection:
Fetches real-time historical data directly from Yahoo Finance for the period 2018–2023.Feature Engineering: Beyond just using raw prices, the project utilizes the ta library to generate technical indicators (like RSI, MACD, and Bollinger Bands) to provide the model with better market context.Advanced Architecture: Implements a Bidirectional LSTM model. This allows the network to have backward and forward information about the sequence at every time step, improving prediction accuracy.Robust Training: Uses EarlyStopping to prevent overfitting and ReduceLROnPlateau to fine-tune the learning rate during training.Performance Metrics: Evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and the $R^2$ score.


### Results & Visualizations
The project includes interactive Plotly visualizations that compare:Actual vs. Predicted Prices: A clear line chart showing how closely the model tracks real market movements.Market Trends: Insights into stock volatility and growth over the 5-year period.⚙️ 

👤 Author : Meet Kuber Student & AI/ML Enthusiast(https://www.linkedin.com/in/meetkuber/)
