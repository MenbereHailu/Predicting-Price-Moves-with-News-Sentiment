# 📁 Task 1: Setup, GitHub Integration & Exploratory Data Analysis (EDA)

## 🎯 Objective

This task focuses on:
- Setting up a reproducible Python data science environment
- Initializing Git and GitHub for version control
- Implementing CI with GitHub Actions
- Performing Exploratory Data Analysis (EDA) on financial news headlines

---

## ✅ Task Checklist

### 1. Setup & Version Control
- [x] Create GitHub repository
- [x] Create and switch to a new branch: `task-1`
- [x] Setup Python virtual environment
- [x] Add `requirements.txt` with required libraries (e.g., `pandas`, `seaborn`, `nltk`, etc.)
- [x] Add `.gitignore` to exclude unnecessary files
- [x] Create folder structure (see below)
- [x] Add initial `README.md` file
- [x] Setup GitHub Actions for Continuous Integration (CI)

### 2. Exploratory Data Analysis (EDA)
- [x] Load and inspect news dataset
- [x] Analyze:
  - Headline lengths
  - Article counts by publisher
  - Article counts by date
  - Publishing frequency over time
  - Hour-of-day publishing trends
  - Publisher domain distribution
- [x] Visualize results using bar charts, histograms, and line plots

---

## 📁 Folder Structure

<pre> ``` ├── .github/ │ └── workflows/ │ └── unittests.yml # GitHub Action for CI (unit test runner) ├── data/ │ └── news_data.csv # Raw news dataset ├── notebooks/ │ └── 01_eda_news.ipynb # Jupyter Notebook for EDA ├── scripts/ │ └── data_loader.py # Helper script to load/clean data ├── tests/ │ └── test_loader.py # Unit tests for data loading ├── requirements.txt # Python dependencies ├── .gitignore # Files/folders to ignore in Git ├── README.md # Project overview (this file) ``` </pre>


---

## 📦 Required Libraries

Install all dependencies with:

```bash
pip install -r requirements.txt
```
Example packages:

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- pytest
- jupyter

📊 Outputs
Key plots and summaries will be stored in outputs/ (optional).



## 🖊️ Author
- Maintained by Menbere Hailu
- 📧 menberehailu.w@gmail.com
- 🌐 GitHub: MenbereHailu