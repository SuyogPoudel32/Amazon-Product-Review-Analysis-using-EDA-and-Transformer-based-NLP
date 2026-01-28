# 📦 Amazon Product Review Analysis using NLP & EDA

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)   

Analyze **Amazon product reviews** using **Python**, **Pandas**, **Seaborn**, and **Transformer-based NLP** to extract actionable business insights from customer reviews.  

---

## 📌 Project Overview

This project aims to evaluate **customer satisfaction** and **brand perception** across Amazon product categories.  
It combines **Exploratory Data Analysis (EDA)** with **sentiment analysis** on review titles using a pre-trained transformer model (**DistilBERT**).  

Key goals:
- Explore product categories, pricing, ratings, and sales patterns
- Understand customer sentiment and satisfaction
- Assess brand health and perception
- Demonstrate real-world data cleaning, analysis, and NLP techniques

---

## 🗂 Dataset

**Source:** Amazon product dataset (Excel format)  

**Key Features:**
- Product category
- Price and discount
- Rating and number of reviews
- Review titles (text data)

⚠️ Note: The dataset may contain biased or incomplete customer reviews.

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas & NumPy** – data manipulation
- **Matplotlib & Seaborn** – data visualization
- **Hugging Face Transformers**
  - `distilbert-base-uncased-finetuned-sst-2-english`
- **Jupyter Notebook**

---

## 🔄 Workflow

1. **Data Loading & Overview**
   - Inspect dataset structure, data types, and missing values
2. **Data Cleaning**
   - Remove irrelevant columns
   - Handle missing or inconsistent values
   - Convert data types for analysis
3. **Exploratory Data Analysis (EDA)**
   - Category-wise product distribution
   - Rating and pricing patterns
   - Review volume analysis
4. **Sentiment Analysis (NLP)**
   - Apply transformer-based sentiment classification
   - Label reviews as **Positive** or **Negative**
5. **Insight Generation**
   - Category vs sentiment comparison
   - Customer satisfaction trends
   - Business insights & conclusions

---

## 🤖 Sentiment Analysis Approach

- **Model:** `distilbert-base-uncased-finetuned-sst-2-english`
- Classifies review titles into:
  - **Positive**
  - **Negative**
- Results analyzed across product categories to evaluate:
  - Customer satisfaction
  - Brand perception

⚠️ **Limitations**
- Only positive/negative sentiments (no neutral class)
- May misinterpret sarcasm or mixed-emotion reviews
- Time-based trends not analyzed (no temporal data)

---

## 📊 Key Insights

- **Electronics** is the most dominant category
- Products with higher review counts generally indicate stronger customer trust
- Sentiment distribution varies across categories
- Discounts do not always guarantee positive sentiment or higher ratings

---

## 💡 Business Implications

- Focus promotions on high-volume, positively-reviewed categories
- Identify categories needing quality improvement
- Combine review volume with sentiment to evaluate brand health better than ratings alone

---

## 📁 Repository Structure


## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/amazon-review-analysis.git
cd amazon_data_analysis
```

# Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn transformers torch
```
# Open the notebook:
```bash
jupyter notebook
```

# Run all cells sequentially.

# 👤 Author

Suyog Poudel
Aspiring Data Analyst | Python | Data Analysis | NLP
