#  Study-Track – AI-Based Student Study Habit Recommender

##  Project Overview

**Study-Track** is an AI-based system designed to analyze students' study habits and generate **personalized study recommendations**. The project uses data analysis and machine learning techniques to help students improve productivity, consistency, and academic performance.

---

##  Problem Statement

Students often struggle with:

* Poor time management
* Ineffective study routines
* Lack of personalized guidance

Traditional one-size-fits-all study plans are inefficient. This project addresses the problem by using **AI-driven analysis** to recommend customized study strategies based on individual student data.

---

##  Solution Approach

The system:

1. Collects student study-related data
2. Preprocesses and normalizes the data
3. Groups students using **clustering techniques**
4. Applies AI-based logic to generate **personalized study plans**
5. Outputs clear, actionable study recommendations

---

##  Project Architecture

```
Student Data (CSV / Input)
        ↓
Data Preprocessing
        ↓
Clustering Model (ML)
        ↓
Student Group Identification
        ↓
Recommendation Engine
        ↓
Personalized Study Plan
```

---

##  Project Structure

```
Study-Track-AI-Based-Student-Study-Habit-Recommender/
│
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
│
├── data/
│   ├── raw/
│   │   └── student.csv
│   └── processed/
│       ├── study_log_export.csv
│       └── cluster_output.csv
│
├── database/
│   └── students.db
│
├── models/
│   ├── student_cluster_model.pkl
│   └── student_scaler.pkl
│
└── notebooks/
    ├── Clustering.ipynb
    ├── Recommendation_Engine.ipynb
    └── Study_Track.ipynb   ← Main execution notebook
```

---

##  Notebook Description

###  Clustering.ipynb

* Trains a clustering model on student data
* Groups students based on study habits
* Saves trained model and scaler

###  Recommendation_Engine.ipynb

* Loads trained model
* Predicts student cluster
* Generates study recommendations

###  Study_Track.ipynb (MAIN FILE)

* End-to-end execution notebook
* Integrates data, model, and recommendation logic
* Produces final personalized study plan



---

## Technologies Used

* **Python**
* **Pandas & NumPy** – Data processing
* **Scikit-learn** – Machine learning (Clustering)
* **Matplotlib / Seaborn** – Visualization
* **Jupyter Notebook** – Development environment
* **SQLite** – Database storage

---

##  How to Run the Project

###  Option 1: Run on Google Colab (Recommended)

1. Open [https://colab.research.google.com](https://colab.research.google.com)
2. Upload `Study_Track.ipynb`
3. Upload `data/` and `models/` folders if prompted
4. Click **Runtime → Run all**

---

###  Option 2: Run Locally

#### Step 1: Install Dependencies

```bash
pip install -r requirements.txt
```

#### Step 2: Launch Jupyter Notebook

```bash
jupyter notebook
```

#### Step 3: Open and Run

* Open `notebooks/Study_Track.ipynb`
* Click **Run → Run All Cells**

---

##  Sample Output

* Student study habit classification
* Personalized subject-wise study plan
* Time management suggestions
* Improvement recommendations

---

##  System Overview

> “Study-Track is an AI-based student study habit recommender system that analyzes student data, groups students using clustering, and generates personalized study plans to improve learning efficiency and academic performance.”

---

##  Future Enhancements

* Google Calendar Integration
* Automatic Study Timetable Creation
* Web application using **Streamlit**
* Real-time student input form
* Deep learning-based recommendation model
* Mobile app integration
* Performance tracking dashboard

---

## Team Members & Contributions

| Team Member       | GitHub Profile | Role                 | Key Contributions |
|-------------------|---------------|----------------------|-------------------|
| **Astle Joe A S** | [astlejoe789](https://github.com/astlejoe789) | AI Engineer | K-Means clustering model development, student behavior analysis |
| **Megharaj Koli** | [MegharajKoli](https://github.com/MegharajKoli) | Backend Developer | FastAPI server, SQLite database, user authentication |
| **Ravilla Monika** | [RavillaMonika](https://github.com/RavillaMonika) | ML Logic Specialist | Recommendation engine logic, mapping clusters to insights |
| **Akash A** | [Akash-2006-07-03](https://github.com/Akash-2006-07-03) | Frontend Developer | Streamlit UI, interactive dashboard, data visualizations |
| **Venusri** | [Venu504](https://github.com/Venu504) | Data Engineer | Data collection, preprocessing, feature engineering |


---

## License

This project is licensed under the MIT License.

---

 *Designed as an academic AI/ML project with practical impact on student learning.*
