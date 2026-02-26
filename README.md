# Student Sleep Patterns – Machine Learning Analysis

## Project Overview
This project analyzes student sleep and lifestyle patterns using machine learning techniques.  
The objective is to identify behavioral clusters and detect potential outliers based on sleep duration, study hours, caffeine intake, and related variables.

This project was developed as part of a Data Science and Machine Learning course.

---

## Dataset Description
The dataset contains 500 samples with:

### Numerical Variables
- Study_Hours  
- Sleep_Duration  
- Caffeine_Intake  
- Physical_Activity  
- Sleep_Quality  
- Weekday_Sleep_Start  
- Weekday_Sleep_End  
- Weekend_Sleep_Start  
- Weekend_Sleep_End  

### Categorical Variables
- Gender  
- University_Year  

---

## Methodology

### 1. Data Preprocessing
- Handling categorical encoding  
- Feature scaling (Standardization / Normalization)  
- Feature selection (SelectKBest)  

### 2. Dimensionality Reduction
- PCA  
- t-SNE  

### 3. Clustering Methods
- KMeans  
- DBSCAN  
- Gaussian Mixture Model (GMM)  

### 4. Outlier Detection
- Isolation Forest  
- Local Outlier Factor (LOF)  
- One-Class SVM  

---

## Key Results
- Identified distinct student behavior clusters based on sleep and study patterns.  
- Observed relationships between caffeine intake and sleep quality.  
- Detected outlier profiles representing extreme lifestyle patterns.  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## How to Run
1. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
