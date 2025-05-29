# Task 1: Git and GitHub

## 📌 Overview
This task demonstrates the setup and use of **Git** and **GitHub** in a Python development environment, along with a basic CI/CD workflow. It includes environment configuration, version control, and a continuous integration pipeline to ensure code quality and collaboration readiness.

## 🧩 Key Objectives
- Setting up a Python development environment.
- Implementing Git for version control.
- Setting up GitHub Actions for CI/CD.
- Demonstrating relevant skills in software development best practices.

## 📊 Key Performance Indicators (KPIs)
- ✅ Development environment successfully set up.
- ✅ Version control with Git properly configured.
- ✅ CI/CD workflow integrated via GitHub Actions.
- ✅ Relevant technical skills demonstrated clearly and effectively.

## 📁 Folder Structure
├── .vscode/ # VS Code specific settings
│ └── settings.json
├── .github/ # GitHub Actions workflows
│ └── workflows/
│ └── unittests.yml
├── .gitignore # Files to ignore in version control
├── requirements.txt # Python dependencies
├── README.md # Project overview and documentation
├── src/ # Source code files
│ └── init.py
├── notebooks/ # Jupyter notebooks and analysis
│ ├── init.py
│ └── README.md
├── tests/ # Unit tests
│ └── init.py
└── scripts/ # Utility or setup scripts
├── init.py
└── README.md


## ⚙️ Setup Instructions
1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd <project-folder>

2. **Create and activate a virtual environment**
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
3. Install  dependancy 
   pip install -r requirements.txt


## 🚀 CI/CD Pipeline
- GitHub Actions is used for continuous integration.
- Workflow file: .github/workflows/unittests.yml
- Automatically runs unit tests when pushing code or creating a pull request.

## 🧪 Testing
- Unit tests are located in the tests/ directory.
To run manually 
     python -m unittest discover tests


