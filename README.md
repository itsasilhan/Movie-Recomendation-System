#  Movie Recommendation System

This project is a movie recommendation system that suggests similar movies based on genre similarity and predicted ratings. It combines data parsing, preprocessing, machine learning, and an interactive web application built with Streamlit.

---

##  Project Overview

The system performs the following steps:

- Parses movie data (Top 250 movies) from IMDb using JSON  
- Cleans and preprocesses the dataset  
- Applies machine learning models to predict movie ratings  
- Computes similarity between movies using cosine similarity  
- Provides an interactive dashboard for users to explore recommendations  

---

## Data Source

- IMDb Top 250 Movies  
- Source: https://www.imdb.com/chart/top/

---

##  Features

-  Select a movie and get similar recommendations  
-  Predict movie ratings using ML models  
-  Data preprocessing and feature engineering  
-  Content-based filtering using cosine similarity  
-  Interactive UI built with Streamlit  

---

##  How It Works

1. **Data Collection**  
   Movie data is parsed from IMDb (Top 250) using JSON format.

2. **Data Preprocessing**  
   - Cleaning missing values  
   - Feature extraction (genres, metadata)  
   - Vectorization of features  

3. **Machine Learning**  
   - Multiple models are tested to predict movie ratings  
   - Model performance is evaluated  

4. **Recommendation System**  
   - Cosine similarity is used to find similar movies  
   - Recommendations are based on genre similarity  

5. **Frontend (Streamlit)**  
   - User selects a movie  
   - System displays top similar movies instantly  

---

##  Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Streamlit  
- JSON  

---

## Installation & Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/movie-recommendation-system.git
