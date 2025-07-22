
# 🛍️ Sentiment Analysis of Amazon Product Reviews – All Beauty Category

## 📌 Project Overview

This project analyzes customer reviews in the Amazon "All Beauty" product category. By using sentiment analysis techniques, we explore how customers express satisfaction or dissatisfaction and identify how product metadata (like price and verification status) influences sentiment.

## 🎯 Objectives

- Classify reviews into positive, neutral, and negative based on star ratings.
- Explore the relationship between sentiment and price.
- Compare sentiment trends across verified vs. unverified purchases.
- Visualize review activity over time.
- Prepare data for future machine learning modeling.

## 📂 Dataset Description

The dataset was sourced from the [McAuley Lab Amazon Reviews 2023](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023) collection via Hugging Face. It includes:

- Review text and title
- Star ratings (1–5)
- Timestamps
- Verified purchase status
- Product metadata (price, description, category)

## 🔍 Exploratory Analysis Highlights

- Distribution of ratings and sentiments
- Sentiment comparison by purchase type
- Price analysis by sentiment
- Review activity trends over months


## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- spaCy (for NLP preprocessing)
- Hugging Face datasets
- Google Colab

## 📈 Future Work (Phase 2)

- Train a sentiment classification model using review text
- Extend analysis to other Amazon categories (e.g., Electronics, Books)
- Evaluate NLP pipelines and classification performance
- Publish results in a GitHub repository and Kiggle

