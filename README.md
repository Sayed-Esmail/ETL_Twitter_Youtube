# 📊 Social Media ETL Pipeline

## 📌 Overview
This project implements an **ETL (Extract, Transform, Load) pipeline** that fetches social media posts from **Twitter** and **YouTube**, normalizes the data, and stores it in a unified dataset.  
It also computes engagement metrics such as **daily engagement** and **top posts**.

---

## 📂 Files
- `main.ipynb` → Jupyter Notebook with step-by-step pipeline execution.
- `master_dataset.csv` → Unified dataset of fetched posts (Twitter + YouTube).  
- `README.md` → Instructions to set up and run the project.  
- `.env` → (Not uploaded, you need to create this file locally with your API keys).  

---

## ⚙️ Requirements
Install required libraries:
```bash
pip install pandas  requests
