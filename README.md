# STATS 507 Final Project: Sentiment Analysis Across Domains

**Author**: Yuxin Zhao  
**Model**: distilbert-base-uncased-finetuned-sst-2-english  
**Datasets**: amazon_polarity, tweet_eval (via Hugging Face)

## 🔍 Project Overview

This project compares the performance of a pretrained sentiment classifier across two domains: Amazon product reviews and Twitter posts. We analyze predicted sentiment distribution, model confidence, and classification accuracy.

## 📁 Files

- `final_project.ipynb`: Main code notebook
- `sentiment_with_predictions.csv`: Output data with predicted sentiment
- `figure1.png`, `figure2.png`, `figure3.png`: Figures used in the final report
- `Final_Project_Report.pdf`: 2-page project report

## ⚙️ Environment

- Python 3.9+
- transformers
- datasets
- pandas, matplotlib, seaborn

Install with:
```bash
pip install transformers datasets pandas matplotlib seaborn
