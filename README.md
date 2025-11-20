ESG-Driven Stock Prediction:

This project predicts next-day stock movement by integrating ESG sentiment, topic modeling, and technical market indicators.
It combines ESG text data with OHLCV stock prices, extracts ESG topics using BERTopic, computes technical indicators (MACD, RSI, Bollinger Bands, OBV), 
and trains machine learning models such as LightGBM and XGBoost to understand how ESG signals influence short-term market behavior

Features:

ESG Sentiment Integration: Merges multi-platform ESG sentiment data to capture real-world discussions influencing investor behavior.

Advanced Topic Modeling - Uses BERTopic to uncover latent ESG themes correlated with market reactions.

Technical Indicator Engineering -Computes trend, momentum, volume, and volatility indicators (MACD, RSI, Bollinger Bands, OBV, etc.).

Multi-Source Data Fusion - Aligns ESG signals with historical stock prices collected from Yahoo Finance.

Machine Learning Models -Trains LightGBM and XGBoost classifiers to predict next-day market direction.

Explainability- Identifies which ESG themes and technical indicators most influence predictions.

Project Workflow:

Load & preprocess ESG sentiment files

Download OHLCV stock data using yfinance

Engineer technical indicators using ta

Apply BERTopic for ESG theme extraction

Merge all features into a unified dataset

Train ML models (LightGBM/XGBoost)

Evaluate prediction accuracy & feature importance

Objective:

To demonstrate how ESG-driven sentiment and topic trends can be combined with financial indicators to create a more context-aware stock prediction system, improving short-term market forecasting for research and quant applications.
