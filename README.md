# Email Campaign Performance Analysis

This repository contains a complete data analysis and machine learning pipeline to evaluate and optimize an email marketing campaign for an e-commerce platform.

## Project Objectives
This notebook addresses four key questions:
1. *What percentage of users opened the email and what percentage clicked on the link?*  
2. *Can we build a model to predict click probability and optimize email targeting?*  
3. *By how much could our model improve click-through rates (CTR), and how can we test that?*  
4. *What interesting patterns exist across different segments (email type, country, day, etc.)?*


## Technologies Used
- Python (pandas, scikit-learn, matplotlib, seaborn)
- Jupyter Notebook
- Random Forest for classification
- Data preprocessing with OneHotEncoding & Pipelines

## How to Run

1. Clone the repository:
   - git clone https://github.com/gaurav-chhajer/Email-Campaign-Analysis.git
   - cd email-campaign-analysis

2. Create a virtual environment:
   - python -m venv venv
   - source venv/bin/activate  # or venv\Scripts\activate on Windows

4. Install the dependencies:
   - pip install -r requirements.txt

5. Launch the notebook:
   - jupyter notebook campaign_analysis.ipynb

# Insights Summary
- Personalized, short emails performed better than generic or long ones.
- Users from the UK and US had higher engagement.
- Mid-week (especially Wednesdays) showed peak CTR.
- A trained model could improve CTR by intelligently selecting users more likely to click.
