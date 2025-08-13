# Project Title:  What Fuels the Seed? Bayesian Insights From Tunisia

**Predicting early-stage venture performance using a hybrid Bayesian modeling approach.**

## 📖 Project Overview
This project examines how **founder and startup characteristics influence early-stage venture performance** within the Tunisian entrepreneurial ecosystem. Using data from **75 startups backed by Flat6Labs Tunisia (2017–2022)**, it predicts two key outcomes: **revenue growth** and **external investment acquisition**.  

A **hybrid modeling approach** combining regression analysis and Bayesian methods allows robust predictions despite limited data and high variability. Results emphasize the importance of **founder full-time commitment, educational background, technical expertise, and ecosystem support**.  

This study provides a **probabilistic, evidence-based evaluation framework** that helps investors, accelerators, and policymakers make more informed decisions in emerging markets.

---
## 🛠️ Tech Stack
- **Python Libraries:**
  - Data manipulation: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Statistical analysis: `scipy.stats`, `patsy`, `skew`, `boxcox`, `yeojohnson`, `boxcox1p`  
  - Bayesian modeling: `pymc`, `arviz`, `pytensor`  

## 📂 Project Structure
├── startup_success_modeling.ipynb # Main Jupyter Notebook
├── /data # Dataset folder (optional/sample data)
├── requirements.txt # Dependencies
└── README.md # Project description

# Clone the repository
git clone https://github.com/hyba-ab/startup-success-modeling.git

# Navigate to project folder
cd startup-success-modeling

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# Install dependencies
pip install pandas numpy matplotlib seaborn scipy arviz patsy pymc pytensor jupyter

# Launch Jupyter Notebook
jupyter notebook startup_success_modeling.ipynb
