# esg-news-prediction-and-trading
# ESG News Prediction and Trading

This project presents a full pipeline for ESG (Environmental, Social, Governance) signal extraction and investment strategy generation based on financial news using NLP models and LSTM networks.

## 📊 Overview

This repository contains all the notebooks, models, and data pipelines developed as part of a master's thesis focused on building a **dynamic ESG scoring system** and a **signal-based investment algorithm**, using:

- **Natural Language Processing (NLP)** with RoBERTa and LLMs (GPT-4o)
- **LSTM** networks for time series forecasting of ESG scores
- **Streamlit app** for ESG score dashboards and signal simulation
- **Vertex AI** for scalable model training and deployment

## 📁 Repository Structure

## 🧠 Notebooks Summary

### 🔍 NLP - ESG Classification
- `01_LONGCHAIN.ipynb`: ESG vs. Non-ESG classification using LangChain + GPT.
- `02_ROBERTA_ESG_OR_NOT.ipynb`: Fine-tuning RoBERTa for ESG detection.
- `03_INFERENCE_ROBERTA_1.ipynb`: Batch inference on the full news corpus.

### 📂 ESG Category Assignment
- `04_LONGCHAIN_2.ipynb`: LLM-based labeling (Environmental / Social / Governance).
- `05_ROBERTA_E_S_G.ipynb`: RoBERTa classifier for ESG category.
- `06_INFERENCE_ROBERTA_2.ipynb`: Full corpus classification (E/S/G).

### 💬 Sentiment Analysis
- `07_LONGCHAIN_3.ipynb`: Sentiment tagging (bullish/bearish/neutral).
- `08_SENTIMENT_ANALYSIS.ipynb`: RoBERTa + Attention model for ESG sentiment.

### 🧼 Data Engineering
- `09_DATA_PREPARATION.ipynb`: Cleaning, ticker matching, and sector filling.
- `10_MEDIA_REPUTATION.ipynb`: Weighting sources based on frequency.
- `11_DATA_EXPLORATION.ipynb`: Exploratory data analysis of ESG patterns.

### 🧠 LSTM Modeling
- `12_EMBEDING_GENERATION.ipynb`: Creating daily news embeddings.
- `13_WINDOW_GENERATION.ipynb`: Sliding window creation.
- `14_MATCHING_WINDOWS.ipynb`: Labeling windows with ESG scores.
- `15_LSTM_TRAINNING.ipynb`: LSTM autoregressive model for ESG prediction.

### 🧾 Final Dataset & Trading
- `16_COMPLETE_DATASET.ipynb`: Full ESG time series creation.
- `17_COMPLETE_DATASET_2.ipynb`: Refinement and interpolation.
- `18_TRADING_ALGO.ipynb`: Signal generation, execution, and backtesting.

### 📊 Streamlit Dashboard
- `19_STREAMLIT.ipynb`: ESG dashboard with score visualizations.
- `20_STREAMLIT_2.ipynb`: Signal simulation and comparison with benchmark.

