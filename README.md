# Session 1 — Intro to Data Course

This repository contains the materials for **Session 1** of *Intro to Data Course*.  
- Slides: see [`slides/`](./slides/) folder  
- Notebooks: see [`notebooks/`](./notebooks/) folder 
---

## 📑 Session Outline

1. **Course Introduction**
   - What is Data Analytics and Data Mining?
   - Course structure and semester project
   - Who are you, and what do you want to get out of the course?

2. **Reproducible Data Analysis**
   - Why version control matters
   - Git vs GitHub/GitLab
   - Setting up your course repository

3. **What Is Data?**
   - Where data comes from
   - How data collection shapes what we can learn
   - Finding and evaluating datasets

4. **The Data Lifecycle**
   - Data generation and collection
   - Preprocessing
   - Analysis and interpretation
   - Data retention and destruction

5. **Types of Data**
   - Structured
   - Semi-structured
   - Unstructured

6. **From Programming to Machine Learning**
   - Classical programming vs machine learning
   - When machine learning is useful
   - A first look at the relationship between AI, ML, statistics, data mining, and data analytics

7. **Your Course Project**
   - Form groups
   - Choose a real dataset
   - Define a research question
   - What makes a good research question?
   - FINER criteria

8. **Before Next Week**
   - Get the course environment running
   - Form your project group
   - Draft 2–3 possible research questions


---
## 🚀 Environment Setup

Before starting, please **fork this repository** and create a fresh Python virtual environment.  
All required libraries are listed in `requirements.txt`.

> ⚠️ If you encounter errors during `pip install`, try removing the version pinning for the failing package(s) in `requirements.txt`.  
> On Apple M1/M2 systems you may also need to install additional system packages (the “M1 shizzle”).

---

### macOS / Linux (bash/zsh)

```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate

# Upgrade pip and install dependencies
pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
.venv\Scripts\Activate.ps1

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (Git Bash)
```bash
# Select Python version (if using pyenv)
pyenv local 3.11.3

# Create and activate virtual environment
python -m venv .venv
source .venv/Scripts/activate

# Upgrade pip and install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
```

You’re now ready to run the session notebooks!

Deactivate the environment when you’re done:
```bash
deactivate
```
