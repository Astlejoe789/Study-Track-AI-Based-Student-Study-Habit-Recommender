# Study Track – AI Based Student Study Habit Recommender System

## Overview
Study Track is an AI-powered student analytics and recommendation system designed to analyze study behavior and learning patterns to provide personalized study habit recommendations.  
The system leverages machine learning techniques to cluster students based on their academic activity and performance data, enabling data-driven guidance to improve learning efficiency and consistency.

This project was developed as a **team project under the Infosys Internship Program**, following professional software development and repository management practices.

---

## Problem Statement
Students often struggle to maintain effective and consistent study habits due to a lack of personalized guidance. Traditional learning systems do not adapt to individual learning behavior, resulting in reduced academic performance and engagement.

---

## Solution
Study Track addresses this problem by:
- Collecting and analyzing student study logs and performance data
- Applying machine learning–based clustering to identify learning behavior patterns
- Generating personalized study habit recommendations
- Providing visual insights and a simple interaction layer for better understanding

---

## Key Features
- Behavioral analysis of student study patterns
- KMeans-based clustering for learner segmentation
- Personalized study habit recommendations
- Data visualization for performance insights
- Persistent machine learning models for reuse
- Clean, modular, and professional project structure

---

## Technology Stack
- **Programming Language:** Python  
- **Machine Learning:** Scikit-learn  
- **Data Processing:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn  
- **Notebook Environment:** Jupyter / Google Colab  
- **Database:** SQLite  
- **Interface Layer:** Flask / Streamlit  
- **Version Control:** Git & GitHub  

---


---

## Installation and Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```
## Step 2: Install Dependencies
```pip install -r requirements.txt```

# Step 3: Execute the Project

Open the main pipeline notebook:

```notebooks/study_track_pipeline.ipynb```


Run all cells sequentially to perform data analysis, clustering, and recommendation generation.

.

## 📊 Dataset

The project utilizes multiple datasets representing student study behavior and academic activity. These datasets are used to analyze learning patterns, train machine learning models, and generate personalized study habit recommendations.

Dataset Components

Student Profile Data:
Contains basic student-related information required for analysis and identification within the system.

Study Log Data:
Records student study activity, including study duration, frequency, and time-based learning behavior.

Performance Metrics:
Includes academic performance indicators used to correlate study habits with learning outcomes.

Processed & Clustered Data:
Derived datasets generated after preprocessing and machine learning–based clustering, used for recommendation generation and analysis.

⚙️ System Workflow

Student study activity and performance data are collected from datasets.

Data preprocessing and feature engineering are performed.

Students are grouped using KMeans clustering based on behavioral patterns.

Trained models and scalers are saved for reuse.

Personalized study habit recommendations are generated.

Insights are visualized and presented through notebooks or a simple interface.

## 📈 Machine Learning Approach

Clustering Algorithm: KMeans

Purpose: Group students with similar study behavior

Features Used: Study duration, consistency, performance indicators

Output: Cluster labels used to generate personalized recommendations

The model is trained once and persisted using serialized files for efficient reuse without retraining.

## 🧪 Evaluation and Analysis

Cluster distributions are analyzed to understand student learning patterns.

Visualizations are used to interpret study behavior and performance trends.

Recommendation logic is validated using sample student profiles.

## 🔐 Data Privacy & Ethics

All data used in this project is anonymized.

No real personal or sensitive student information is exposed.

The project is intended solely for academic and learning purposes.

## 👥 Team Members

- **[Astle Joe A S](https://github.com/astlejoe789)** 
- **[Megharaj Koli](https://github.com/MegharajKoli)** 
- **[Ravilla Monika](https://github.com/RavillaMonika)** 
- **Akash A**
- **Venusri**
