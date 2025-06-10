##  Mashable News Shares - Data Analysis
**Period**: March 2025 – June 2025  
**Goal**: Practice structured data analysis and explore what features boost online news shares.
**Link**: [My Kaggle code](https://www.kaggle.com/code/sharon305/structured-data-practicing)

---

### Description
**Main Question**:  
Which features have the most impact on the number of news article shares?

This project applies several classification models to identify influential features:

- 🌳 Decision Tree  
- 🌲 Random Forest  
- 🚀 XGBoost  
- 💡 LightGBM

---

### Resource
- **Source**: UCI Online News Popularity Data Set  
- **Link**: [Kaggle Dataset](https://www.kaggle.com/datasets/thehapyone/uci-online-news-popularity-data-set/data?select=OnlineNewsPopularity.csv)

---

### Language & Tools
* Python
* pandas, scikit-learn, xgboost, lightgbm, matplotlib, seaborn

---

### Outcome
* **Accuracy**: 0.69 
* **Top 5 Important Features** (based on feature importance):
  1. `data_channel_is_entertainment`: 42.57 
  2. `data_channel_is_tech`: 37.04
  3. `data_channel_is_world`: 33.85
  4. `kw_avg_avg`: 29.74
  5. `data_channel_is_socmed`: 28.35
  6. `is_weekend`: 28.28

> According to the results, the data channel categories have the greatest impact on the number of shares, especially the *entertainment*, *tech*, *world* and *social media* channels.

---

### Author

- [Sharon](https://github.com/hchh6453)
