# My Thriving Child – Data Analyst Interview Task

A social‑media performance analysis and dashboarding exercise for the Data Analyst Internship at *My Thriving Child*.

![Screenshot (125)](https://github.com/user-attachments/assets/680712a9-2771-4ee2-b6ce-a57bbf3da4fa)

---

## Project Overview

This repository contains everything you need to:
1. **Clean & explore** the provided Instagram & Facebook datasets with Python.  
2. **Build** a Power BI dashboard summarizing key social media KPIs.  
3. **Report** on insights and recommendations.

---

## 📁 Repository Structure

```

My‑Thriving‑Child‑Task/
├── data/
│   ├── raw/
│   │   ├── Copy of Instagram\_Analytics - DO NOT DELETE (for interview purposes) - Instagram Profile Overview\.csv
│   │   └── Copy of Facebook\_Analytics - DO NOT DELETE (for interview purposes) - Facebook Profile Overview\.csv
│   └── cleaned/
│       ├── Instagram\_Analytics\_Cleaned.csv
│       └── facebook\_profile\_overview\_cleaned.csv
├── notebooks/
│   ├── Instagram\_script.ipynb    # Data cleaning & exploratory analysis (Instagram)
│   └── Facebook\_script.ipynb     # Data cleaning & exploratory analysis (Facebook)
├── dashboard/
│   └── Social Media Performance Dashboard.pbix   # Power BI file
├── report/
│   └── REPORT.docx               # Written summary of insights & recommendations
└── README.md                     # This file

````

---

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/sai-forge/My-Thriving-Child-Task.git
cd My-Thriving-Child-Task
````

### 2. Inspect & clean data

1. Open **`notebooks/Instagram_script.ipynb`** and **`notebooks/Facebook_script.ipynb`** in JupyterLab or Jupyter Notebook.
2. Install dependencies (if needed):

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Run each notebook end-to-end to generate cleaned CSVs in `data/cleaned/`.

### 3. View the Dashboard

* Open **`dashboard/Social Media Performance Dashboard.pbix`** in Power BI Desktop.
* Explore the 3 pages:

  * **Intro**:  Key Performance Indicators for Instagram & Facebook
  * **Page 1**: KPI Overview and & Monthly Trend Analysis
  * **Page 2**: Engagement and Post Type Performance

### 4. Read the Report

* See **`report/REPORT.docx`** for a written summary of:

  * Key performance metrics tracked
  * A/B‑testing approach for ads
  * Insights & recommendations
  * Additional analyses to consider

---

##  Key Performance Indicators

* **Instagram**: New followers, profile impressions, reach, visits, engagement, share/Reel share breakdown
* **Facebook**: Net likes, page followers, impressions, reach, reactions, post engagements
* **Comparisons**: Reels vs static posts, organic vs paid reach, quarterly content‑type performance

---

##  Recommendations

> **(See full discussion in `report/REPORT.docx`)**

* Reels drive \~87% of Instagram shares—focus on short‑form video content.
* Engagement peaked in April; consider replicating top‑performing posts.
* Paid reach is \~36%, balance budget between organic and paid campaigns.
* A/B test creative variables (image vs headline) to optimize CTR & conversions.
* Future analyses: time‑of‑day performance, follower cohort analysis, sentiment analysis of comments.

---

##  Contributing

This repo was created for a single interview task. If you have feedback or suggestions, please open an issue or reach out directly.

---

## 📄 License

*This content is provided for demonstration/interview purposes only.*
© 2025 *My Thriving Child* | Prepared by George
