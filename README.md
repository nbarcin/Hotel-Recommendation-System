# 🏨 Hotel Recommendation System

A content-based recommendation system that suggests hotels based on user preferences and location using Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

In the era of digital travel platforms, choosing the right hotel has become increasingly complex due to the overwhelming number of available options. Recommendation systems play a vital role in simplifying this decision-making process by providing personalized suggestions based on user preferences.

In this project, we develop a **content-based hotel recommendation system** using a large-scale dataset of over 500,000 hotel reviews. The dataset includes key information such as hotel names, locations, review scores, user-generated tags, and textual feedback.

To generate meaningful recommendations, we focus on two main inputs:

- 📍 Location (country)  
- 📝 User preference (free-text description)  

We apply Natural Language Processing (NLP) techniques—including tokenization, stopword removal, and lemmatization—to extract meaningful keywords from both user input and hotel tags. By measuring the similarity between these processed texts, the system identifies hotels that best match the user's intent.

The goal of this project is to demonstrate how simple yet effective NLP-based techniques can be used to build an interpretable and practical recommendation system.

---

## 📊 Dataset

The dataset contains large-scale hotel review data, including:

- `Hotel_Name` → Name of the hotel  
- `Hotel_Address` → Location information  
- `Average_Score` → Overall hotel rating  
- `Reviewer_Score` → Individual user rating  
- `Tags` → User-generated tags (key feature)  
- `countries` → Country information  

---

## 🧠 Methodology

### 🔹 Text Processing
- Lowercasing  
- Tokenization  
- Stopword removal  
- Lemmatization  

### 🔹 Feature Engineering
- Cleaned and normalized text data  
- Tag-based representation of hotels  
- User query preprocessing  

### 🔹 Recommendation Logic
- Similarity-based matching using keyword overlap  
- Ranking by:
  - Similarity score  
  - Average hotel rating  

---

## 🤖 Model Approach

This project uses a **content-based filtering approach**, which means:

- No user history required  
- Recommendations are based on item similarity  
- Fully interpretable results  

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/hotel-recommendation-system.git
cd hotel-recommendation-system
