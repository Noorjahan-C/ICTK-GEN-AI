# 🚀 ICTK Machine Learning & Generative AI - Starter Pack

Welcome to the ICTK Machine Learning & Generative AI Training Program.

This starter pack will help you set up your development environment and prepare for hands-on sessions during the course.

---

# 📋 Software Requirements

Before starting the course, please install the following software:

| Software | Purpose |
|-----------|----------|
| Python 3.12+ | Programming Language |
| VS Code | Code Editor |
| Git | Version Control |
| Jupyter Notebook | Interactive Coding Environment |

---

# 🐍 Step 1: Install Python

### Download Python

https://www.python.org/downloads/

### Installation Steps

1. Download the latest stable version.
2. Run the installer.
3. Check:

```
Add Python to PATH
```

4. Click **Install Now**.

### Verify Installation

Open Command Prompt and run:

```bash
python --version
```

Expected output:

```bash
Python 3.12.x
```

---

# 💻 Step 2: Install VS Code

Download:

https://code.visualstudio.com/

Install using default settings.

---

# 🔧 Step 3: Install Git

Download:

https://git-scm.com/download/win

Verify installation:

```bash
git --version
```

Example output:

```bash
git version 2.xx.x
```

---

# 📁 Step 4: Create a Project Folder

```bash
mkdir ICTK_ML_GenAI
cd ICTK_ML_GenAI
```

---

# 🌐 Step 5: Create a Virtual Environment

Create virtual environment:

```bash
python -m venv venv
```

Activate environment:

```bash
venv\Scripts\activate
```

You should see:

```bash
(venv)
```

at the beginning of the terminal.

---

# 📦 Step 6: Install Required Libraries

Install all required packages:

```bash
pip install -r requirements.txt
```

---

# 📓 Step 7: Install and Launch Jupyter Notebook

Install:

```bash
pip install notebook
```

Launch:

```bash
jupyter notebook
```

A browser window will automatically open.

---

# ⚙️ VS Code Setup

## Install Recommended Extensions

Open VS Code and install:

### Python Development

- Python
- Pylance
- Jupyter

### Git Support

- GitLens

### Data Science

- Data Wrangler
- Excel Viewer

### AI Development

- GitHub Copilot
- Gemini Code Assist

---

# 📝 Git Basics

## Configure Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

## Clone Repository

```bash
git clone <repository_url>
```

## Check Status

```bash
git status
```

## Add Files

```bash
git add .
```

## Commit Changes

```bash
git commit -m "Initial Commit"
```

## Push Changes

```bash
git push origin main
```

## Pull Latest Updates

```bash
git pull origin main
```

---

# 🐼 Python Libraries Used in This Course

## Data Manipulation

- NumPy
- Pandas

## Data Visualization

- Matplotlib
- Seaborn

## Machine Learning

- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost

## Explainable AI

- SHAP

## Generative AI

- OpenAI SDK
- Google Generative AI SDK

## Application Development

- Streamlit

---

# 📂 Course Structure

## Day 1: Python & Data Foundations

- Introduction to AI, ML and GenAI
- NumPy
- Pandas
- Data Loading
- Data Cleaning
- Data Visualization
- Matplotlib
- Seaborn

---

## Day 2: Supervised Machine Learning

- Machine Learning Workflow
- Regression
- Classification
- Model Training
- Validation
- Evaluation Metrics

---

## Day 3: Model Optimization & Unsupervised Learning

- Feature Engineering
- Overfitting and Underfitting
- Hyperparameter Tuning
- Cross Validation
- Clustering
- Dimensionality Reduction

---

## Day 4: Generative AI & LLMs

- Introduction to Generative AI
- Large Language Models
- Prompt Engineering
- Zero-Shot Prompting
- Few-Shot Prompting
- API Usage
- Responsible AI

---

## Day 5: Integrating ML with GenAI

- ML + GenAI Integration
- Explainable AI
- SHAP
- Automated Insights
- Streamlit Applications
- Best Practices

---

# 🚨 Common Issues

## Python Not Found

Error:

```bash
'python' is not recognized
```

Solution:

Reinstall Python and ensure:

```text
✔ Add Python to PATH
```

was selected.

---

## Pip Not Found

Run:

```bash
python -m ensurepip --upgrade
```

---

## Virtual Environment Not Activating

Open PowerShell as Administrator and run:

```bash
Set-ExecutionPolicy RemoteSigned
```

---

## Module Not Found

Install the missing package:

```bash
pip install package_name
```

---

# 📚 Learning Resources

### Python Documentation

https://docs.python.org/

### NumPy Documentation

https://numpy.org/doc/

### Pandas Documentation

https://pandas.pydata.org/docs/

### Scikit-Learn Documentation

https://scikit-learn.org/

### Streamlit Documentation

https://docs.streamlit.io/

### OpenAI Documentation

https://platform.openai.com/docs

### Google Gemini Documentation

https://ai.google.dev/

---

# 🎯 Course Outcome

By the end of this program, participants will be able to:

✅ Perform data preprocessing using Python

✅ Build machine learning models

✅ Evaluate and optimize ML models

✅ Understand and use Generative AI tools

✅ Design effective prompts

✅ Use LLM APIs

✅ Integrate Machine Learning with Generative AI

✅ Develop lightweight AI applications using Streamlit

---

**Happy Learning! 🚀**
