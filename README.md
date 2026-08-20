# Internship Recommender (ML System)

**Machine Learning Career Recommendation Engine**

> **Note**: This repository is a fork of `Shivam-dev30/internship-recommender` with modifications to its deployment structure and CI/CD pipelines to run on Railway and conform to standard engineering practices.

## 🚀 Live Demo
- **Live Link**: [https://internshiprecommender.up.railway.app](https://internshiprecommender.up.railway.app)

## ⚙️ Setup Instructions

### Environment Setup
Create a `.env` file based on `.env.example`:
```bash
cp .env.example .env
```

### Running Locally
```bash
pip install -r requirements.txt
python app.py
```

## 🛡️ Security
- Environment files (`.env`) and virtual environments (`venv`) are ignored from source control.

## Deployment
Deployed via Railway using the included `Procfile`.
