# CryptoTrade: A Reflective LLM-based Agent for Real-Time Bitcoin & Ethereum Trading

This project implements a lightweight, explainable crypto trading assistant powered by Google's Gemini 1.5 Flash LLM. It replicates and extends the ideas from the original **CryptoTrade** paper, focusing on real-time decision-making using sentiment analysis, live market data, and prompt-based explainability.

##  Project Overview

The agent makes Buy/Hold/Sell decisions for Bitcoin based on:
- Latest crypto news headlines (via [GNews API](https://gnews.io))
- Live Bitcoin price and change percentage (via [CoinGecko API](https://www.coingecko.com/en/api))
- Sentiment analysis using TextBlob
- Prompt-based explainable reasoning using Gemini LLM (via [Google Generative AI SDK](https://ai.google.dev))

The project includes:
- Autonomous agent for daily decisions
- Interactive agent for manual queries
- Explainable AI integration with step-by-step reasoning
- Qualitative validation metrics (latency, consistency, output clarity)

---

##  Technologies Used

- Python 3.9
- Google Gemini (via `google-generativeai`)
- TextBlob for sentiment scoring
- GNews + CoinGecko API
- Jupyter Notebook (PoC + Evaluation)

---

## 📚 Credit & Citation

This implementation is inspired by the original CryptoTrade paper:

**Li, Y., Luo, B., Wang, Q., Chen, N., Liu, X., He, B.**  
*CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading.*  
Presented at EMNLP 2024.  
[arXiv Paper](https://arxiv.org/abs/2402.01966)  
[Official GitHub Repository](https://github.com/Xtra-Computing/CryptoTrade)


