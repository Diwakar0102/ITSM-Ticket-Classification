# 🖥️ ITSM Ticket Classification

## 📌 Project Overview
This live project focuses on **classifying IT Service Management (ITSM) tickets** into categories (e.g., Software, Hardware, Network, Access Issues) using machine learning.  
The goal is to reduce manual effort and improve response times in IT support.  

## 🎯 Objective
- Automate the classification of incoming IT support tickets.  
- Enable faster triage and assignment to the right support team.  

## 📂 Dataset
The dataset contains IT ticket details such as:  
- Ticket ID  
- Short Description / Description  
- Category & Subcategory  
- Priority, Incident Type  

*(Dataset not included due to confidentiality. Use sample ITSM datasets for replication.)*  

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- NLP Libraries (NLTK / spaCy)  
- Matplotlib, Seaborn  

## 📊 Approach
1. Data Cleaning & Text Preprocessing (Tokenization, Stopword Removal, Lemmatization)  
2. Feature Extraction using TF-IDF  
3. Model Training (Logistic Regression, Naive Bayes, Random Forest, etc.)  
4. Model Evaluation using Accuracy, F1-Score  
5. Deployment-ready pipeline for classification  

## 🚀 Results
- Achieved **88% accuracy** in ticket classification.  
- NLP preprocessing improved classification performance significantly.  

## 📌 Requirements
Install dependencies using:  
```bash
pip install -r requirements.txt

