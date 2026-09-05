# Advanced Google Play NLP Analyzer

An end-to-end NLP and machine learning based application for analyzing
Google Play Store reviews and extracting actionable product insights.

## 📌 Project Overview

This project analyzes Google Play Store reviews using Natural Language
Processing and machine learning techniques.

The system performs:
- Review scraping
- Text preprocessing
- Topic analysis
- Version-wise analysis
- Issue clustering
- Trend analysis
- Aspect-based sentiment analysis
- Sentiment classification

## 🚀 Key Features

### 1. Review Scraping
Fetches Google Play Store reviews for a selected application.

### 2. NLP Preprocessing
- Text cleaning
- Stopword removal
- Lemmatization
- App-version normalization

### 3. Topic Analysis
Identifies terms that occur more frequently in low-rated and high-rated
reviews to surface potential problems and positive themes.

### 4. Version Analysis
Analyzes review activity and user ratings across different app versions.

### 5. Issue Clustering
Uses TF-IDF and K-Means clustering to group reviews into common issue
categories.

### 6. Trend Analysis
Tracks specific issues across app versions using OR and AND keyword logic.

### 7. Aspect-Based Sentiment Analysis
Identifies sentiment associated with specific app aspects such as:
- Calls
- Messages
- Notifications
- Media
- Privacy
- Backup
- Groups
- Performance
- Updates

### 8. Machine Learning
Uses TF-IDF based machine learning models for sentiment classification
and model evaluation.

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- spaCy
- Matplotlib
- Streamlit
- Google Play Scraper

## 🔄 Project Workflow

Google Play Reviews
        ↓
Data Collection
        ↓
Preprocessing
        ↓
EDA & Topic Analysis
        ↓
Version Analysis
        ↓
Issue Clustering
        ↓
Trend Analysis
        ↓
Aspect Sentiment
        ↓
ML Evaluation

## ⚙️ Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd google-play-review-intelligence