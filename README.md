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


# 📊 Task-2 : Stock Price Analysis and Technical Indicator Dashboard

## 🧾 Project Overview
This project involves loading and analyzing stock price data using Python, TA-Lib, and PyNance to calculate key financial indicators and visualize insights. The goal is to prepare clean data, apply technical analysis, and create an interactive dashboard-ready dataset for stock market insights.

---

## ✅ Features
- Load and clean historical stock price data (Open, High, Low, Close, Volume)
- Compute technical indicators using **TA-Lib**:
  - Moving Averages (SMA, EMA)
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
- Extract financial metrics using **PyNance**
- Generate visualizations for trend analysis and signal interpretation
- Follow best practices in version control using Git and GitHub



---

## 🔧 Tools & Libraries
- Python (Pandas, Matplotlib, Seaborn)
- TA-Lib (Technical Analysis Library)
- PyNance (Financial metrics)
- Git & GitHub

---

## 📌 Workflow Summary
- Merged essential changes from `task-1` into `main` using a **Pull Request**
- Created a new development branch `task-2` for ongoing dashboard development
- Committed all progress with descriptive messages for clear version tracking

---

## 📈 Key KPIs
- **Proactivity**: Used external resources and documentation to implement tools
- **Accuracy**: Verified indicators against expected trends
- **Completeness**: Full pipeline from data prep to indicator calculation and visualization

---

## 📊 Sample Output
Visualizations include:
- Price with SMA/EMA overlays
- RSI and MACD signal plots
- Volume distribution and trendlines

---

## 🚀 Next Steps
- Integrate visualizations into an interactive dashboard
- Expand analysis with additional financial metrics
- Explore predictive modeling using indicator data

---





---






## 🖊️ Author
- Maintained by Menbere Hailu
- 📧 menberehailu.w@gmail.com
- 🌐 GitHub: MenbereHailu