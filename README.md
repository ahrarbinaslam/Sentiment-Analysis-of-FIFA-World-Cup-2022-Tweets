# Sentiment Analysis of Tweets During the 2022 FIFA World Cup 🏆

This project analyzes Twitter sentiments surrounding the 2022 FIFA World Cup held in Qatar. Using a dataset of over 22,500 tweets, we explore public opinion on the event through Natural Language Processing (NLP) techniques, aiming to uncover both the positive and negative sentiments shared by users.

## 📄 Project Overview
The 2022 FIFA World Cup drew significant global attention and, along with it, a vast array of public reactions on social media platforms like Twitter. This project utilized a dataset from Kaggle containing English-language tweets tagged with `#WorldCup2022`. By analyzing these tweets, we aimed to capture the emotional landscape surrounding the event, particularly noting the mix of enthusiasm for the tournament and concerns about human and migrant rights in Qatar.

## 📊 Dataset

- **Source**: Kaggle  
- **Size**: 22,524 English tweets with the hashtag `#WorldCup2022`  
- **Data Fields**: Tweet text, timestamp, and additional metadata  

## 🛠 Methods

We employed the following NLP techniques to analyze the dataset:

- **VADER Sentiment Analysis**: VADER (Valence Aware Dictionary and sEntiment Reasoner) was used to categorize tweets into positive, negative, or neutral sentiments.
- **Word Clouds**: Word clouds were generated to visualize the most frequently mentioned words in tweets, revealing common topics and sentiments around the event.

## 🔍 Findings

The sentiment analysis revealed a diverse range of public reactions to the 2022 FIFA World Cup:

- **Positive Sentiments**: Many tweets expressed excitement, support for teams, and appreciation for the game, reflecting the uplifting spirit typically associated with global sports events.
- **Negative Sentiments**: However, a significant portion of tweets conveyed negative sentiments, primarily in response to concerns about human rights issues in the host country, Qatar. These tweets highlighted public awareness and criticism regarding migrant rights and labor conditions.

## ✅ Conclusion

This project demonstrates how NLP can be leveraged to extract and interpret public emotions from large volumes of textual data. By applying sentiment analysis to social media data, we gain insights into public opinion and can better understand the societal impact of major events like the FIFA World Cup.

## 📚 Libraries

- **Natural Language Toolkit (NLTK)**
- **VADER Sentiment Analysis**
- **WordCloud** library for visualization
- **Matplotlib** for plotting
- **Pandas** for data analysis
- **Textacy** for text preprocessing
