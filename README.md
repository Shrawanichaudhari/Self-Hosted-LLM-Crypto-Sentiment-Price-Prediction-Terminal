# 🚀 Self-Hosted Crypto Intelligence Terminal
**NMIMS INNOVATHON 2026 | Challenge 2: AI & Data Intelligence**

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://self-hosted-llm-crypto-sentiment-price-prediction-terminal-kjf.streamlit.app/)
**Live Demo:** [https://self-hosted-llm-crypto-sentiment-price-prediction-terminal-kjf.streamlit.app/](https://self-hosted-llm-crypto-sentiment-price-prediction-terminal-kjf.streamlit.app/)
## **ScreenShots of Dashboard:**
<img width="1366" height="654" alt="Screenshot 2026-04-30 161538" src="https://github.com/user-attachments/assets/5b6a8812-9f02-4f1e-80fd-0c8c44239139" />

Lets select BTC for Analytics

<img width="1366" height="651" alt="Screenshot 2026-04-30 161632" src="https://github.com/user-attachments/assets/33428dcf-082c-491f-9b53-927b743a0ae6" />

Sentiment Price Divergence

<img width="1092" height="496" alt="Screenshot 2026-04-30 161725" src="https://github.com/user-attachments/assets/87c6cfee-8d18-4ac7-825c-d611deeac753" />

24-Hour Price Forecast (ARIMA Time Series)

<img width="1070" height="580" alt="Screenshot 2026-04-30 162042" src="https://github.com/user-attachments/assets/c039086b-1db4-434c-939a-039711d52cdb" />


<img width="1084" height="608" alt="Screenshot 2026-04-30 162112" src="https://github.com/user-attachments/assets/fab4b7e9-1f1a-4118-8f98-1ffa39ad373b" />


<img width="1043" height="577" alt="Screenshot 2026-04-30 162237" src="https://github.com/user-attachments/assets/01a9fc53-67ed-4fce-a220-2e977d8674c1" />


<img width="1137" height="580" alt="Screenshot 2026-04-30 162259" src="https://github.com/user-attachments/assets/0647f96f-3d4c-40d4-a3f4-082d23b6fefd" />




## 1. Executive Summary
A full-stack trading intelligence terminal using **locally-hosted LLMs (Mistral 7B)** to analyze social sentiment and **Prophet** for time-series forecasting. [cite_start]The system provides real-time, explainable trading signals without relying on expensive cloud APIs[cite: 19, 20].

## 2. Technical Architecture

- [cite_start]**Data Ingestion**: Real-time pipelines for Binance (Price), Reddit (Sentiment), and Etherscan (Whale Alerts)[cite: 44].
- [cite_start]**Sentiment Engine**: Ollama-powered Mistral 7B using few-shot prompting for 75% accuracy[cite: 50, 51].
- [cite_start]**Price Forecasting**: Facebook Prophet model for 1h, 4h, and 24h directional prediction[cite: 60].
- [cite_start]**UI**: High-performance Streamlit dashboard for real-time visualization[cite: 83].

## 3. Performance Metrics
- [cite_start]**Target Directional Accuracy**: >55%.
- **Backtest Win Rate**: Tracked via 30-day historical simulation.
- [cite_start]**Latency**: Local LLM inference < 2 seconds on 16GB RAM[cite: 93].

## 4. Setup Instructions
1. Install [Ollama](https://ollama.com) and run `ollama pull mistral`.
2. Clone this repo and install dependencies: `pip install -r requirements.txt`.
3. Configure your API keys in the `.env` file.
4. Launch the terminal: `streamlit run terminal.py`.
