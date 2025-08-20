# Day 3 Progress

## 1. Discussion on Day 2 Question
- We discussed whether one data source is enough to make a model generalize or if multiple data sources are better.  
- Conclusion:  
  - A single source can work if it is very large and diverse, but it usually carries inherent biases.  
  - Multiple sources improve generalization by adding diversity, reducing dataset bias, and making the model more robust to unseen real-world scenarios.  
- A model trained only on one source may perform well on similar data but will likely struggle when applied to different leagues, regions, or conditions.

## 2. Further Data Exploration – Social Media Sentiment (Twitter API)
- Started exploring **Twitter API** (X API) for collecting tweets mentioning players.  
- Objective: Use Natural Language Processing (NLP) for sentiment analysis.  
- Tools and approaches:  
  - Libraries: `tweepy` or `snscrape` for fetching tweets.  
  - Sentiment analysis: Using **VADER** or **TextBlob** to quantify sentiment scores (positive, neutral, negative).  
- Importance:  
  - Public and fan sentiment impacts a player’s market value.  
  - Sentiment features (popularity, media hype, controversies) will be integrated into the prediction model.  

## 3. Question for Day 4
- **Which will generalize the model better: huge data with less diversity, or small data with high diversity? Why?**
