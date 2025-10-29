# 🚀 JobDash: The AI Jobs Market Dashboard
Welcome to JobDash, your comprehensive dashboard for analyzing the ever-evolving Artificial Intelligence job market! This project combines detailed data analysis with powerful visualization to uncover key trends in AI salaries, skills, and industry demands.

---

## Project Overview  
**Analyze 15,000+ AI job postings** to uncover **salary trends, top skills, remote work**, and more!  
Built for **beginners** using **pandas + matplotlib** — **clean, simple, job-ready code**  

---

## Dataset (`ai_job_dataset.csv`)  
| Column | Meaning |
|--------|--------|
| `job_id` | Unique ID |
| `job_title` | Role name |
| `salary_usd` | Salary in USD |
| `experience_level` | EN, MI, SE, EX |
| `company_size` | S, M, L |
| `remote_ratio` | 0%, 50%, 100% |
| `required_skills` | Comma-separated list |
| `posting_date` | When job was posted |

---

## 10 Business Problems Solved  

| # | Problem |
|---|--------|-----------|
| 1 | **Average Salary by Experience** | EX: **$180K** |
| 2 | **Top 5 Highest-Paying Roles** | ML Engineer: **$160K** |
| 3 | **Salary by Company Size** | Large (L): **$110K** |
| 4 | **Which Company Size Pays Most?** | **L > M > S** |
| 5 | **Experience vs Salary Correlation** | **r = 0.69** (Strong) |
| 6 | **Remote Work Distribution** | **37% on-site, 34% full remote** |
| 7 | **Top 5 Industries by Benefits** | Consulting: **8.1/10** |
| 8 | **Top 10 Industries by Jobs** | Finance: **10 jobs** |
| 9 | **Salary by Education** | Associate: **$115K** |
| 10| **Job Postings by Month** | **June & August** peak |

---

## Tools Used  
- `pandas` – Data cleaning & analysis  
- `matplotlib` – Simple charts  
- `numpy` – Math & stats  

---

## 📊 Key Analysis & Insights
The data analysis covers a dataset of 15,000 AI job entries and provides key insights into:

Average Salaries: Analyze salary distribution globally (in USD) to understand the financial landscape of AI roles.

Fun Fact: The dataset shows salaries ranging from approximately $32k USD to nearly $400k USD.

In-Demand Skills: Discover the most frequently required technical skills, such as Python, Deep Learning, SQL, Kubernetes, and more.

Experience vs. Pay: Compare salaries across different experience levels (e.g., Entry, Mid-level, Senior, Executive).

Work Arrangement: Examine the ratio of fully remote (100%), hybrid (50%), and on-site (0%) job opportunities.

Geographic Trends: Identify which industries and countries are hiring the most for AI and Data Science roles.

---

## Category	Tool	Description
Data Analysis	Python	The core programming language for data manipulation.
Data Processing	Pandas, NumPy	Used to load, clean, and transform the AI job data.
Visualization Prep	Matplotlib, Seaborn	Libraries for statistical visualizations and data exploration.
Dashboard	Power BI	Used to create the interactive AI Jobs Dashboard.pbix file.

--- 

## 📁 Repository Structure
aijobs.ipynb: The Jupyter Notebook containing the complete Python data analysis and exploratory data visualization.

AI Jobs Dashboard.pbix: The source file for the interactive Power BI Dashboard.

ai_job_dataset.csv: The dataset used for this project (not included in the file list, but referenced in the notebook).

---

## 💻 Getting Started
Prerequisites
Python 3.x

Jupyter Notebook (or Google Colab)

Microsoft Power BI Desktop (for viewing the .pbix file)

Running the Analysis
Clone the repository:

    git clone https://github.com/swapitsneil/jobdash.git
    cd jobdash
    
Install the required Python libraries:

    pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook:

    jupyter notebook aijobs.ipynb
    
Viewing the Dashboard
Download and install Power BI Desktop.

Open the AI Jobs Dashboard.pbix file directly in Power BI Desktop.

---
✍️ Author
Swapnil Nicolson Dadel - swapitsneil
