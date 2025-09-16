# Pharmacovigilance-Drug-Safety-Analysis
An end-to-end Data Science project on Pharmacovigilance using EDA, NLP, Topic Modeling &amp; Dashboarding for drug safety insights
# 💊 Pharmacovigilance Drug Safety Analysis

An end-to-end Data Science project on **Pharmacovigilance** using **EDA, NLP, Topic Modeling, and Interactive Dashboards** to analyze **drug safety and adverse drug reactions (ADRs)**.

---

## 📖 Problem Statement
Pharmacovigilance plays a critical role in ensuring drug safety by identifying and analyzing **adverse side effects** reported by patients.  
The goal of this project is to extract insights from drug reviews, identify hidden patterns using **topic modeling**, and present results with a **dashboard for healthcare decision-making**.

---

## 📊 Dataset
- **Source:** Open-source drug review datasets (side effects & patient experiences).  
- **Size:** ~ Several thousand drug reviews.  
- **Features:**  
  - `Drug Name`  
  - `Condition`  
  - `Side Effects / Review Text`  
  - `Rating`  
  - `Date`  

---

## 🛠️ Project Workflow
### 1. Data Cleaning
- Removed duplicates, null values, and irrelevant characters.  
- Cleaned side-effect text using **regex & NLP preprocessing**.  

### 2. Exploratory Data Analysis (EDA)
- Most prescribed drugs.  
- Most common conditions.  
- Distribution of ratings.  
- Side effect frequency analysis.  

### 3. NLP & Machine Learning
- **Topic Modeling (LDA):** Extracted top 5 topics from side effect reviews.  
- **Word Clouds:** Generated for each topic to visualize frequent terms.  
- **Sentiment Analysis:** Classified reviews into Positive / Neutral / Negative.  

### 4. Dashboard
- Built **interactive Tableau dashboard** for drug safety analysis.  
- Included filters for **Drug, Condition, Rating, and Side Effects**.  
- Visuals: Bar charts, pie charts, trend lines, and topic insights.  

---

## 📈 Results & Insights
- Identified **most reported side effects** for critical drugs.  
- Topic modeling revealed **5 distinct groups of side effects**.  
- Sentiment analysis highlighted **patient concerns vs satisfaction**.  
- Dashboard enables **quick comparison between drugs & conditions**.  

---

## 🚀 How to Run
### Requirements
```bash
pip install -r requirements.txt
