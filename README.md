# Amazon Baby Product Reviews – AI Sentiment Analysis

**Expertise:** Python, NLP, AI (RoBERTa), Sentiment Analysis, Data Analysis, Visualization

## Project Overview
This project applies AI-based sentiment analysis to Amazon Baby product reviews (~183K records).  
The goal is to understand how AI models capture customer sentiment compared to star ratings and simpler text-based methods.

### Key Steps:
- Data cleaning and preprocessing (~183K reviews)  
- Sampling 2,000 reviews for model testing  
- Applying RoBERTa transformer for sentiment classification (Positive / Negative / Neutral)  
- Comparing AI sentiment vs original ratings using evaluation metrics  
- Generating visualizations to highlight sentiment distribution and review insights  

### Key Findings
- AI Sentiment Model (RoBERTa) performed better on negative reviews than text-based approaches  
- Text-based methods captured positive reviews more accurately  
- Neutral sentiment remains challenging for both methods  

**Agreement with star ratings:**

| Sentiment | AI  | Text-based |
|-----------|-----|------------|
| Positive  | 91% | 96%        |
| Negative  | 71% | 42%        |
| Neutral   | 21% | 09%        |

## Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn)  
- HuggingFace Transformers (RoBERTa)  
- Seaborn / Matplotlib for visualization  
- **Google Colab** for cloud execution and running AI models  

## Files in This Repo
- `AI_Sentiment_BabyReviews.ipynb` → Jupyter Notebook for AI Sentiment Analysis (developed in **Google Colab**)  
- `Sanchal_Amazon_Sentiment.csv` → Sample processed results (2,000 reviews)  
- `requirements.txt` → Python dependencies  

## Key Learning
- AI models capture nuance better than simple text-based methods but still struggle with neutral reviews  
- Text-based methods are simpler but limited in capturing complexity  
- Validating AI predictions against ground truth (ratings) is crucial  

## Next Steps
- Expand model testing to the full dataset (~183K reviews)  
- Compare with other transformer models (BERT, DistilBERT)  
- Experiment with preprocessing techniques to improve neutral sentiment detection  

## Interactive Dashboard
Tableau Dashboard Link: 
https://public.tableau.com/app/profile/sanchal.sunil.dhurve/viz/Amazon_baby_Products_Review_Analysis/AmazonBabyProductsReviewsAnalysis
