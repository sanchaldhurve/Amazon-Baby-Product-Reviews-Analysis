# Amazon Baby Product Reviews – AI Sentiment Analysis  

**Expertise:** Python, NLP, AI (RoBERTa), Sentiment Analysis, Data Analysis, Visualization  

---

## Project Overview  
This project applies **AI-based sentiment analysis** to Amazon Baby product reviews (~183K records).  
The goal was to understand how well AI models capture customer sentiment compared to star ratings and simpler text-based methods.  

Key steps included:  
- Data cleaning and preprocessing (~183K reviews)  
- Sampling 2,000 reviews for faster model testing  
- Applying **RoBERTa transformer model** for sentiment classification (Positive / Negative / Neutral)  
- Comparing AI sentiment vs original ratings using evaluation metrics  
- Generating visualizations to highlight sentiment distribution and review insights  

---

## Key Findings  
- **AI Sentiment Model (RoBERTa)** performed better on **negative reviews** than text-based approaches  
- **Text-based methods** captured **positive reviews** more accurately  
- Both approaches **struggled with neutral sentiment** (often misclassified)  

Example agreement with star ratings:  
- Positive → **91% (AI) vs 96% (Text-based)**  
- Negative → **71% (AI) vs 42% (Text-based)**  
- Neutral → **21% (AI) vs 09% (Text-based)**  

---

##  Tools & Libraries  
- **Python** (Pandas, NumPy, Scikit-learn)  
- **HuggingFace Transformers** (RoBERTa model)  
- **Seaborn / Matplotlib** for visualization  
- **Google Colab** for cloud execution  

---

## Files in This Repo  
- `AI_Sentiment_BabyReviews.ipynb` → Jupyter Notebook for AI Sentiment Analysis  
- `Sanchal_Amazon_Sentiment.csv` → Processed sample results (2,000 reviews)  
- `requirements.txt` → Python dependencies  

---

## Key Learning  
This project demonstrated the importance of **validating AI models against ground truth** (ratings) rather than assuming predictions are reliable.  
- Text-based methods = simple but limited nuance  
- AI = better at complexity but still fails on neutral tone  
- Neutral classification remains a challenge in sentiment analysis  

---

## Next Steps  
- Expand model testing to the full dataset (~183K reviews)  
- Compare with other transformer models (BERT, DistilBERT)  
- Try different preprocessing techniques for better neutral detection  

