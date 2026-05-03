#  News Recommendation using Contextual Bandits

##  Overview
This project implements a news recommendation system using contextual bandit algorithms on the Microsoft News Dataset (MIND). The goal is to recommend relevant news articles to users by learning from their interactions (click / no-click) while balancing exploration and exploitation.

---

##  Approaches

This project is implemented in two ways:

###  Basic Model
- Uses user history and news embeddings  
- Simple feature representation  
- Acts as a baseline model  

###  Enhanced Model
- Includes entity embeddings  
- Includes date-time features  
- Provides richer context and better personalization  

---

##  Algorithms Used
- Epsilon-Greedy  
- UCB (Upper Confidence Bound)  
- Thompson Sampling  
- LinUCB  
- Disjoint LinUCB  

---

##  Evaluation Metrics
- AUC  
- MRR  
- nDCG@5  
- nDCG@10  
- CTR (Click-Through Rate)  

---

##  Dataset
Microsoft News Dataset (MIND - Small)

Includes:
- User behavior logs (click history)  
- News metadata (title, category, entities)
- Entity Embedding vector file

**Note: During development, some parts of this project were executed on Google Colab due to occasional kernel crashes on my local machine. The code has since been adjusted to run on a local environment. However, if any issues occur during execution, they may be related to system or environment differences. Please feel free to reach out for clarification or assistance.- 
**
