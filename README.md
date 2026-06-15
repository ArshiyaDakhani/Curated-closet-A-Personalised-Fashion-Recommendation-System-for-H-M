# Curated Closet: Personalized Fashion Recommendation System for H&M

## Master's Thesis Project

A machine learning-powered fashion recommendation system developed using the H&M Personalized Fashion Recommendations dataset. This project leverages collaborative filtering and cosine similarity techniques to generate personalized product recommendations based on customer behavior, transaction history, and product metadata.

**Author:** Arshiya Dakhani  
**Degree:** MSc Business Analytics  
**Institution:** Dublin Business School  
**Year:** 2024

---

## Project Overview

Online fashion retailers manage millions of products and customer interactions every day. Traditional recommendation systems often struggle to adapt to rapidly changing fashion trends, seasonal demand, and individual customer preferences.

This research develops a personalized recommendation engine for H&M that predicts relevant fashion products for customers based on:

- Historical purchase behavior
- Product characteristics
- Customer demographics
- Transaction patterns

The goal is to improve customer experience, engagement, and product discovery through intelligent recommendations.

---

## Research Question

How can machine learning be used to predict the top product recommendations for each customer within a 7-day interval, resulting in a dynamic and personalized recommendation system for H&M?

---

## Objectives

- Develop a personalized recommendation system for H&M
- Analyze customer purchasing behavior
- Generate top product recommendations
- Evaluate recommendation performance using standard metrics
- Improve customer satisfaction through personalization

---

## Dataset

Source:
H&M Personalized Fashion Recommendations Dataset (Kaggle)

Dataset Components:

- articles.csv
- customers.csv
- transactions_train.csv
- Product images

Dataset Statistics:

| Dataset | Records |
|----------|----------|
| Articles | 105,542 |
| Customers | 1,371,980 |
| Transactions | 31,788,320 |

---

## Methodology

### Data Preparation

- Data cleaning
- Missing value handling
- Feature engineering
- Data transformation
- Customer-product interaction matrix generation

### Machine Learning Models

#### Collaborative Filtering

Learns customer preferences from historical purchase patterns and recommends products purchased by similar users.

#### Cosine Similarity

Calculates similarity between products and customers based on interaction vectors and product attributes.

### Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Development
5. Model Training
6. Recommendation Generation
7. Performance Evaluation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Evaluation Metrics

The recommendation models were evaluated using:

- Precision
- Recall
- F1-Score
- Mean Average Precision (MAP)

These metrics assess recommendation relevance and ranking quality.

---

## Key Findings

- Successfully developed a personalized recommendation framework for fashion retail.
- Collaborative filtering effectively captured customer purchasing behavior.
- Cosine similarity improved product relevance by identifying similar products.
- Personalized recommendations have the potential to improve customer engagement and increase sales.

---

## Project Structure

project/

├── data/

│ ├── articles.csv

│ ├── customers.csv

│ └── transactions_train.csv

│

├── notebooks/

│ ├── EDA.ipynb

│ ├── Collaborative_Filtering.ipynb

│ └── Recommendation_System.ipynb

│

├── src/

│ ├── preprocessing.py

│ ├── recommendation_engine.py

│ ├── evaluation.py

│ └── utils.py

│

├── images/

│ ├── workflow.png

│ ├── age_distribution.png

│ └── recommendations.png

│

├── thesis.pdf

├── requirements.txt

└── README.md

---

## Results

### Exploratory Data Analysis

Insights generated from:

- Customer age distribution
- Product category distribution
- Purchase frequency analysis
- Product popularity trends

### Recommendation Output

The system generates personalized product recommendations by analyzing customer interactions and product similarity.

Example:

Customer → Historical Purchases

↓

Recommendation Engine

↓

Top Recommended Fashion Products

---

## Ethical Considerations

This project considers:

- User privacy
- GDPR compliance
- Fair recommendation practices
- Algorithmic transparency
- Bias mitigation

---

## Future Improvements

- Deep Learning Recommendation Models
- Reinforcement Learning Approaches
- Real-time Recommendation Engine
- Image-Based Fashion Similarity
- Hybrid Recommendation Systems

---

## Thesis

The full dissertation is available in this repository as:

Research.pdf

---

## License

This project is published for academic and portfolio purposes.

---

